---
published: false
---
*This is the 2nd post of blog post series ‘Deep Learning and Machine Learning’.*

# MP Neuron model

The McCulloch-Pitts Neuron model relates to the theory developed in the 90s where Walter McCulloch and Warren Pitts put forward the idea. It is similar to a human neuron in Biology consisting of Axons, Soma etc. These are mapped to the functioning of the neural network.

## 1) Data

The MP neuron takes binary input and gives binary output. If the input data is not binary it can be compacted to binary before it can be feeded to the model.

## 2) Classification

The classification is also binary which is 0 or 1. The model can give a yes or no answer based on the input and the threshold.

## 3) Model

It consists of a function with a single parameter. The input is aggregated(g). There is a threshold value which is decided. If the value of the function is equal to or greater than the threshold value, it gives a positive output and vice versa.

<center>
<img src="{{site.baseurl}}/assets/images/model.png" alt="">
<sub>site: One Fourth Labs</sub>
</center>

The MP Neuron model basically draws a line where positive values lie on the line or above the line whereas the negative values below the line.

## 4) Loss function

The squared loss function is applied. It finds the difference between the predicted value and the actual prediction as a square.

## 5) Learning

<center>
<img src="{{site.baseurl}}/assets/images/learn.png" alt="">
<sub>site: One Fourth Labs</sub>
</center>

Learning in MP Neuron consists of finding the threshold value with lowest error for prediction. This is done with brute force for a single parameter.

## 6) Accuracy

Accuracy is given by the standard matrix of the division of the number of right predictions by the total number of predictions.

The MP Neuron basically helps to find a line that separates the positive value from the negative ones.

The disadvantages of MP Neuron are-

1. Boolean input and output.
2. Fixed slope
3. Few intercepts possible
4. Fixed parameters
5. Less flexible
6. Less variety of Inputs.

_**3rd post** will be out soon.._ *(Keep Scrolling)*.

_Thank you for reading my post._
