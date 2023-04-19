## Pre Draft (Section 2)
### Slides 0 
After the introduction of Gradient Descent, I'd like to introduce the application section of our project.

### Slides 1 Application Introduction
Our application uses a CNN model to predict handwritten digits in the MNIST dataset. MNIST is a well-known dataset used for image recognition and classification tasks. It consists of 70,000 handwritten digits in grayscale images.

Shown in the slide is an example image of MNIST dataset.

In our project, we explore how Gradient Descent applies in CNN model predicting MNIST. 

Our source code repo can be found at this link.

### Slides 2 Model Introduction
Our CNN model consists of 3 convolution layers and 1 fully-connected layer. The loss function is CrossEntropy and Gradient Descent method was implemented with SGD.

Other parameters for the model include 30 epochs, a batch size of 64, and a learning rate of 0.001.

Our model is visualized in the left.

### Slides 3 Gradient Descent
The SGD iteration formula is given here, where $w_t$ represents the weights at iteration $t$, $\alpha$ is the learning rate, and then the gradient of the loss function.

In the algorithm, for each batch, the algorithm step is: set gradient zero, forward propagation, compute loss, backward propagation, and finally, the parameters are updated using SGD.

### Slides 4 Conclusion
The epoch-loss plot shows the trend of the model's loss function over time. This plot displays a downward trend with rapid reductions in initial epochs and slower reductions when the algorithm converges.

### Slides 5 Classification Result
The prediction on testing set for our model is shown in the slide. The accuracy is over 98%. So, the Gradient Descent algorithm used in our CNN model works well.

For further improvement, we can consider adjusting parameters.Additionally, we can use better GD algorithms such as Adam.

In the next part, Liang will introduce more about GD algorithms. 