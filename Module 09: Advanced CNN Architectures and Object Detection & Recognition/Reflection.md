### Module 09 Reflection
This week's module covered advanced CNN architectures, including:
* VGGNet (2014)
* GoogLeNet/ Inception (2014)
* ResNet (2015)
* R-CNN(2014)
* Faster R-CNN (2015)
* Mask R-CNN (2017)
### **Object Detection**: 
Localizing and classifying multiple objects within an image, includes drawing a bounding box around each specific object.
  * Bounding Boxes:
    - A rectangle specified by, top-left corner coordinates (x, y) and width & height, may also include a class label and confidence score.
    - Types include: Axis-Aligned Bounding Box (AABB) and Oriented Bounding Box (OBB).
  
___
### A09
For this week's group assignment we were tasked with creating an Object detection cheat sheet. My group tried to cover all relevant topics including key concepts (shown below), steps in an object detection task, common algorithms, libraries, frameworks, evaluation metrics, and tips & challenges. We also tried to include additional resources for quick reference.
##### Example of part of our cheat sheet below:
<img width="807" alt="Screenshot 2024-12-10 at 7 07 34 PM" src="https://github.com/user-attachments/assets/ad23158d-1551-4e91-8c95-8f8fff3e718a">

___
### L09
This lab asked us to use an object detection model on the Pascal VOC 2007 dataset. In hindsight, I was running into the issue of session limitations with the Google Colab free tier and my model was not completing training, leading to poor results. If I could do this lab over again, I would use only a portion of the dataset in order to properly apply training, evaluation and visualization techniques. My main takeaway was the difference between CPUs and GPUs or TPUs, in that this dataset paired with the SSD MobileNet V2 model was too computationally demanding for the tools I was using. A lesson learned that scaling down is sometimes necessary. 
