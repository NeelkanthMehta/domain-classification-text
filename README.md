**Problem Statement**
Haptik is one of the world's largest conversational AI platforms. It is a personal assistant mobile app, powered by a combination of artificial intelligence and human assistance. It has its domain in multiple fields including customer support, feedback, order status and live chat.
We have with us the dataset of Haptik containing the messages it receives from the customers and which topic(class) the messages refer to.
We need to create a model predicting which class a particular message belongs to using NLP. We will also try to use techniques like LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation) to assign topics to new messages.

**About the dataset**
The snapshot of the data you will be working on:


Solving it will help you apply the following skills:
1. Text preprocessing techniques like tokenization, vectorization, etc.
2. Implementation of Logistic Regression, Naive Bayes and Linear SVM.
3. Topic modelling with LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation)
4. Usage of coherence score to determine the optimum number of topics

The following steps were involved in the modelling process:
1. Data Cleaning: it involved transforming several columns (OneHotEncode types) into a single categorical target label
2. Data Processing: For efficiency, we choose to work with only a subset of entire dataset. This involved transforming the data with Tf-Idf vectorizing (text column) and LabelEncoding (target variable) and usual train-test splitting.
3. Classification and Implementation: fitting Logistic Regression, Naïve Bayes classifier and Support Vector Classifier to the dataset and comparing their accuracy
4. Validation of test set: we test the models on the left over data (ones that weren't included in the training sample dataset)
5. LSI modelling: Latent Semantic Analysis is a type of topic model that enables us classify documents based on most likely topics, it is more robust than simple cosine similarity in that it handles synonymy and polyonymy well. We measure the model performance with its coherence values.
