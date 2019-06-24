# CNN-Chars74kDataset

Feature Visualization

The above image is a visual representation of what the feature maps detected for the image of number 3. As we scan through the multiple feature maps, we can see that each feature maps strives to recognize certain rudimentary shapes of the characters such as simple edges, simple curves and so on. In case of the number 3, one feature map of the first layer detected the long edge of the three on the right side. Another one detected the downward curves on the hanging parts of the number 3 while a few of them attempted to detect shapes of number 3 from top to down. These feature maps retain most of the information from the image and so, the number 3 is still visible to the naked eye. 


As we get deeper into the convolution layer, each feature map evolves to build on the previous feature maps and gains an ability to recognize complex shapes. In my CNN, there are only two convolution layers and so, the final convolution layer builds on the evolution of the first convolution layer. As it’s apparent from the image above, the final convolution layer dives deeper into abstraction. This increase in vagueness makes it visually less interpretable. On the contrary of what the image of the feature maps look like, the final convolution layer is far more useful and beneficial to the model. In this layer, the feature maps evolve to detect more complex shapes such as corners, joining of two curves and so on. This makes the last layer lose out on more information about the image and gain information about the class of the image. If one more convolution layer was to be added then there is a possibility that the feature maps saturate and don’t learn anything at all. In other words, there would be nothing more to learn from the image. 

