# SMS_Spam_Detection_using_NLP
A supervised deep learning project using Natural Language Processing(NLP) that classifies a given SMS as a spam/ham message.

![spam_ham_5](https://github.com/user-attachments/assets/78297550-6ec2-4cd3-ad4c-2e50645195be)


### Dependencies/Libraries used:
* Pandas
* Numpy
* Seaborn
* Sklearn
* NLTK
* Pickle
* Streamlit

### Input data:
Dataset - [https://www.kaggle.com/datasets/bagavathypriya/spam-ham-dataset](https://www.kaggle.com/datasets/bagavathypriya/spam-ham-dataset)

### Building Model:

* ### Imbalanced Data
 ![spam_ham_M1](https://github.com/user-attachments/assets/26bbc461-fa27-46de-ade0-6500ae798e3e)

* ### Visualizing the trend of number of characters, number of words and number of sentences in a spam/ ham SMS
 ![spam_ham_M2](https://github.com/user-attachments/assets/0d707bc2-d0e7-4359-a5bf-38f6e6db78f2)

* ### Plotting the trend as a Heatmap
 ![spam_ham_M3](https://github.com/user-attachments/assets/6a45fc9f-898a-4912-af99-4cc3446a06e3)

* ### Most common words in a Spam Corpus
 ![spam_ham_M4](https://github.com/user-attachments/assets/34427830-51b1-4a10-ac4c-1d5c2f5c891a)

* ### Performance of Various Models
 ![spam_ham_M5](https://github.com/user-attachments/assets/6f942ba8-cddf-4e79-99b8-550acbbaa3fe)


# Results:
* Applied NLP techniques like tokenization, lemmatization, and stop words and punctuation removal using NLTK and regex.
* Performed feature engineering with handcrafted features such as digit count and email length.
* Implemented various classification models, Naive Bayes, SVC, ETC to find the best performer.
* Created an ensemble model, improving the accuracy from 97.87% to 98.25%.
* Designed & deployed a basic UI with Streamlit for classifying new inputs as spam or ham.


# Top Performing Model
Combined Support Vector Classifier, Multinomial Naive Bayes and Extra Trees Classifier to build an Stacking Classifier Model( Ensemble Model) whose:

* ### Accuracy: 0.9825918762088974
* ### Precision: 0.9736842105263158

# Testing Examples:
* Example 1:![spam_ham_2](https://github.com/user-attachments/assets/8dd33e66-a2c5-46fe-ab4f-61c8d02d9f3d)


* Example 2:![spam_ham_4](https://github.com/user-attachments/assets/1ef23986-224a-498d-9de6-248c8b4e59ad)


* Example 3:![spam_ham_3](https://github.com/user-attachments/assets/642a163a-3892-4e5c-a237-48d8581c5df4)


