---
published: true
---
*This is the 3nd post of blog post series ‘Deep Learning and Machine Learning’.*

## CNN's Drawback

CNNs (convolutional neural networks) are awesome. They are one of the reasons deep learning is so popular today.
CapNets seems to be quite popular due to its computation then CNN's . Here first we see what are its major fall back.  
<center>
<img src="{{site.baseurl}}/assets/images/face.jpg" alt="">
<sub>site : http://sharenoesis.com/wp-content/uploads/2010/05/7ShapeFaceRemoveGuides.jpg</sub>
</center>

<br>

Let us consider a very simple and non-technical example. Imagine a face. What are the components? We have the face oval, two eyes, a nose and a mouth. For a CNN, a mere presence of these objects can be a very strong indicator to consider that there is a face in the image. Orientational and relative spatial relationships between these components are not very important to a CNN 

## CNN Working 

How do CNNs work?

> The main component of a CNN is a convolutional layer.Its job is to detect important features in the image pixels. Layers that are deeper (closer to the input) will learn to detect simple features such as edges and color gradients, whereas higher layers will combine simple features into more complex features. Finally, dense layers at the top of the network will combine very high level features and produce classification predictions.

An important thing to understand is that higher-level features combine lower-level features as a weighted sum: activations of a preceding layer are multiplied by the following layer neuron’s weights and added, before being passed to activation nonlinearity. Nowhere in this setup there is pose (translational and rotational) relationship between simpler features that make up a higher level feature. CNN approach to solve this issue is to use max pooling or successive convolutional layers that reduce spacial size of the data flowing through the network and therefore increase the “field of view” of higher layer’s neurons, thus allowing them to detect higher order features in a larger region of the input image. * _Max pooling is a crutch that made convolutional networks work surprisingly well, achieving superhuman performance in many areas. But do not be fooled by its performance: while CNNs work better than any model before them, max pooling nonetheless is losing valuable information_ *.

## Major Difference between Capsule and Neurons

<center>
<img src="{{site.baseurl}}/assets/images/table.png" alt="">
<sub>site : https://pechyonkin.me/images/201711-capsules-2/capsules-table.png</sub>
</center>

_**4th post** will be out soon.._ *(Keep Scrolling)*.

_Thank you for reading my post._
