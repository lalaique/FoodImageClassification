# Food Image Classification

This project aims to classify 80 different food categories from 30612 images with deep learning architecture. Four pretrained models are implemented for transfer learning, including VGG16, Xception, InceptionV16, and MobileNetV2. The top 10 layers are frozen to keep some primitive features, and additonaled 4 new layers are also added, including dropout to prevent overfitting. Image data augmentation is also applied to the learning, including zoom, rotation, channel shift, horizontal flip, aiming to improve the ability of the model to generalize. Finally, an ensemble method is also leveraged to improve performance by combining predictions from multiple models. The ensemble method averages out the outputs and successfully reduce the variance of neural network models. As a result, the final accuracy rate goes up to 65% at the test set. The above-mentioned approach method is performed in [transfer_learning.ipynb](https://github.com/lalaique/FoodImageClassification/blob/main/transfer_learning.ipynb).

