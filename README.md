# Rock-Vs-Mine Prediction


A sonar rock vs mine predictive system using logistic regression aims to classify sonar signals as either coming from rocks or mines (metal cylinders). 

Creating a predictive system involves several steps, including data preprocessing, building the logistic regression model, training the model, evaluating its performance, and making predictions. Here's a detailed approach to building a sonar rock vs. mine predictive system using logistic regression:

### Step 1: Data Collection
- Obtain the dataset. For this example, we will use the "Sonar, Mines vs. Rocks" dataset from Kaggle.

### Step 2: Data Preprocessing
1. **Load the Data:**
   - Import the necessary libraries.
   - Load the dataset into a Pandas DataFrame.

2. **Normalize the Data:**
   - Normalize the features to bring them to a similar scale.

3. **Label Encoding:**
   - Convert the categorical labels ('R' for rock, 'M' for mine) into binary numerical values (0 and 1).

### Step 3: Building the Logistic Regression Model
- Use the `LogisticRegression` class from scikit-learn.

### Step 4: Training the Model
- Split the dataset into training and testing sets.
- Train the model using the training data.

### Step 5: Evaluating the Model
- Evaluate the model's performance using metrics such as accuracy score.

### Step 6: Making Predictions
- Use the trained model to make predictions on new data.

- While on Training data you will be get the accuracy of  83.42245989304813 %
- And test data accuracy obtained is 76.19047619047619 %
