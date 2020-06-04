# CNN-on-CIFAR-Keras-Tensorflow
CNN on CIFAR Keras Tensorflow Application
# CIFAR-10, 32x32 colored images of 10 different obj., Airplane, car, etc
# 0 airplane										
# 1 automobile										
# 2 bird										
# 3 cat										
# 4 deer										
# 5 dog										
# 6 frog										
# 7 horse										
# 8 ship										
# 9 truck										
![cifar](https://user-images.githubusercontent.com/57037068/83808922-a3333900-a6c6-11ea-8fdd-ef3059c23913.PNG)

Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_2 (Conv2D)            (None, 29, 29, 32)        1568      
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 14, 14, 32)        0         
_________________________________________________________________
conv2d_3 (Conv2D)            (None, 11, 11, 32)        16416     
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 5, 5, 32)          0         
_________________________________________________________________
flatten (Flatten)            (None, 800)               0         
_________________________________________________________________
dense (Dense)                (None, 256)               205056    
_________________________________________________________________
dense_1 (Dense)              (None, 10)                2570      
=================================================================
Total params: 225,610
Trainable params: 225,610
Non-trainable params: 0
_____________________________
32*32*3
# add more convolutional and pooling layers since there is immense data

# Confusion between 3 and 5 = cat and dog
# Confusion between 9 and 1 = truck and automobile

![he](https://user-images.githubusercontent.com/57037068/83808913-9e6e8500-a6c6-11ea-8f1c-fda6b8f8d94b.png)

![cifarac](https://user-images.githubusercontent.com/57037068/83808917-9f9fb200-a6c6-11ea-91bc-2174a11e6236.png)
