- **SMS Spam Analysis Data**
  - Dataset:https://github.com/SH00git/NLP/blob/main/P10.0spam.csv
  - Code: https://github.com/SH00git/NLP/blob/main/P10.0%20SMS%20Spam%20Analysis.ipynb

  - Steps followed:
    - Libraries used: pandas, numpy, spacy, Scikit Learn,seaborn, matplotlib
    - Preprocessing:  Lowercasing, Stop Word and Punctuation Removal, Tokenisation, Lemmetization, Vectorization (Bag of Words and bi-grams).
    - Visualisation: Histogram plot of token length and charcter length for spam- ham messages.
    - Modelling : NaivesBayes Model tuned with GridSearchCV
    - Results: Classification Report, accuracy_score and Confusion Matrix
    - Achieved an accuracy of 0.98 

- **News Category Classification**
  - Dataset:https://www.kaggle.com/code/hengzheng/news-category-classifier-val-acc-0-65
  - Code: https://github.com/SH00git/NLP/blob/main/P11.%20News%20Category%20Classification.ipynb
 
  - Steps:
    - Libraries Used: pandas, numpy, spacy, Scikit Learn,seaborn, matplotlib, string, unicode
    - Preprocessing: Lowercasing, Stop Word and Punctuation Removal, Regex for removing special characters, Unicode text conversion  Tokenisation, Lemmetization, Vectorization (TF-IDF).
    - Visualisation: Histogram, Bar plots
    - Modelling: NaivesBayes Model tuned with GridSearchCV
    - Results: Classification Report, accuracy_score and Confusion Matrix
    - Achieved an accuracy of 0.42

- **NER Classification** - Predict the Tags of text entities based on classification Training
  - Dataset:https://www.kaggle.com/datasets/abhinavwalia95/entity-annotated-corpus?select=ner_dataset.csv
  - Code: https://github.com/SH00git/NLP/blob/main/P13.%20NER%20Recognition%20and%20Classification.ipynb
  - Steps:
    - Libraries Used: pandas, numpy, spacy, Scikit Learn,seaborn, matplotlib, string, unicode
    - Modelling: Logistic Regression, NaivesBayes Model tuned with GridSearchCV
    -  Results: Classification Report, accuracy_score and Confusion Matrix
    - Achieved an accuracy of 0.92

- **Flipkart Sentiment Analysis**
  - Dataset:
  - Code:
  - Steps:
    - Libraries Used: pandas, numpy, spacy, Scikit Learn,seaborn, matplotlib, string, unicode
    - Preprocessing: Lowercasing, Stop Word and Punctuation Removal, Regex for removing special characters, Unicode text conversion  Tokenisation, Lemmetization, Vectorization (TF-IDF).
    -  Visualisation:  Bar plots, word clouds
    - Modelling: Model Selection using cross validation, Tuned hyper parameters for logistic regression,RandomForest, SupportVector, NaivesBayes,Decision Trees using RandomizedSearchCV
    -  Results: Classification Report, accuracy_score and Confusion Matrix
    - Achieved an accuracy of 0.42
