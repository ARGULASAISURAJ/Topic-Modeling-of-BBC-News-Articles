# Topic-Modeling-of-BBC-News-Articles

This is a project on analysis and Topic modelling / document tagging of BBC Articles with LSI/LSA and LDA algorithms. 

Data is sourced from http://mlg.ucd.ie/datasets/bbc.html

The courpus contains 2,225 documents from BBC's news website corresponding to stories in five topical areas (business, entertainment, politics, sport, tech) from 2004-2005.

**Dataset snapshot**

![pic1](https://github.com/ARGULASAISURAJ/Topic-Modeling-of-BBC-News-Articles/blob/main/pic1.PNG)

**Topic modeling** has been done using **LSI/LSA and LDA algorithms**, after vectorizing the text using **TF-IDF vector** in three different ways:

(1) after normal cleaning of the text corpus (punctuation removal, stopword removal, etc.),

(2) with term frequency filter, to exclude the top 10% of the most frequent words and words that appear less than 5 times in the documents (drawing from Zipf's Law), and

(3) with a part of speech filter, to limit your TD-IDF matrix to nouns only.

Determined optimum number of topics using **coherence values**.

**Observation**

After vectorizing the text using TF-IDF vector in three different ways normal cleaning,using term frequncy,part of speech as noun and using LSI/LSA and LDA algorithms for topic modeling. Top 5 words discussed in each of topic are discussed.

From the results - LDA model using normal cleaning has better keywords and relevant to each article.

**Dataset snapshot keywords after 3 cleaning methods and 3 **

![pic3](https://github.com/ARGULASAISURAJ/Topic-Modeling-of-BBC-News-Articles/blob/main/pic3.PNG)
