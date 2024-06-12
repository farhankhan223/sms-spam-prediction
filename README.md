# sms-spam-prediction
It looks like you've developed a comprehensive text classification model for spam detection using the SMS Spam Collection dataset. Here's a summary of what you've done:

1. **Data Cleaning and Exploration**:
   - Imported necessary libraries and the dataset.
   - Explored the dataset's structure and shape.
   - Cleaned the dataset by dropping unnecessary columns and removing duplicate rows.
   - Conducted exploratory data analysis (EDA) to understand the distribution of spam and ham messages.
   - Visualized the distribution of various text-related features.

2. **Text Preprocessing**:
   - Converted text to lowercase.
   - Tokenized text into words.
   - Removed special characters, stopwords, and punctuation.
   - Applied stemming to convert words to their root forms.
   - Created word clouds to visualize the most frequent words in spam and ham messages after preprocessing.

3. **Model Building**:
   - Utilized CountVectorizer to convert text data into numerical features.
   - Split the dataset into training and testing sets.
   - Trained multiple classification models including Gaussian Naive Bayes, Multinomial Naive Bayes, and Bernoulli Naive Bayes.
   - Evaluated models using accuracy, confusion matrix, and precision scores.
   - Trained additional models such as Support Vector Classifier, K-Nearest Neighbors, Decision Tree, Logistic Regression, Random Forest, AdaBoost, Bagging, Extra Trees, and Gradient Boosting.
   - Employed a Voting Classifier to combine predictions from multiple models.

4. **Deployment**:
   - Saved the CountVectorizer and the Random Forest model using pickle for future use.
   - Mentioned an intention to create a Streamlit app for SMS prediction and adding a README file on GitHub.

For creating a Streamlit app, you can follow these steps:

1. Install Streamlit: `pip install streamlit`
2. Create a Python script containing the app code.
3. Define the UI elements and model prediction logic within the script.
4. Run the app using `streamlit run <filename.py>`.

For GitHub, create a README file detailing your project, including its purpose, dataset description, model details, and instructions for running the Streamlit app. You can also include any relevant visualizations or screenshots. Once created, commit the README file to your GitHub repository.

If you need further assistance with Streamlit app creation or README file formatting, feel free to ask!
