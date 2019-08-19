# Small web app deploying a CNN built with the [fast.ai](https://www.fast.ai) library

CNN built using the Fast AI library. Model specifications:
- Overview: CNN used to classify oval sports balls into Rugby Balls, Australian Rules Footballs or American Footballs
- Architecture: [ResNet34](https://www.kaggle.com/pytorch/resnet34) (with optimised hyperparameters)
- Data: Training set conisted of 575 images downloaded from Google Images (143 in the validation set). Datasets excluded images that were not photographs of oval sports balls (e.g. hand drawn images, clip-art, GIFs)
- Training: ~10 minutes on a GPU hosted on [Colab](https://colab.research.google.com); 94.4% accuracy
- Supporting materials: Largely follows lesson 2 of the Fast AI [Practical Deep Learning for Coders (v3)](https://course.fast.ai/) course
- Further reading: More on [prolate spheroids here](https://en.wikipedia.org/wiki/Football_(ball))
- Note: We do not discriminate between Rugby Union and Rugby League balls

# Sample images used in CNN training
![oval sports balls](https://github.com/andrewtwort/oval-sports-ball-classifier/blob/master/Oval%20Balls.png)
Sample images: [Wikipedia](https://en.wikipedia.org/wiki/Football_(ball))
