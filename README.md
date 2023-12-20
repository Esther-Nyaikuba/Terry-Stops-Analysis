# Terry Stops Analysis in Seattle

**Author**: Esther Nyaikuba
<p  align = "centre">
   <img width= "600" height="350" src="terry_stops.jpg">
</p>

# Introduction
In the United States, a Terry stop allows police to briefly detain a person based on reasonable suspicion of criminal activity. This project explores the the potential impact of features such as the presence of weapons, time of day, officer characteristics (gender, race), and subject characteristics (perceived race, perceived gender) influencing the arrest outcome of Terry stops. 

# Project Overview
The aim of this project is to develop a binary classification model that predicts whether an arrest will occur after a Terry Stop. This analysis aims to provide insights into the factors influencing stop outcomes and explore the potential impact of features such as the presence of weapons, time of day, officer characteristics (gender, race), and subject characteristics (perceived race, perceived gender). This algorithm, as well as the insights generated from this study will be crucial for law enforcement agencies optimize their procedures during Terry Stops, leading to more informed decision-making and potentially improving overall public safety.


# Business Understanding
The key stakeholders for this project are law enforcement agencies focusing on seattle. This analysis aims to provide insights into the factors influencing stop outcomes and explore the potential impact of features such as the presence of weapons, time of day, officer characteristics (gender, race), and subject characteristics (perceived race, perceived gender). This algorithm, as well as the insights generated from this study will be crucial for law enforcement agencies optimize their procedures during Terry Stops, leading to more informed decision-making and potentially improving overall public safety. The project will be conducted with a focus on transparency, fairness, and ethical considerations.

# Data Understanding
This data represents records of police reported stops under Terry v. Ohio, a landmark Supreme Court case in 1967-8. This is When a police officer has a reasonable suspicion that an individual is armed, engaged in, or about to be engaged in criminal conduct, the officer may briefly stop and detain an individual for a frisk or search.
Each record contains perceived demographics of the subject, as reported by the officer making the stop and officer demographics as reported to the Seattle Police Department. 

### Data Structure
The dataset has the following structural features; 
1. Number of rows = 58,370 
2. Number of columns = 23 
3. The data format is CSV. 

# Modeling

### Model Evaluation
<b>Logistic Regression:</b>

The Logistic Regression model achieved an accuracy score of 74.90%. This means that, on average, it correctly predicted the target variable for 74.90% of the instances in the dataset.

<b>Decision Tree:</b>

The Decision Tree model achieved a slightly higher accuracy score of 74.92% compared to Logistic Regression. It suggests that the Decision Tree model performed slightly better in terms of accuracy on the same dataset.

<b>KNN (K-Nearest Neighbors):</b>

The KNN model achieved the highest accuracy score among the three models, with a score of 74.97%. This indicates that the KNN model, using the chosen configuration, had the highest accuracy in predicting the target variable.

# Conclusion
In conclusion, this project provided valuable insights into the performance of three machine learning models on the given dataset. The findings contribute to our understanding of Terry Stops, and the lessons learned can guide future projects in this field. Overall, the project served as a valuable exploration of terry stops in seattle and lays the foundation for further analysis and improvements.


# Recommendations
<ul>
<li>Conduct training programs for law enforcement officers to enhance their judgment on deciding when it is suitable to make an arrest during a Terry stop. Providing clear guidelines on differentiating situations requiring immediate action from those that can be addressed later can contribute significantly to reducing unnecessary arrests.</li>

<li>Emphasize the importance of recording the officer's precinct in all Terry stops. This additional data point can enhance the predictive capabilities of the model.</li>

<li>Implement training modules for officers to recognize optimal situations for conducting a 'frisk' during Terry stops. Understanding the appropriate circumstances for frisking individuals can serve as a crucial indicator in predicting arrests accurately.</li>
<ul>
    
<b># Next Steps</b>
<ul>
<li>Further analyze unknown or missing values.</li>
<li>Experiment with SMOTE.</li>
<li>Tune Support Vector Classification.</li>
</ul>