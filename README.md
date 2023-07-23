# Violence-Tweet-Classification:
## Overview
The primary objective of "Classifying Violence Text" is to build a robust machine learning model capable of categorizing text documents into specific violence classes. By analyzing the textual content, we strive to uncover patterns and features that differentiate the various forms of violence, thereby contributing to our collective effort in addressing these pressing societal challenges.

## Dataset
For this undertaking, I utilized a dataset sourced from [Kaggle](https://www.kaggle.com/datasets/gauravduttakiit/violence-tweet-classification), comprising textual descriptions of violence incidents, meticulously labeled with five distinct classes representing the different forms of violence. This dataset serves as the foundation for training, validating, and evaluating our classification model.

## Data Preprocessing
To ensure the model's efficacy, we subjected the text data to essential preprocessing steps, including:
- Converting all text to lowercase to maintain uniformity in text representation.
- Removing punctuations to focus solely on the meaningful words.
- Eliminating common stop words to reduce noise and enhance signal detection.
- Applying lemmatization to simplify the words and reduce them to their base or root form.

## Text Vectorization
In order to convert the preprocessed text into numerical features, we leveraged the TF-IDF (Term Frequency-Inverse Document Frequency) Vectorizer. This powerful technique captures not only the significance of individual words in a document but also their relevance across the entire corpus.

## Machine Learning Model
The Machine Learning model we chose for this classification task is the widely-used Logistic Regression algorithm. Renowned for its simplicity and efficiency in binary and multi-class classification problems, Logistic Regression proved to be a suitable choice for our project. We trained the model on the transformed TF-IDF features to effectively categorize the text documents into their respective violence classes.

## Tools and Technology Used
In this data science endeavor, I harnessed the capabilities of various Python libraries, including:
- Pandas: For seamless data manipulation and analysis.
- Matplotlib and Seaborn: For creating insightful data visualizations and plots.
- Scikit-Learn: To implement and evaluate the machine learning models.

## Results and Insights
The trained Logistic Regression model demonstrated commendable performance in classifying violence text, achieving notable accuracy and precision across the violence classes. The insights gleaned from this classification effort offer valuable understanding into the distinct characteristics of each form of violence, potentially aiding in devising effective prevention strategies and support mechanisms.


![eco](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/b7be84b5-ff70-4954-a3fa-25dc460b8dd9)

![emov](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/17b11b1b-2394-442c-9130-b55e3795628d)

![harmful](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/e7030684-4c44-452f-a7f0-41a38e29aa3a)

![phys_vi](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/54b4d69b-5064-4621-ad3a-7578e672092d)

![sx_vio](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/ebd1c074-436c-4baf-b0e0-f46e51cb9991)

![wordcount](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/3d05e22c-b2db-4c2b-9d63-db381ffdfcd9)

![confusion_matrix](https://github.com/NyAiko/Violence-Tweet-Classification/assets/105801284/4f201b12-c3be-42ab-83bd-f0e9cfc2465b)

**Tools Used:** Python, Pandas, Matplotlib, Seaborn, Scikit-Learn
