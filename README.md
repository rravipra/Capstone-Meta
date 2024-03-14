# Capstone-Meta
MSDS Capstone Project in collaboration with Meta affiliated with the University of Washington. (Team Members: Ananya Bajaj, Hema Varshita, Rashmika Reddy, Rthvik Raviprakash, Sayani Boral)

# Objective:

Facebook Integrity uses ML models to help identify and remove content that violates its community standards, such as hate speech, graphic violence, and sexual exploitation. These models are trained on large datasets of examples of bad content and are able to recognize patterns and features that are associated with such content. This spans a variety of policies, including spam messages, fake accounts, and fraudulent activity.

However, these ground-truth datasets are gathered through human review, which is a slow and costly process. To accurately identify violations, human reviewers must have expertise in the relevant area. This expertise can be difficult to find and retain, and the cost of hiring and training qualified reviewers can be high. Additionally, with 3 billion monthly active users, Facebook's user base is massive. If even only 0.1% of users created a violating post each month, that is still 3 million violations to identify and address. Obviously, we are not able to manually review every post that may pose a violation risk. 

Therefore, one of the biggest challenges within Integrity is finding high enough label volume to train a reliable model. With the improvements across LLMs, we can generate sample data at high volumes to train models to tackle very sparse problems.

# Data:

Social Media Hateful & Toxic Comments: [Dataset](https://socialmediaarchive.org/record/19?ln=en)

General Reddit dataset: [Dataset](https://www.kaggle.com/datasets/smagnan/1-million-reddit-comments-from-40-subreddits)

# Code files:

The notebooks file in this repository are:

- falcon_7B.ipynb
- T5_model.zip
- NN_model.ipynb
- Logistic_regression_model.ipynb

# Images of graphs acquired from the code outputs:

# Considerations with the Data:
