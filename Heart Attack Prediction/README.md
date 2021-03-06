# Heart-Attack-Prediction
To predict whether a person will suffer from heart attack or not.
# Objectives
To predict the probability of suffering of any patient from heart attacks in the upcoming future.  
To exploit different machine learning techniques on medical data set to assist in the prediction of heart attack.           
Identify the major factors influencing heart attack. 
# Dataset
The dataset is taken from kaggle, https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

Here we have the description of the features:                                    
age - age in years                                          
sex - sex (0 = female; 1 = male)                            
cp - chest pain type (1 = typical angina; 2 = atypical angina; 3 = non-anginal pain; 0 = asymptomatic)           
trtbps - resting blood pressure (in mm Hg on admission to the hospital)            
chol - serum cholestoral in mg/dl            
fbs - fasting blood sugar > 120 mg/dl (0 = false; 1 = true)            
restecg - resting electrocardiographic results (0 = normal; 1 = hypertrophy; 2 = having ST-T wave abnormality)        
thalachh - maximum heart rate achieved          
exng - exercise induced angina (0 = no; 1 = yes)                         
oldpeak - ST depression induced by exercise relative to rest                       
slp - the slope of the peak exercise ST segment (0 = downsloping; 1 = flat; 2 = upsloping)              
caa - number of major vessels (0-4) colored by flourosopy          
thall - thallium stress test (1 = fixed defect; 2 = reversable defect; 3 = normal)                
output - 0 = less chance of heart attack; 1 = more chance of heart attack            
# Methodologies
1. Dataset collection
2. Performed EDA  : Handled Outliers , Deleted duplicate rows, visualization and Feature scaling.  
3. Created 7 different Classification Models : Logistic Regression, KNN, Decision Tree, SVM, Random Forest, Naive Bayes, XGBoost.
4. Performed comparative analysis on the techniques used.

# Visualization

![image](https://user-images.githubusercontent.com/95580124/156964038-6382a59e-63b5-4764-8fe5-d46f76a924e0.png)

![image](https://user-images.githubusercontent.com/95580124/156967363-2e479566-04ae-42c6-8461-ea18af2c471c.png)

![image](https://user-images.githubusercontent.com/95580124/156967383-8dc75d41-62f9-4631-a100-5c7db066044e.png)


# Libraries used
1. Data Cleaning: numpy, pandas
2. Visualisation: seaborn, matplotlib
3. Feature scaling: MinMaxScaler
4. Splitting to train and test: train_test_split
5. Accuracy calculation & confusion matixs: metrics,confusion_matrix,accuracy_score,precision_score,recall_score,f1_score
6. Algorithms: DecisionTreeClassifier, RandomForestClassifier, svm, KNeighborsClassifier, LogisticRegression, GaussianNB, XGBClassifier
