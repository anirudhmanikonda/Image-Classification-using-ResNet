# Image-Classification-using-ResNet50
We will be building a very deep convolutional network, using Residual Networks (ResNets). In theory, very deep networks can represent very complex functions; but in practice, they are hard to train. Residual Networks, introduced by https://arxiv.org/pdf/1512.03385.pdf, allow you to train much deeper networks than were previously feasible.

By the end of this project, we'll be able to:

      Implement the basic building blocks of ResNets in a deep neural network using Keras
      Put together these building blocks to implement and train a state-of-the-art neural network for image classification
      Implement a skip connection in your network
      For this assignment, we'll use Keras.
      
# Residual Network
ResNet-50 is a pretrained Deep Learning model for image classification of the Convolutional Neural Network(CNN, or ConvNet), which is a class of deep neural networks, most commonly applied to analyzing visual imagery. ResNet-50 is 50 layers deep and is trained on a million images of 1000 categories from the ImageNet database. Furthermore the model has over 23 million trainable parameters, which indicates a deep architecture that makes it better for image recognition. Using a pretrained model is a highly effective approach, compared if you need to build it from scratch, where you need to collect great amounts of data and train it yourself. Of course, there are other pretrained deep models to use such as AlexNet, GoogleNet or VGG19, but the ResNet-50 is noted for excellent generalization performance with fewer error rates on recognition tasks and is therefore a useful tool to know.

Architecture of ResNet-50
ResNet stands for Residual Network and more specifically it is of a Residual Neural Network architecture. What characterizes a residual network is its identity connections. Identity connections takes the input directly to the end of each residual block, as shown below with the curved arrow:

Image of Residual learning: a building block

![resnet-e1548261477164](https://user-images.githubusercontent.com/58980493/124714389-53552000-df1f-11eb-8051-4dd99c1843d2.png)


Specifically, the ResNet50 model consists of 5 stages each with a residual block. Each residual block has 3 layers with both 11 and 33 convolutions. The concept of residual blocks is quite simple. In traditional neural networks, each layer feeds into the next layer. In a network with residual blocks, each layer feeds into the next layer and directly into the layers about 2–3 hops away, called identity connections.

Image of ResNet Architecture
![resnet](https://user-images.githubusercontent.com/58980493/124715152-48e75600-df20-11eb-9f40-e9a237b5a821.png)
# Reference List:
   https://arxiv.org/pdf/1512.03385.pdf 

