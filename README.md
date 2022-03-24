# Applied-ML-Project
**Title: DISEASE PREDICTION USING MACHINE LEARNING.**

**What are we trying to solve?**
We aim to build a Machine Learning model that can predict the disease a person might have based upon the symptoms they are displaying.
Comparative study of various ML algorithms to figure out the best model and demonstrating the disease prediction system developed.
Predict tendency for a disease in long term based on current diseases. 
The dataset we will be using can be found at this link: https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning

**Dataset:**
The dataset we will be using can be found at this link: https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning
This dataset has total 133 total columns, 132 of them being symptoms experienced by patients and last column is the prognosis for the same. 

**Our Approach:**
**Data Collection**:  For this particular problem, we decided to pick a dataset from Kaggle. This dataset consists of 2 .csv files : Testing.csv and Training.csv
This dataset basically consists of 133 columns out of which the last column is for “prognosis” while the remaining 132 columns have the symptoms. This dataset claims to predict 42 different types of diseases.
**Data Pre-processing:** As the quality of the data is very important for a robust Machine Learning model to be built, we would be cleaning and transforming our data before moving ahead with the training of the model. Our dataset has got binary except the last column(target column) i.e prognosis which is of string type. Identifying and handling the missing values, feature scaling, encoding the categorical data would be some of the steps we would be carrying out to clean our dataset.
**Building the model:** Now that our data is collected and cleaned to be used, we will use this data to train our ML model.This data will be used to train the Naive Bayes Classifier, Random Forest Classifier, Clustering algorithms, Support Vector classifiers algorithms for better prediction results. The metrics could be accuracy, AUC_weighted, confusion matrix with cost parameters to determine the quality of the models and decide upon which is the most suitable model.
**Conclusion:** After training the models and deciding upon the top 3, we will be predicting the disease from the symptoms by combining the predictions of all the 3 models. This will help make our model more accurate and hence reliable.

**QUESTIONS WE AIM TO ANSWER THROUGH OUR PROJECT**
How risky is a particular disease based on the symptoms and their intensity?
Which are the major diseases found amongst maximum people with even minor symptoms?
Which ML algorithms were specifically good for detecting a specific kind of disease?
Is there any correlation between diseases ?

**WHAT WE EXPECT TO LEARN FROM OUR PROJECT**
How to deal with data before training any machine learning model?
What are the different types of models and how are they similar/different from one another?

**IS OUR IDEA NOVEL? Yes**
We would be doing probabilistic classification based on Bayes theorem with independence assumptions between the features. This would allow us to predict a disease in long term based on the disease which a patient is having currently. Association rule mining along with Naive bayes classification were never used together for this purpose.
In clinical medicine, a validated calculator for Drug & Disease has been used for decades. 
https://reference.medscape.com/guide/medical-calculators.  However, there are still several medical issues that has not been addressed with these calculators. On of the reason is the lack of biostatistician and/or ML scientist working in this field, and cross-functional team work between ML scientist and the clinicians. The developed medical calculators are mostly using basic linear algorithm to make the explainability easy and simple. Here in this study, we aim to use complex models for disease prediction. However, this study will be in lack of validation due to the limited amount of data we have.
Recent advances in disease prediction is emerging towards bio-molecular level. For instance, recently we have witnessed ethical issues while allocating the resources (ICU bed, ventilation, hospital stay, i.e.) between COVID patients. This forced bio-statisticans and ML scientists to identify biomarkers to stratify disease severity (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7218676/, https://pubmed.ncbi.nlm.nih.gov/34132393/
The promising results obtained from recent biomarker led disease severity and mortality prediction will be widely implemented in soon future. This study has visual symptoms and accessing to patients’ biomolecular data is not the scope.

