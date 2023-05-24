# Email-Classifier

Link for Web Application : https://mohneetkaur-email-classifier-app-zdd1i1.streamlit.app/

The Email Classifier project is a machine learning-based system that aims to predict whether an incoming email is spam (unwanted or unsolicited) or ham (legitimate or desired). It utilizes various techniques from natural language processing and text classification to analyze the content and characteristics of emails.

The project involves training a classification model using a labeled dataset of emails, where each email is labeled as either spam or ham. The model learns patterns and features from these labeled examples to make predictions on new, unseen emails.

To build the classifier, the project utilizes a combination of preprocessing techniques such as tokenization, removing stop words, and applying stemming or lemmatization. Feature extraction methods like bag-of-words or TF-IDF (Term Frequency-Inverse Document Frequency) may be employed to represent the emails as numerical feature vectors. These vectors capture the presence or importance of certain words or phrases in the email content.

With the trained classifier, the system can accept new email inputs and analyze their content using the learned model. It assigns a probability or confidence score indicating the likelihood of the email being spam or ham. Based on this prediction, the system can take appropriate actions, such as filtering spam emails into a separate folder or flagging them for review.

The models used in the Email Classifier project are:

SVC (Support Vector Classifier)
KN (K-Nearest Neighbors)
NB (Naive Bayes)
DT (Decision Tree)
LR (Logistic Regression)
RF (Random Forest)
AdaBoost (Adaptive Boosting)
BgC (Bagging Classifier)
ETC (Extra Trees Classifier)
GBDT (Gradient Boosting Decision Tree)

The Email Classifier project serves as a valuable tool for email providers, organizations, or individuals to enhance their email filtering and prioritize important communications. By accurately identifying spam emails, it helps improve email management, reduces the risk of falling for scams or phishing attempts, and enhances overall productivity and security.

