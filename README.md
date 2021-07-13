# Modeling-Passengers-Airport-and-Airline-Choice-Behaviour
This is my academic team project. Due to privacy concerns, data, codes, and reports will not be published.

## Problem description
### What drives passengers’ choice of airport and airline?
Two international airports in Seoul Metropolitan Area
- Gimpo airport: Smaller and old, but closer to the city 
- Incheon airport: Larger and new hub airport, but farther from the city 

![alt text](https://github.com/TrucAPhan/Modeling-Passengers-Airport-and-Airline-Choice-Behaviour/blob/3b4308ccfe23ca415c260640bf1f4434461fbd7f/Korea%20Airports.png)

## Data description
- Survey data of 488 respondents
- 27 variables (originally 38 variables)
  - Airport choice
    - GMP, ICN
  - Airline
    - Korean Air (KE), Asiana Air (OZ), Korean LCC, Foreign Carriers
  - Socio-demographic: age, gender, occupation, income, etc
  - Alternative-Specific : flight information, travel time, mode of transport, etc

## Data Mining Procedures Using Python 
- EDA:
  1. Clean Redundant Data
  2. Process Missing Values
  3. Variable Recategorization/Regroup
  4. Process Outliers
  5. Variables Selection according to the Correlation Matrix Forward Method, and Holdout Method
- Modeling:
  1. Logistic Model
  2. Decision Tree Model
- Model Evaluation
  - Airport Choice Model: Logit model performance is slightly better than that in Tree model, yielding the following results:
    - Accuracy: 83.97%
    - Precision: 77.91%
    - Recall: 97.1%
  - Airline Choice Model: Similar to airport prediction, the prediction result of Logit model for airlines choice is also slightly better compared to the Tree model -- see results below:
    - Accuracy: 71.54%  
    - Precision: 73.04 % 
    - Recall: 93.33 % 
- Recommendation: We recommend using Logit model for both airport and airline selection due to high sensitivity rate.


