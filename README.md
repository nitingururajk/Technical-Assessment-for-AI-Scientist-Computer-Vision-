# Technical-Assessment-for-AI-Scientist-Computer-Vision-
This repository consists of a Colab notebook taken from Tensorflow tutorials which performs action recognition. It uses an Inflated 3D CNN to perform action recognition on the UCF Dataset.


*Taken From: https://www.tensorflow.org/hub/tutorials/action_recognition_with_tf_hub*


The reason I have chosen this code is because it performs really well on the Kinectics-400 dataset and is based on the paper:

"Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" by Joao Carreira and Andrew Zisserman

![image](https://user-images.githubusercontent.com/102589425/163395028-57bd938e-e96b-49bf-a387-1dbc2f34ac4a.png)


The idea of this paper is it takes a 2D CNN architecture and replace each 2D conv/pool layers with a 3D version. 
We can also use weights of 2D CNN to initialize the 3D CNN. This network uses the Inception CNN architecture but with 3D Convolution blocks.

There are various other ways to do action recognition but this is one of the more popular approach.

Results of action recognition can be seen in the Notebook.

A sample GIF and its results are shown below:

![](index.gif)


![image](https://user-images.githubusercontent.com/102589425/163396642-765fb22e-535b-4451-8da9-0919632a6059.png)


By changing the video, other actions can also detected.
