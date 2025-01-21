# FIFA World Cup Win Prediction System Using Machine Learning

This project aims to predict the probability of a team's victory in the FIFA World Cup using machine learning techniques. By leveraging historical data of World Cup matches, we implemented and evaluated several machine learning classifiers to build an effective prediction system.

## Overview

We experimented with **five machine learning classifiers**:  
- **K-Nearest Neighbor (KNN)**  
- **Naive Bayes**  
- **Decision Tree**  
- **Logistic Regression**  
- **Support Vector Machine (SVM)**  

In addition, we explored **two ensemble classifiers**:  
- **Random Forest**  
- **Gradient Boosting**  
---
### Key Findings

- The **Gradient Boosting Classifier** achieved the **highest accuracy of 62.40%**, making it the best-performing model.  
- **Logistic Regression**, **Random Forest**, and **Support Vector Machine** also showed promising results, with accuracies above 60%.  
- The **K-Nearest Neighbor** and **Decision Tree** classifiers performed below 60%, with accuracies of **58.86%** and **59.40%**, respectively.  
- To improve performance, we combined K-Nearest Neighbor and Decision Tree into an **ensemble model**, which resulted in an accuracy of **60.22%**.  
Despite these results, the prediction accuracy can likely be improved further by exploring additional features and more advanced machine learning techniques.
---
## Datasets

We used two custom-created structured datasets for this project:  
1. **Match Dataset**:  
   - Contains data from FIFA World Cup matches spanning **1930 to 2018**.  
   - Features: 10 columns, including `Year`, `Stage`, `Home Team Name`, `Home Team Goals`, `Away Team Name`, `Away Team Goals`, etc.  
   - Total records: **916**.  

2. **Winner Dataset**:  
   - Contains the **winners of each FIFA World Cup**.  
   - Mapped with the Match Dataset for training the models.  

Data was primarily collected from reliable online sources such as Wikipedia. The raw data was stored in Excel sheets and converted to CSV format for analysis.

## Future Scope

- Experimenting with more features to enhance prediction accuracy.    
- Exploring advanced machine learning and deep learning algorithms for better performance.  

## Technologies Used

- **Programming Language**: Python  
- **Libraries**: NumPy, Pandas, Scikit-learn, Matplotlib  
- **Data Format**: CSV  
