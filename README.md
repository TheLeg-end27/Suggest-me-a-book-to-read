# Cat or dog
As part of following the fast.ai course, Practical Deep Learning for Coders, I had the idea of training a model to identify cats and dogs. This is the first work following this course. More projects to come. Next up: identifying tumors.
Code was partially used from:
https://www.kaggle.com/code/oralet/is-it-a-bird-creating-a-model-from-your-own-data

Run this command to install the libraries needed.

```
!pip install -Uqq fastai icrawler
```
#Data collection
We first download images from Google, these are some samples of the images.
![cat](./readme_images\cat.png)
![dog](./readme_images\dog.png)
![sample](./readme_images\sample.png)
#Model training
I've used google colab for the model training process, as this can require a lot of processing power. 
![finetune](./readme_images\finetune.png)
![test](./readme_images\test.png)
#Evaluation
With almost 100% accuracy, I was a little surprised to see how far image recognition and the latest have progressed in the past few years. Being able to easily do this would have been unthinkable a decade ago. 
