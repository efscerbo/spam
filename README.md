# spam
Spam classifier via logistic regression

Note: The dataset of emails which I downloaded was too
big to upload on GitHub (> 25 MB), so I split it into
two separate files: 'data/train_1.csv' and 
'data/train_2.csv'. If you wish to run the code, you 
should load each of these files separately and then combine 
them, as in the following:

emails_1 = pd.read_csv('data/train_1.csv')

emails_2 = pd.read_csv('data/train_2.csv')

emails = pd.concat([emails_1, emails_2], ignore_index=True)
