# faceID
Trying out different methods for performing face identification on faces that a model hasn´t seen before. This repo only contains the exploratory ipynb files. At the time of creating this project I did not fully grasp all the methods that I implemented and did not achieve good results. Today, I am confident that I would be able to improve this model but I still gained some valuable insights from this project!

It is based on a siamese neural network that takes an image pair as input and calculates a latent feature for each image. The distance between those latent features then determines if the two faces belong to the same person or not.

![image](https://user-images.githubusercontent.com/59232492/207034900-a6836832-d885-48e5-9cd7-b7f19b41518e.png)

The siamese neural network is more or less the resnet architecture implemented from scratch.
