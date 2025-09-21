This project is a Natural Language Processing (NLP) task where I built a model to classify restaurant reviews from Zomato as either positive or negative.

The process involved several steps:

Data Loading: I started by loading the dataset of Zomato reviews, which includes the review text and a sentiment label (positive or negative).
Data Cleaning: I then performed text cleaning on the reviews. This involved removing punctuation and numbers, converting all text to lowercase, and removing common English stopwords. I also used stemming to reduce words to their root form (e.g., 'loving' and 'loved' become 'love'). This helps reduce the vocabulary size and focuses on the core meaning of the words.
Bag of Words Creation: After cleaning, I converted the text data into a numerical format that a machine learning model can understand using the Bag of Words model. This technique represents each review as a vector where each dimension corresponds to a unique word in the vocabulary, and the value represents the frequency of that word in the review. I limited the number of features (words) to 1500 to manage dimensionality.
Data Splitting: I split the dataset into training and testing sets to evaluate the model's performance on unseen data.
Model Training: I chose a Naive Bayes classifier to train on the training data. Naive Bayes is a simple yet effective algorithm for text classification tasks.
Prediction and Evaluation: Finally, I used the trained model to predict the sentiment of the reviews in the test set. I then evaluated the model's performance using a confusion matrix and calculated the accuracy score to understand how well it performed."
You can also mention the accuracy score you obtained (0.71 in this case) and discuss what that means in terms of the model's ability to correctly classify reviews. Good luck with your interview!
<!---
Bhargavihyma/Bhargavihyma is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
