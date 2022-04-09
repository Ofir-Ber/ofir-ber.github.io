## Human Activity Recognition (HAR)

**Project description:** 
In this project, we elaborate on human activity recognition tracked by wearable shoe insoles that have several sensors on them. The project's objective is to accurately predict a range of human activities. The dataset is provided by a start-up company, Embry Tech, that has collected movement data among several experiment participants. The methods used in the model building process are Correlation Analysis, PCA, Binary Logistic Regression, Decision Tree, Random Forest and finally a Catboost Classifier for multiclass classification. The findings illustrate that accurate prediction remains a complex task and while very different activities such as sitting and running are easily distinguishable, more mixed activities such as mixed walking and mixed walking that includes stairs up are more arduous to differentiate between

8 participants with different gender, age, height, and weight were recruited to perform 12 types of activities: walking, mixed walking, jogging, climbing down, climbing up, stairs up, stairs down, mixed walking that included stairs up movement, mixed walking with little pauses, standing, sitting and no activity at all.

### Models
we have used three different machine learning algorithms to classify the target variable. For that purpose we have splitted the target into two categories that define whether the human wearing the insole is moving or not. The categories of sitting, standing and no activity were combined to represent no movement and the rest to represent some movement, e.g. walking, mixed walking. 

<img src="har_images/har_1.jpg?raw=true"/ width="500" height="600">
<img src="har_images/har_2.jpg?raw=true"/>
<img src="har_images/har_3.jpg?raw=true"/>

For more details see [Jupyter Notecook](https://github.com/Ofir-Ber/HAR/blob/main/HAR.ipynb)
[Repository](https://github.com/Ofir-Ber/HAR)
