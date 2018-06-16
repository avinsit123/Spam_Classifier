Spam Classifier in Octave Language


Objective:To predict if email is spam(1) or not spam(0) using Support Vector Machines


Method

Step 1:Preprocessing->In processEmail.m,the email preprocessing and normalization steps have been implemented.Some of them include changing all URls to a commom keyword,reducing all similar words to their stemmed form,removing punctuations etc.

Step 2:Mapping->All the words are mapped to their respective indices in the dictionary file Vocab.txt.Check processEmail.m

