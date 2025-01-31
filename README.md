# Kannada-MNIST---Classification-Problem

# Problem Statement:

* This is an extension of classic MNIST classification problem. Instead of using Hindu numerals, lets use a recently-released dataset of Kannada digits. This is a 10 Class classification
  problem.

# Source file:

* Dataset can be downloaded from the link : https://www.kaggle.com/datasets/higgstachyon/kannada-mnist.
* All details of the dataset curation has been captured in the paper titled: Prabhu, Vinay Uday. "Kannada-MNIST: A new handwritten digits dataset for the Kannada language."https://arxiv.org/abs/
  1908.01242.

# Procedure:

1. Extracted the dataset from the npz file from the downloaded dataset or from the web.There are 60000 images for training and 10000 images for test. Each image is of the size 28X28.
   
2. Performed PCA to 10 components. So now we have train and test images in 10 dimension instead of 28X28 dimension.
   
3. Applied the following models:

   * Decision Trees
   * Random Forest
   * Naive Bayes Model
   * K-NN Classifier
   
  

5. For each of this method, following metrics are used:

    * Precision, Recall and F1 - Score
    * Confusion Matrix
    * Roc - AUC Curve   
  

7. Repeated the same experiment for different component size : 15,20,25,30

