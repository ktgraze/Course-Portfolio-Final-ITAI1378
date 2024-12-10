### Module 05 Reflection
For Module 05's lecture we were introduced to the basics of machine learning for computer vision. 
* We covered the three types of ML: 
1. *Supervised Learning* - when the computer is given labeled data, and the programmer asks the model to determine the relationship between the input and the output variables. Common problems are Regression and Classification tasks.
2. *Unsupervised Learning* - the computer is given data with no direction or labels from the programmer, and the computer finds hidden patterns. Common problems are Clustering tasks or finding patterns in examples.
3. *Reinforcement Learning* - A model that improves upon itself in new situations using a trial-and-error method - very similar to how humans learn.
* Features and Labels in image data - images are labeled, the algorithm treats the image's pixels as features and uses them to train the model.
* A refresher of the ML pipeline - define the problem, data preprocessing, model training, deploying the model, and using the model in production.
* ML for CV specifics:
  - Focus on feature selection and extraction
  - Popular techniques include SVM, k-NN, and Random Forests.
  - Traditional methods have limitations, such as difficulty with high-dimensional data and complex, non-linear relationships.
  - Deep learning offers a more powerful and flexible approach to computer vision tasks.
  - Despite the advancements, traditional machine learning remains an important foundation in the field.
___
The individual lab assignment L05, asked us to use a subset of the classical CIFAR-10 dataset to train a Support Vector Machine (SVM) algorithm for the task of image classification. CIFAR-10 contains 60,000 32x32 color images with 10 different classes - airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. I worked in Google Colab, utilizing the code assistant Gemini. 
The models performance was not particularly exceptional, the accuracy was 54.7%, meaning the model guessed a little bit better than by chance. Precision is the ratio of true positives and false positives, with the ship class being guessed correctly by 66% versus the cat and dog classes at 48% and 49% respectively. Recall is the ratio of true positives to the sum of true positives and true negatives and had nearly identical results to precision. The F1-score is the mean or average of precision and recall which was also similar. 
#### A snippet of the model being trained and evaluated:
<img width="468" alt="image" src="https://github.com/user-attachments/assets/49315ba5-0c17-4edf-9efd-efabc9e65499">
