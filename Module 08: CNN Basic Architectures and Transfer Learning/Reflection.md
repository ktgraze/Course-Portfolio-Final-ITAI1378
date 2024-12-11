### **Module 08 Reflection** :
Though we did not have an assignment due for this module, I would like to still recap what I learned in the week's lecture.
### **Transfer Learning** : 
Uses a pre-trained model's knowledge to improve performance on a related task, which saves time and resources compared to training a model from scratch.  
#### Examples of pre-trained models for transfer learning:
* *VGG models* - like VGG16, known for their depth and simplicity.
* *ResNet models* - like ResNet-50, address the vanishing gradient problem.
* *Inception models* - like InceptionV3, utilitze inception modules for efficient feature extraction.
* *EfficientNet models* - Optimized for both accuracy and efficiency.
* Vision Transformers (ViT) - Applying transformer architecture to vision tasks.
#### Common TL techniques:
* *Freezing* - fix weights in early layers of the pre-trained model (which extract generic features) and fine-tune the later layers on the target task.
* *Fine-tuning* - Train all layers of the pre-trained model on the target dataset.
