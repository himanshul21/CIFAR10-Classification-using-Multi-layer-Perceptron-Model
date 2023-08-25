CS776A: Deep Learning for Computer Vision - Assignment 1

This assignment is done by Himanshu Lal - 21111403 - himanshul21@iitk.ac.in
 
========================================================================================================================================================================

Libraries used: 
numpy version : 1.20.1, 
cv2 : 4.0.1,
matplotlib : 3.3.4
pickle : 0.7.5
jupyter 1.0.0

========================================================================================================================================================================

Code Files are stored in : Jupyter Notebook (.ipynb) and python files (.py).

1. Dataset->cifar-10-batches-py : Store the extracted train dataset and test dataset.
				  Dataset is not loaded with this assignment if you wanted to run the complete assignment please download it from the site given below 
				  and after extraction put all the datasets in this folder.

2. codefiles                    : This folder stores all the models weights, extracted features and code files for MLP.
             -> HimanshuLal21111403.ipynb  :  This file stores all the codes of assignment.
             -> unaugmented_model.pkl      :  This file stores the weights of the model trained with original dataset.
	     -> augmented_model.pkl        :  This file stores the weights of the model trained with augmented dataset.
	     -> BBResNet18_features.pkl    :  This file stores the extracted features of the original train, augmented train and test dataset from the BBResNet18 model.
	     -> feature extractor          :  This file stores the code to extract features from the BBResNet18 Model.

3. Report                        : Report of the Assignment.
Every Code and Jupyter Notebook is properly commented for better understanding.

========================================================================================================================================================================
 Procedure to run the codes 

1. Download the dataset from the site : https://www.cs.toronto.edu/~kriz/cifar.html.
2. Extract the above downloded file and save all the train_batch[1:5] and test_batch in the folder Dataset->cifar-10-batches-py.
3. Run "HimanshuLal21111403.ipynb" file to train the model and checking the results.
4. If you don't wanted to train the model from the start then skip the training pasrt and go to the last section and run the model with loaded weights.

========================================================================================================================================================================
In case of any query kindly contact me: mob :8795917058, himanshul21@iitk.ac.in

========================================================================================================================================================================