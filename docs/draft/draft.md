## MATH 214 Project Pre Draft (Section 2)
### Slides 0 
After the introduction of Gradient Descent, I'd like to introduce the application section of our project.

### Slides 1 Application Introduction
Our application uses a CNN model to predict handwritten digits in the MNIST dataset. MNIST is a well-known dataset used for image recognition and classification tasks. It consists of 70,000 handwritten digits in grayscale images of 28x28 pixels.

Shown in the slide is an example image from the MNIST dataset.
Through our project, we explore how Gradient Descent applies in deep learning. 

The source code repo  can be found at this link.

### Slides 2 Model Introduction
Our CNN model consists of 3 convolutional layers and 1 fully connected layer. The loss function we used is CrossEntropy and Gradient Descent was implemented with SGD.

Other parameters for the model include 30 epochs, a batch size of 64, and a learning rate of 0.001.

The visualized model is shown in the left.

### Slides 3 Gradient Descent
The SGD iteration formula is given here, where $w_t$ represents the weights at iteration $t$, $\eta$ is the learning rate, and $\nabla L(w_t)$ is the gradient of the loss function with respect to the weights.

The algorithm trains the model by specific epochs and batch_size. For each batch, the algorithm step is: set gradient zero, forward propagation, compute loss, backward propagation, and finally, the parameters are updated using SGD.

### Slides 4 Conclusion
In conclusion, we have shown how a CNN model can be used to predict handwritten digits in the MNIST dataset. By using Gradient Descent with SGD to update the model's parameters, the model gradually improves its ability to classify digits.

The epoch-loss plot  shows the trend of the model's loss function over time. The plot displays a downward trend with rapid loss reductions in initial epochs and slower reductions as the algorithm converges.

### Slides 5 Classification Result
The prediction on testing set for our model is shown in the slide. The total loss is approximately 0.0413, and the accuracy is around 98.67%. This indicates that the Gradient Descent algorithm used in our CNN model, works well.

To further improve the performance of our model, we could consider adjusting parameters such as the learning rate and batch size. Additionally, we could experiment with different GD algorithms such as Adam.

In the next part, we will introduce more GD algorithms and discover further. 