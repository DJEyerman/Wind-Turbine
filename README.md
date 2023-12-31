# Predictive Maintenance for Wind Turbines

In this data science project, our objective was to develop a robust predictive maintenance model for wind turbines, leveraging various classification algorithms. The project aimed to proactively identify potential equipment failures and optimize maintenance schedules, thereby minimizing downtime and maximizing operational efficiency.

## Objective:
    The primary goal was to create a predictive maintenance model that could forecast potential 
    issues in wind turbines before they occur. This proactive approach would enable timely 
    maintenance interventions, ultimately enhancing the reliability and performance 
    of the turbines.

## Data Collection:
    A comprehensive dataset was collected, encompassing a variety of features such as turbine 
    sensor data, historical maintenance records, weather conditions, and operational parameters. 
    This diverse dataset served as the foundation for training and evaluating the predictive 
    maintenance models.

## Classification Models:
    Several powerful classification algorithms were employed to develop and compare predictive 
    maintenance models:
        1. Gradient Boosting (GradBoost)
        2. AdaBoost
        3. Bagging
        4. Random Forest
        5. Decision Tree
        6. Logistic Regression
        7. XGBoost (XGB)

## Model Development:
    Each classification model was meticulously trained and fine-tuned using the collected 
    dataset. The models were designed to predict the likelihood of a turbine requiring 
    maintenance within a specified time frame.
    
![Wind_Turbine_Final_Confusion_Results](https://github.com/DJEyerman/Wind-Turbine/assets/38670302/e7c948d3-0540-4f7b-9661-c83897c873b4)

## AdaBoost Model with Oversampling:
    After rigorous evaluation, the AdaBoost model, implemented with oversampled data 
    to address class imbalance, emerged as the most effective predictive maintenance 
    model. AdaBoost's ability to adapt and improve the performance of weak learners, 
    combined with oversampling techniques, resulted in a robust model for identifying 
    potential maintenance needs.
    
  ![Wind_Turbine_Final_Confusion_Matrix](https://github.com/DJEyerman/Wind-Turbine/assets/38670302/24f5ee9a-c814-4645-8cc0-e51ccfc928f6)

## Model Evaluation:
    All models were rigorously evaluated using key performance metrics such as precision, 
    recall, accuracy, and the area under the Receiver Operating Characteristic (ROC) curve. 
    The AdaBoost model consistently demonstrated superior performance, particularly in 
    correctly identifying instances requiring maintenance.  The final confusion matrix was:     

## Business Impact:
    The implementation of the AdaBoost model with oversampling data has significant 
    implications for wind turbine operations. By accurately predicting maintenance needs, 
    the project empowers wind farm operators to plan and execute maintenance activities 
    more efficiently, reducing downtime and operational costs.

## Conclusion:
    This data science project exemplifies the successful application of various 
    classification models to address the crucial challenge of predictive maintenance 
    for wind turbines. The chosen AdaBoost model, augmented with oversampling techniques, 
    stands out as a powerful tool for enhancing the reliability and longevity of wind 
    turbine assets. The insights gained from this project pave the way for a data-driven 
    approach to maintenance planning, optimizing the performance of renewable energy infrastructure.

