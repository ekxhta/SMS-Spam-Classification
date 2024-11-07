# SMS Spam Classification

This project aims to classify SMS messages as spam or ham (non-spam) using machine learning. The dataset used in this project consists of SMS messages labeled as either 'spam' or 'ham'. The steps followed in this project include data cleaning, exploratory data analysis (EDA), text preprocessing, feature extraction, and model building.

## Steps Involved

1. **Data Cleaning**: The dataset is cleaned by removing null values and duplicates to ensure high-quality data.
2. **Exploratory Data Analysis (EDA)**: Key insights are derived from the data, such as the average number of characters, words, and sentences in spam and ham messages.
3. **Text Preprocessing**: The text data undergoes several preprocessing steps, including:
   - Lowercasing
   - Tokenization
   - Removal of special characters, stop words, and punctuation
   - Stemming
4. **Vectorization**: The text data is converted into numerical format using the Bag of Words technique.
5. **Model Building and Evaluation**: We train two models:
   - **Logistic Regression**: A linear model for classification.
   - **Random Forest**: An ensemble model using multiple decision trees.
   
   After evaluation, Logistic Regression achieved an accuracy of 97.26%, while Random Forest achieved 96.23%.

## Installation

1. Clone the repository:

Memory updated
Here are the different descriptions for your project:

a) README for GitHub
markdown
Copy code
# SMS Spam Classification

This project aims to classify SMS messages as spam or ham (non-spam) using machine learning. The dataset used in this project consists of SMS messages labeled as either 'spam' or 'ham'. The steps followed in this project include data cleaning, exploratory data analysis (EDA), text preprocessing, feature extraction, and model building.

## Steps Involved

1. **Data Cleaning**: The dataset is cleaned by removing null values and duplicates to ensure high-quality data.
2. **Exploratory Data Analysis (EDA)**: Key insights are derived from the data, such as the average number of characters, words, and sentences in spam and ham messages.
3. **Text Preprocessing**: The text data undergoes several preprocessing steps, including:
   - Lowercasing
   - Tokenization
   - Removal of special characters, stop words, and punctuation
   - Stemming
4. **Vectorization**: The text data is converted into numerical format using the Bag of Words technique.
5. **Model Building and Evaluation**: We train two models:
   - **Logistic Regression**: A linear model for classification.
   - **Random Forest**: An ensemble model using multiple decision trees.
   
   After evaluation, Logistic Regression achieved an accuracy of 97.26%, while Random Forest achieved 96.23%.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/username/sms-spam-classification.git
     ```
2. Navigate to the project directory:

   ```bash
    cd sms-spam-classification
   ```
3. Install dependencies using pip:
   ```bash
      pip install -r requirements.txt
   ```
4. Ensure the following dependencies are included in your requirements.txt:
    - pandas
    - numpy
    - scikit-learn
    - matplotlib
    - seaborn
    - nltk

## Dataset

The dataset used for this project contains SMS messages labeled as spam or ham. The dataset is listed in the resources as **Spam_SMS.csv**

## Conclusion

The project demonstrates how to use machine learning techniques for SMS spam classification. Logistic Regression showed slightly better performance than Random Forest for this dataset.

