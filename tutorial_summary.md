-------------------------------
Summary of Tutorials:

--
Tutorial 1:

In Tutorial 1 I learned the process of backpropagation and the simple maths behind the basics of neural networks.
Furthermore we use TensorFlow and Keras to train and optimize our first model. 
In the end, we tried to change multiple parameters such as other layers (dropout layer), different optimizers and
different types of losses.

--
Tutorial 2:

In the second tutorial we get to know to the principle of Transfer Learning for Object Classification. 
That means, that a model, which was pretrained on a dataset, is used so solve new problems, or in this case to be used on another dataset, the 'Dogs and Cats dataset'. 
With a pretrained model, just few epoches are necessary to achieve a good performance.

--
Tutorial 3:

This tutorial brings us to the Segmentation with U-Net. 
The aim is to improve efficiency on working with the training data. 
By fedding the neural network with a larger region than their predicition is for, we create feature maps to create a high resolution segmentation-map. 
Furthermore, we introduced the Dice Coefficient Loss, which is based on the a coefficient comparing the similarity of our network and the truth. 
It is commonly used for image segmentation.