# Titanic Survival Prediction
This project involves using the Titanic dataset to predict whether a passenger survived the disaster. 
For this purpose, we utilised a Decision Tree classifier.

## Project Structure
- Part 1: Data Preparation
- Part 2: Model Training and Evaluation

## Dataset
The Titanic dataset contains information about passengers, including their survival status, demographics, and other relevant attributes. 
The dataset includes the following columns:
- **PassengerId**: Unique identifier for each passenger
- **Survived**: Survival status (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings or spouses aboard the Titanic
- **Parch**: Number of parents or children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)


## Project Steps
### Part 1: Data Preparation
- Loading the Dataset:
The dataset is loaded into a pandas DataFrame for analysis.
- Observing the Data:
Initial exploration of the data to understand its structure and identify any immediate issues.
- Removing Uninformative Columns:
Columns that do not provide useful information for predicting survival are removed.
- Encoding Categorical Features:
Categorical features are encoded using the one-hot encoding method to convert them into numerical values.
- Splitting the Dataset:
The dataset is split into training, development, and test sets to evaluate model performance at different stages.

### Part 2: Model Training and Evaluation
- Plotting the Tree Structures:
Visualising the decision tree structures with varying maximum depths to understand how depth affects complexity.
- Tuning the Decision Tree Model:
Altering the maximum depths from 2 to 10 and evaluating the model's performance on the training and development sets.
Finding the best depth where the model performs well on both the training and development sets.
- Evaluating the Model's Performance:
Using the test set to evaluate the final model's performance and ensure its generalisability.
