# SMS Spam Classifier

## About

Here we compare different Machine Learning models and identify which model is best suited for classifying the given SMS into Spam or Ham classes.

## Method

1. **Data Cleaning**
    - Removed all unnecessary columns.
    - Converted the text labels (Ham/Spam) to integers (0/1).
    - Removed duplicate entries.

2. **Exploratory Data Analysis (EDA)**
    - Analyzed the dataset to extract insights.
    - Noticed that spam messages generally have more characters than ham messages.

3. **Data Preprocessing**
    - Transformed the text data using NLTK (Natural Language Toolkit) to make it easier to train.

4. **Model Training**
    - Trained the processed data with various models from `sklearn`.
    - Compared the performance of these models.

## Results

Among all the models, Random Forest and Multinomial Naive Bayes were the best performing models, both achieving a precision of 1.0 and an accuracy above 95%. Precision is prioritized in this context to minimize the misclassification of ham messages as spam, as ham messages may be significant to the user.
