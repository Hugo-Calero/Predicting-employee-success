# Predicting-employee-success

This project was done with HC-One, the largest care home operator in the UK. The company provided with data of past and present employees, including their position and
length of service, employment history, and a series of features related to the area where they work/worked. 

The main goal was to identify which employees were succesfull for the company. This analysis is done for 3 separate jobs within HC-One: carers, senior carers, and nurses. 
Toward this goal, in the first part of the project we applied unsupervised machine learning techniques and statistical inference methods to determine the minimum length 
of service (in months) an employee has to work for the company in order to be classified as a succesful hire.

After this, machine learning models were developed to automatically select employees according to the information available in their CV and the previously obtained
results. In this stage, Generative Adversarial Networks were used to generate synthetic samples with which to train the models, as well as feature selection techniques 
and the machine learning algorithms.

Model interpretability was provided by using the SHapley Additive Explanations and Accumulated Local Effects methods of explainability.
