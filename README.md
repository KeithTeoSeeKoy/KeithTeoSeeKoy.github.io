## Portfolio

Listed here are some of my work. If you have an interest in knowing more about my project work, feel free to drop me an email at keithteo.prop@gmail.com.

<a href="https://www.linkedin.com/in/keith-teo-569955202/">View My LinkedIn Profile</a>

### Basic of Data Science Presentation
This is the presentation I've done up to demonstrate how Data Science is being employed in Autonomous Vehicle. Below are some of the slides. What was not included in the slides are my presentation on convolutional neural networks (CNN) and recurrent neural networks (RNN) employed in Autonomous Vehicle to aid in image feature extraction and adding the temporal factor to predict the possibilities of object collision.  

---
[Autonomous Vehicle Case Study](https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/pdf/Autonomous%20Vehicle%20Case%20Study.pdf)

---
<img src="images/AutonomousVeh.JPG?raw=true" width="300"/> <img src="images/AutoVehContent.JPG?raw=true" width="307"/>
<img src="images/AutoVehBackgnd.JPG?raw=true" width="300"/> <img src="images/AutoVehWorkflow.JPG?raw=true" width="300"/>
<img src="images/AutoVehUseCases.JPG?raw=true" width="300"/>

### Capstone Project 1 - HR Attrition Analysis
This is an individual project done over 5 days. I've downloaded the IBM Watson dataset from Kaggle, clean it up and did some transformation via Power Query. I've found that the dataset has quite a worrying 20% employee attrition. This will impact the company talent retention as most of the employee who left are the younger ones. On top of that, the company has already been giving the employees quite an attractive salary with a good salary hike. The root of the cause from the analysis points toward the Overtime factor. About half of the employees who work Overtime left the company. Therefore, the company has to take a closer look at this situation.

I also did a Logistic Regression prediction model using Excel Solver. I've used a 80-20 train test split to generate up my model. With the trained Logistic Regression coefficient, I can then used it to predict whether an employee will stay/leave the company based on the latter profile.

---
[HR Attrition Dashboard](https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/excel/PQCapstone1.xlsx)
[HR Attrition Dataset](https://github.com/KeithTeoSeeKoy/KeithTeoSeeKoy.github.io/blob/master/excel/Capstone1-WA_Fn-HR-Employee-Attrition.csv)

---
<img src="images/HR%20Attrition%20Dashboard.JPG?raw=true" width="600"/> 
<img src="images/HR%20Attrition%20-%20Logistic%20Regression%20Modeling%20Using%20Excel%20Solver.JPG?raw=true" width="600"/>

---
### Capstone Project 2 - Healthcare Insurance Fraud Detection Analysis
This is an individual project done over 9 days. I've downloaded the Healthcare Insurance Fraud Detection dataset from Kaggle. This time round I did a Entity-Relation Diagram (ERD) in Dbeaver. Afterwhich, I've imported the data into the individual SQL table from the dataset I've downloaded. With these tables now populated with the data, I've used SQL to stitch up the tables (using SQL Join statement) I required so that I can output the files into Excel to facilitate my data analysis. After getting the two files I wanted, namely the Inpatient and Outpatient files, I used Power Query to do some minor clean up and transformation. Of course, I could have done these in the SQL environment if I want to. But in real life, when an analyst received unclean dataset, he would still need to know how to handle them.

Both the dashboard layout in Inpatient and Outpatient Analysis are similar. The analysis highlighted the top state where fraud claims is the highest, the healthcare provider and physician that are committing the most fraudulent claims. Of the charts, the most important lies in the Activity Table and Charts in each of the Dashboard. I've clearly pinpointed why each of these insurance claims are fraudulent in the Activity Table.

I've also included three Machine Learning Models (namely Logistic Regression, Decision Tree and Random Forest) to wrap up the prediction portion of this analysis work. Unlike, in my Capstone 1, I'm not using Excel Solver here. I'm using Python with xlwings acting as the bridge so that I'm able to read and write to Excel. Do note that I did not do any optimization in my three models. I'm using default models feeding the same dataset and test size for all three models.  

---
##### <<The file size related to this analysis is rather huge. Hence, I would not be able to make the analysis files available. However, should you be interested, you are still welcome to approach me.>>

---
<img src="images/FraudDetnWorkflow.JPG?raw=true" width="600"/> 
<img src="images/FraudDetnIp.JPG?raw=true" width="600"/>
<img src="images/FraudDetnOp.JPG?raw=true" width="600"/> 
<img src="images/FraudDetnModel.JPG?raw=true" width="600"/>

---
