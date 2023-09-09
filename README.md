# Indian Liver patient prediction
Machine learning classification algorithms are applied for the analysis of liver disease. Decision tree, Random Forest, SVM and GBT classifier algorithms are applied to analyse the patient records. Classification techniques employed using pyspark 
The Dataset is available at,
 https://www.kaggle.com/datasets/uciml/indian-liver-patient-records
The dataset contains 416 liver patient records and 167 non liver patient records collected from North East of Andhra Pradesh, India. It has a column “Dataset” which is the target column used to divide the group into patient with and without disease. It contains 441 male patients and 142 female patient records. Any patient age exceeded 89 is listed as ‘90’. 
Analysis starts with data preprocessing such as cleaning, mean imputation, oversampling for class balance. Numeric columns are standardized using standard scalar. 
The ‘Gender’ column is converted into numeric using String indexer, Which is being encoded using OneHot encoder.
A pipeline is created to encapsulate the sequential processing steps. The stages of the pipeline include the gender indexing, one-hot encoding, and feature assembling. Then classification algorithms are applied for finding the best model with hyper parameter tuning. All the performance evaluation metrices such as precision, recall, f1score, ROC-AUC was analysed for finding the best performing model.
![image](https://github.com/Rajapriya11/Pyspark/assets/119552816/3d59d2cf-5d19-4d77-816a-d081b0c80c84)

