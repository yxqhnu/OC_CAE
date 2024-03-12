# OC_CAE algorithm
  
  **One-class convolutional autoencoder (OC_CAE)** is a novel one class classification algorithm, which is proposed for the detection of abnormal samples in excitation-emission matrix (EEM) fluorescence spectral dataset.The OC-CAE uses Boxplot to analyze the reconstruction errors and uses the LOF algorithm to handle features extracted by hidden layer in convolutional autoencoder (CAE) to jointly identify the authenticity of food.

# The contents of file 
**OC_CAE_ZAV.ipynb** represents the code of OC_CAE algorithm on the ZAV case.  
**OC_CAE_CAO.ipynb** represents the code of OC_CAE algorithm on the CAO case.  
**ZAV.mat** represents the dataset of ZAV case, where the X_training_normal.mat, X_training.mat and X_pre.mat represent the data-augmented training set, training set and prediction set, respectively. And the Y_training_normal.mat, Y_training.mat and Y_pre.mat represent the label of data-augmented training set, training set and prediction set, respectively, where the 0 represents the normal samples, 1 represents the abnormal samples.  
**CAO.mat** represents the dataset of CAO case, where the X_training_normal.mat, X_training.mat, X_test and X_pre.mat represent the data augmented training set, training set, test set and prediction set, respectively. And the Y_training_normal.mat, Y_training.mat, Y_test.mat and Y_pre.mat represent the label of data-augmented training set, training set and prediction set, respectively, where the 0 represents the normal samples, 1 represents the abnormal samples.  
**model_ZAV.pt** represents the well_trained the OC_CAE model of ZAV case.  
**model_CAO.pt** represents the well_trained the OC_CAE model of CAO case.
