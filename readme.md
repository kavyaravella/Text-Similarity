# Text Similarity

This web service checks the text similarity between two texts and gives a metric as a measure for the similarity.
The metric is a numeric value between 0 to 1. When there are no words in common, we will receive a value of 0. If it is an exactly same document, the value received will be 1.

The input folder contains all the text sample files for which the similarity will be checked. Any number of texts can be given. The Preprocess folder will contain the word and frequency for each input sample file. The similarity between every pair of text files is calculated.

The decisions taken to achieve the desired results:
 1. The similarity based metric used is Cosine Similarity. 
 2. Only the words were taken into consideration. Punctuations were removed.
 3. Stop-words and contractions were not considered in the similarity comparison.  
 4. The data structures used are sets and dictionaries.
 5. The ordering of words was not considered.

