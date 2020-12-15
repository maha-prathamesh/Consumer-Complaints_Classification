# Consumer-Complaints-Classification
This is a NLP Project contains concepts Tokenization, Stemming, Lemmatization, Vectorization.

## What we want as the outcome?
We would classify each complaint to its respective category, so that the complaint can be directed to the right vertical


## What is the problem?

Let us get started with the introduction to natural language processing by first looking at the problem that we are going to solve. We have a rich dataset of consumer complaints on various financial products and services. Each row in the dataset describes the complaint and the different features associated with it. In this concept, we'll first construct the features and then build a model that predicts the category into which the complaint falls. You can read more about this dataset here.

Along with the complaint narrative, the other features that are present in data are the issue, the category of the complaint, the date it was received on, the zip code, details of the customer placing the complaint and the current status of the complaint. The final idea is to build a model that will categorize each customer's complaint into a product (12 categories in all).

For the purpose of understanding how text processing works, we will specifically, work on only 2 columns of this dataset. It is evident that if we add more features, the model accuracy will rise and be more robust.

## Brief explanation of the dataset & features
Consumer Complaint Narrative: This is a paragraph (or text) written by the customer explaining his complaint in detail. The data is a string type consisting of text in the form of paragraphs.
Product: This is the category we are to classify each complaint to. The 12 categories the complaints need to be categorized into are:
'Mortgage', 'Student loan', 'Credit card or prepaid card', 'Credit card', 'Debt collection', 'Credit reporting', 'Credit reporting, credit repair services, or other personal consumer reports', 'Bank account or service', 'Consumer Loan', 'Money transfers', 'Vehicle loan or lease', 'Money transfer, virtual currency, or money service', 'Checking or savings account', 'Payday loan', 'Payday loan, title loan, or personal loan', 'Other financial service', 'Prepaid card'
