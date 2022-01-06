# Diabetes-Prediction
Prediksi Resiko Diabetes

Notebook berisikan:
* Import Library
    Kolom terdiri dari:
     0   Diabetes_binary       253680 non-null  float64
     1   HighBP                253680 non-null  float64
     2   HighChol              253680 non-null  float64
     3   CholCheck             253680 non-null  float64
     4   BMI                   253680 non-null  float64
     5   Smoker                253680 non-null  float64
     6   Stroke                253680 non-null  float64
     7   HeartDiseaseorAttack  253680 non-null  float64
     8   PhysActivity          253680 non-null  float64
     9   Fruits                253680 non-null  float64
     10  Veggies               253680 non-null  float64
     11  HvyAlcoholConsump     253680 non-null  float64
     12  AnyHealthcare         253680 non-null  float64
     13  NoDocbcCost           253680 non-null  float64
     14  GenHlth               253680 non-null  float64
     15  MentHlth              253680 non-null  float64
     16  PhysHlth              253680 non-null  float64
     17  DiffWalk              253680 non-null  float64
     18  Sex                   253680 non-null  float64
     19  Age                   253680 non-null  float64
     20  Education             253680 non-null  float64
     21  Income                253680 non-null  float64
     
* Cleaning Data 
* Exploratory Data Analysist (Univariate dan Bivariate)
* Correlation Column: Income, Education, PhysActivity --> Negative correlation
                      GenHlth, HighBP, DiffWalk,BMI --> Positive correlation
* Check Outlier:
    There are outliers in BMI
    Count of outliers are: 9847
    There are outliers in MentHlth
    Count of outliers are: 36208
    There are outliers in PhysHlth
    Count of outliers are: 40949 
* Scaling Data
* Training and Testing Data
* Model Random Forest

