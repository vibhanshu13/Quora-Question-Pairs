# Quora-Question-Pairs
Many people on Quora ask questions with same intent in different wordings. For better user experience on quora, these questions should be merged togather so that writers do not need to answer same question multiple times. Also it will make discovery of content easier on quora. 

# Data Fields
id - the id of a training set question pair
qid1, qid2 - unique ids of each question
question1, question2 - the full text of each question
is_duplicate - set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise.

# Model

Used the architecture provided by Bao et. al. in his research paper. LSTM based siamese network was used to identify the semantic similarity between the two questions. Refer to Bao2018 for research paper
