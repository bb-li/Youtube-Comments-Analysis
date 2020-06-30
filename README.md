# Youtube Comments Analysis
Overview:
This project aims to build up classification models for the cat and dog owners from text comments and use Latent Dirichlet allocation to find out the most popular topics among the owners. There are around 6,000,000 comments recorded in the dataset and the dataset itself is unlabeled. Each data row will have an userid, an text comment and belongs to one channel.

Steps:
1. Identify and label the obvious Cat And Dog Owners in the comments. Perform data preprocessing and use RegexTokenizer and Word2Vec to tokenize the text comments.
2. Use labeled data to train and test logistic regression model, random forest model and gradient boosting model. Extract the best model.
3. Use the best model to classify all the users.
4. Use Latent Dirichlet allocation to analyze the hidden topics that are most attracted to the pet owners.

