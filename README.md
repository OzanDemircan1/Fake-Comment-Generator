# Fake-Comment-Generator
Fake Comment Generator using Reddit Corpus
This program creates fake reddit comments, based on the corpus of subreddit r/NeutralPolitics.

The default number of comments taken from the corpus is 30.000, taking a higher amount than this gives better
results however, the duration of preprocessing increases drastically.

A general topic(ideally political) in the form of a single word, must be given as input in order generate 5 comments, using the top 5 most related keywords.

A Trigram Language model is used to generate the comments.

The created comments goes through a evaluation of 2 layers, a grammar check and a positivity meter respectfully.

The last cell returns the finalized comments and their positivity level.

Please run all the cells in order.

--------------------------------------------------------------------------------------------------------------

All the work for this program was done by Ozan Demircan.
