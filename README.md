# Advance-Data-Science
Natural Language Processing- Conversion of text form written expression into spoken forms
The purpose of the work reported here is to take some initial steps towards addressing deficiencies in previous approaches to text normalization. In English language picking up words like currency, date and time, local expression to make them fluent and accurate in Machine Learning. It is important factor to make it proficient at Machin level. 
Many speech and language applications, including text-to-speech synthesis (TTS) and automatic speech recognition (ASR), require text to be converted from written expressions into appropriate "spoken" forms. This is a process known as text normalization, and helps convert 11:52 to "eleven fifty-two" and $3.16 into "three dollars, sixteen cents”.  
The main task of this project is to automate the process of developing text normalization grammars with Machine Learning and various Algorithms.

The dataset is from the https://www.kaggle.com/. 
It contains a large corpus of text. Each sentence has a sentence_id. Each token within a sentence has a token_id. The before column contains the raw text, the after column contains the normalized text, the training set contains an additional column, class, which is provided to show the token type. Like PLAIN, DATE, PUNCATION, CARDINAL, ELECTRONIC, MEASURE, DIGIT, FRACTION, MONEY, ADDRESS. In addition, there is an id column used in the submission format. This is formed by concatenating the sentence_id and token_id with an underscore (e.g. 123_5).
•	en_sample_submission.csv - file showing the correct format 
•	en_test.csv - the test set, does not contain the normalized text 
•	en_train.csv - the training set, contains the normalized text

  For the given data different algorithms have been used to make text format into appropriate spoken forms. By analysing data and further processing. Hence, we can predict the after words that can be obtained by processing the before words from the data. 
We are implementing Machine Learning models like Logistics and Multinomial Naïve Bayes. We have also implemented Lesk algorithm.
