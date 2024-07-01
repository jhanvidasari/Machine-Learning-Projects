# Hate Speech Detection Project
## Overview
This project focuses on detecting hate speech in textual data sourced from Reddit comments. 

Hate speech detection is crucial for maintaining a safe and respectful online environment and can be approached using machine learning techniques.

## Dataset
The dataset used in this project consists of 3000 Reddit comments labeled as either hateful (1) or non-hateful (0).

Each comment is processed to identify patterns and linguistic cues that differentiate hate speech from regular discourse.

## Methodology
### Data Preprocessing
- **Text Cleaning**: The comments underwent preprocessing steps such as removing special characters, converting text to lowercase, and handling punctuation.

- **Tokenization**: Tokenization was performed to break down sentences into individual words or tokens.

- **Stopword Removal**: Common English stopwords (e.g., "the", "and", "is") were removed to focus on meaningful words.

- **Lemmatization**: Words were lemmatized to reduce them to their base or root form, enhancing consistency in word representation.

### Feature Extraction
**TF-IDF Vectorization**: Text data was transformed into a TF-IDF (Term Frequency-Inverse Document Frequency) matrix. This technique assigns weights to words based on their frequency in a document relative to their frequency in the entire corpus. TF-IDF helps in identifying important words while downweighting common words that appear across many documents.

### Model Training
Several machine learning algorithms were trained and evaluated for hate speech classification:

- Decision Tree
- Logistic Regression
- Naive Bayes (Bernoulli)
- Random Forest
- Gradient Boosting
- AdaBoost
- XGBoost

### Model Evaluation
Each model was evaluated using metrics such as accuracy. 

The Random Forest classifier emerged as the top performer, achieving a high accuracy score without overfitting.

### Visualization
**Word Clouds**: Visual representations of the most frequent words in hateful and non-hateful comments were generated using WordCloud. These visuals provided insights into the language patterns and emphasized the differences between the two categories.

### Results and Conclusion
The project successfully demonstrated the application of machine learning techniques for hate speech detection.

The **Random Forest classifier**, with an **accuracy** of **98.65%**, proved effective in distinguishing between hateful and non-hateful comments.

Further improvements could involve exploring deep learning models or incorporating domain-specific features for enhanced accuracy.
