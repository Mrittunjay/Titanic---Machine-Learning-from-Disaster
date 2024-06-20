# Titanic---Machine-Learning-from-Disaster
This is a binary classification machine learning project to determine if a person will survive or not in the titanic disaster given all the information of the person like age, gender, socio-economic status etc

Here are few of the data visulaizaitons:
![image](https://github.com/Mrittunjay/Titanic---Machine-Learning-from-Disaster/assets/24440830/4294b2a3-d17a-4df1-bd5e-87fdd8903e8f)
![image](https://github.com/Mrittunjay/Titanic---Machine-Learning-from-Disaster/assets/24440830/9ff30efe-c00b-4866-84ac-a22f756be348)
![image](https://github.com/Mrittunjay/Titanic---Machine-Learning-from-Disaster/assets/24440830/36f6c371-39a6-4ecf-868d-0d145da9577f)
![image](https://github.com/Mrittunjay/Titanic---Machine-Learning-from-Disaster/assets/24440830/c3016333-d41d-4c53-8d74-b915f219d81c)

The survival rates vary significantly by age and class.

First-class passengers generally had better survival rates across all ages.

Younger passengers had higher survival rates, especially in third class, indicating possible prioritization during rescue efforts.

Model used for inference is a finetuned random forest classifier with following parameters and metrices:

Best Parameters:  {'bootstrap': True, 'max_depth': 50, 'min_samples_leaf': 2, 'min_samples_split': 2, 'n_estimators': 80}

Accuracy: 0.9000

Precision: 0.9333

Recall: 0.8000

F1 Score: 0.8615

Confusion Matrix:

[[53  2]
 [ 7 28]]


TAKE-AWAYS FROM THIS PROJECT:
This project gave hands-on experience on several important aspets of data science and machine learning:
1. Data exploration and visualization: Used matplotlib and seaborn to explore the data and visualize the relationship between features.
2. Data preprocessing: The dataset had some missing data catagorical features, so needed to handle common issues regarding those in ML model training.
3. Binary classification: Applied various algorithms for optimized inference such as logistic regression, random forests, neural networks etc. 

