### Module 06 Reflection
Introduction to Neural Networks lecture key takeaways:
* *Neural Networks Basics* - "a computational model inspired by the structure and functioning of the human brain. It consists of interconnected nodes, called neurons, organized in layers. Each neuron processes input data and transmits signals to other neurons." Used in various tasks including pattern recognition, image classification, regression, and decision-making.
* *Artificial Neuron Components*:
  - Inputs: data points the neuron receives including, pixels of an image, words in a sentence, numbers representing features.
  - Weights - Importance tags each input has a weight.
  - Bias - Adjusted during training.
  - Activation Functions - the decision-maker which introduces non-linearities, activate or deactivate a neuron, and limit the range of values a neuron can have.
  - Outputs - The final value the neuron generates after all its calculations.
* *Learning Process*:
  - Initialization: start with random weights for connections between neurons.
  - Feedforward: input data is fed into the network and processed through each layer to get the output.
  - Loss Calculation: determine the error of the output by comparing it with the expected result using a loss function.
  - Backpropagation: Calculate the gradient of the loss function with respect to each weight by the chain rule, moving from the output layer backward to input layers.
  - Weight Update: adjust the weights of the connections to minimize the loss, typically using optimization algorithms like gradient descent.
  - Iteration: Repeat the feedforward, loss calculation, backpropagation, and weight update steps until the model performs satisfactorily.
  - Evaluation: Validate the model using a separate dataset not seen by the network during training to test its generalization capability.
___
### A06 TensorFlow Playground Presentation
For this group assignment we were tasked with familiarizing ourselves with the fundamentals of a neural network by experimenting with the TensorFlow Playground. We experimented with tweaking configurations and parameters, including Activation Functions, Hidden Layer Neurons, Learning Rate, Data Noise, and further Dataset Exploration. 
#### Below are the results of trying both ReLU and sigmoid Activation Functions:
<img width="754" alt="Screenshot 2024-12-10 at 4 30 33 PM" src="https://github.com/user-attachments/assets/b8a21875-eb83-416b-95ea-91dc2821a27e">

___
### L06 Chihuahua or Muffin
For this individual lab assignment we were tasked with working on the "Chihuahua or Muffin" workshop, which uses a general neural network to classify whether images are chihuahuas or muffins. The workshop is mostly a walkthrough lab that challanges the user to experiment with changing parameters at the end of the notebook. This lab was challenging but I gained some insight into how different parameters affect overall accuracy.
