# cat-dog-classifier
A CNN based Deep Learning model which takes an image as input and classifies it as a dog or cat image

This is a raw project in which i have used only necessary libraries such as numpy,matplotlib and keras.
No pretrained parameters/models were used in this project.


In this model i have used 5 Convo2D(CNN) layers where each layer is followed by one max pooling layer.
Dropout layers have also been added to the model

I have used RMSprop as my optimizer having a learning rate of 0.0001

At last one Dense layer(Neural Network) had been added which finally gives us the output whether the input image is a dog or a cat image.

![image](https://user-images.githubusercontent.com/69752281/123805970-2182fe80-d90c-11eb-9508-deb149a779e7.png)

![image](https://user-images.githubusercontent.com/69752281/123806335-745cb600-d90c-11eb-89ef-62c2e1f00099.png)

![image](https://user-images.githubusercontent.com/69752281/123806398-88a0b300-d90c-11eb-9298-acf8dce0fc68.png)
I finally achieved testing accuracy of 87.2%
Testing accuracy can be pushed even higher by further research on CNN architectures and by using transfer learning.
