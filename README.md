# Chronic-Illness-Prediction-SPD-Team-4
The purpose of our Project is to Predict the risk of an individual to be diagnised with a particular Chronic Disease. Today, the scientific enterprise performs an essential function in curing patients' ailments and is beneficial to customers after they no longer need to visit a medical institution or different clinic, so customers input signs and symptoms and all different beneficial information. You can study contamination, and the scientific enterprise can benefit from this application sincerely through querying the person's signs and symptoms and getting them into the application, and subsequently the person might be knowledgeable about destiny contamination predictions. 

 This is a preventive app that enables in those tough instances while it is now no longer so handy to visit the medical institution  and make an appointment. Based on the input provided, you will be able to find the likelyhood of the user suffering from the particular chronic disease. We also offer suggestions and treatments from your local doctor to make it more convenient for you. The main goal is to go to the hospital during a pandemic, help people when they cannot make a convenient appointment, and provide medical assistance. Disease prediction web applications are limited by the specific technologies, tools, databases available for system development. 
 
The speed and availability of a user's internet connection affects the response speed of the application. Below, the key features are  sorted according to the  proposed system priorities.

The users of disease prediction web applications must be equipped with a device. 
A stable internet connection is recommended for a smooth user experience. 
The application is free of cost and is made available to all users. 
Less time consuming and provides added options for consulting. 
The Application predicts the closest disease based on the user inputs although it cannot guarantee an exact diagnosis of the disease. 

Recently, many researchers have designed various automated diagnosis models using various supervised learning models. An early diagnosis of disease may control the death rate due to these diseases. In this project, an automated disease diagnosis model is designed using the machine learning models. In this project, we have selected three critical diseases such as Stroke, General cardiovascular disease, and diabetes. In this project, the data are entered into an web Application, the analysis is then performed in a real-time database using a pretrained machine learning model which was trained on the same dataset and deployed in MySQL Workbench, and finally, the disease detection result is shown in the Web Application. Logistic regression is used to carry out computation for prediction. Early detection can help in identifying the risk of Stroke, General cardiovascular disease, and diabetes. The proposed model may help doctors to give timely medications for treatment.


Technology Stack Used
Front End - HTML, CSS
Framework - Flask
Back End - Python
Database - MySQL
IDE - VScode
ML Code-Google Collaboratory & Jupyter Notebook 

Core Features
Risk Prediction based on a Logistic Recurssion Model, on analysing various Datasets integrated with a web-based front end model 


Modules

- Login
- Registration 
- Menu page-Different Chronic Diseases 
  -Stroke 
  -Cardiovascular disease 
  -Diabetes 
  -More to come 
  
- Each disease has an Input page to collect data from the user 
  -Stroke-gender,age,hypertension,heart_disease,ever_married,work_type,Residence_type,avg_glucose_level,bmi,smoking_status
  -Cardiovascular disease -AGE;GENDER;HEIGHT;WEIGHT;AP_HIGH;AP_LOW;CHOLESTEROL;GLUCOSE;SMOKE;ALCOHOL;PHYSICAL_ACTIVITY
  -Diabetes Pregnancies,Glucose,BloodPressure,SkinThickness,Insulin,BMI,DiabetesPedigreeFunction,Age
  
- Result page displaying The Predicted outcome
- Logout


File Wise Description 

1.Database

	-SQL Commands for creation and deployment of Tables for storing the database 


 
 
2.Datasets 

	-The Datasets used to Train the Machine training Models 
 
 	-3.csv-General Cardiovascular Disease
 
 	-db.csv-Diabetes 
 
 	-stroke.csv-Stroke 
 
 	-Source-Kaggle https://www.kaggle.com 
 
 
 
3.Templates-HTML Page Files 

	-Register.html 

	-Login.html

	-Index.html

	-cardio.html-Stroke Page 

	-cardiovascular.html-General Cardiovascular Disease page 

	-diabetes.html-Diabetes page 

	-Output.html-Result Page 



4.app.py

	-Python Code for the Web Application 
     	-Functions 
        	-Register 
        	-Login
        	-Index
        	-Cardio
       		-Cardiovascular 
        	-Diabetes 
        	-Output 
   	-ML Code 
     -strokeml
     -diaml
     -cardiovascularml
	 
	 
     
5.static

	-CSS file for styling the web Application 
	-style.css

