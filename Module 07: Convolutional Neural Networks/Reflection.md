### Module 07 Reflection
This week's lecture covered Convolutional Neural Networks.
#### **Key Takeaways**:
* *Basics of CNNs*:
  - Unlike MLPs (Multi-Layer Perceptrons), that struggle with spatial data, CNNs excel by maintaining the spatial hiearchy of features.
  - CNN Architecture:
    * Input layer
    * Convolutional layers for feature extraction
    * Fully connected layers for classification
    * Output prediction
  - Stride and Padding - determine how the filter/ window moves across the image and how output size is controlled.
  - Common Preproccessing techniques: Normalization, data augmentation, and feature engineering.
___
#### **A07 - Manual CNN** :
Group assignment A07 tasked us with making a Manual CNN by creating a simplified image made up of grids, with numbers signifying pixel values in each grid (we chose a 5x5 cross image). Next we made 3 filters (vertical, horizontal, and diagonal) for edge detection and slid the filters across the image to simulate manual convolution of an image. After, we observed the results of applying each filter, concluding, "this manual application of filters provides foundational insight into how convolutional layers in neural networks work. Convolutional neural networks use multiple filters across various layers to learn complex features from images. By stacking multiple layers, CNNs can detect simple features like edges in the early layers and more complex patterns, such as shapes and textures, in deeper layers." (Goodfellow, Bengio, & Courville, 2016).
#### An example of our original image below:
<img width="2785" alt="image" src="https://github.com/user-attachments/assets/476316ab-c903-46be-99dc-2850045b098a">

<img width="1129" alt="Screenshot 2024-12-10 at 6 33 03 PM" src="https://github.com/user-attachments/assets/47305b34-9e9f-44e0-b3fd-8749ddf43f17">

___
#### **L07 - Chihuahua or Muffin with CNN** :
Overview of individual Lab 07 - we continued our exploration of the Chihuahua vs. Muffin workshop, but this time deploying a Convolutional Neural Network (CNN) instead of the traditional Neural Network from Lab 06. Unlike CNNs, which have been specifically designed for image data and utilize convolutional layers to automatically learn relevant features, traditional NNs require manual feature engineering, which can be time consuming and less accurate. While CNNs exploit the spatial relationships between pixels in an image, NNs treat the input as a flattened vector, ignoring the spatial structure of the image, which can limit the model’s ability to learn complex patterns.Unlike the past lab’s NN performance, which depending on the parameters used, performed its best at a 95% accuracy, the CNN performed perfectly with 100% accuracy. The training time however did take much longer for the CNN, though we used more epochs initially than with the NN. This lab was a great example of the greater accuracy that CNNs bring to image classification. 
