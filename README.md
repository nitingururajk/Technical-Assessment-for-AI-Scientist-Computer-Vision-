# Technical-Assessment-for-AI-Scientist-Computer-Vision-
This repository consists of a Colab notebook taken from Tensorflow tutorials which performs action recognition. It uses an Inflated 3D CNN to perform action recognition on the UCF Dataset.
The reason I have chosen this code is because it performs really well on the Kinectics-400 dataset and is based on the paper:
"Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset" by Joao Carreira and Andrew Zisserman

![image](https://user-images.githubusercontent.com/102589425/163395028-57bd938e-e96b-49bf-a387-1dbc2f34ac4a.png)
The idea of this paper is it takes a 2D CNN architecture and replace each 2D conv/pool layers with a 3D version. 
We can also use weights of 2D CNN to initialize the 3D CNN. This network uses the Inception CNN architecture but with 3D Convolution blocks.
