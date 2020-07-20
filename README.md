# Twitter-Sentimental-Analysis for offensive data


OFFENSIVE LANGUAGE IS PERVASIVE IN SOCIAL MEDIA. INDIVIDUALS FREQUENTLY TAKE ADVANTAGE OF THE PERCEIVED ANONYMITY OF COMPUTER-MEDIATED COMMUNICATION, USING IT TO ENGAGE IN BEHAVIOUR THAT MANY OF THEM WOULD NOT CONSIDER IN REAL LIFE.ONLINE COMMUNITIES, SOCIAL MEDIA PLATFORMS, AND TECHNOLOGY COMPANIES HAVE BEEN INVESTING HEAVILY ON WAYS TO COPE WITH OFFENSIVE LANGUAGE TO PREVENT ABUSIVE BEHAVIOUR IN SOCIAL MEDIA.ONE OF THE MOST EFFECTIVE STRATEGIES FOR TACKLING THIS PROBLEM IS TO USE COMPUTATIONAL METHODS TO IDENTIFY OFFENSE, AGGRESSION, AND HATE SPEECH IN USER-GENERATED CONTENT (FOR EXAMPLE, POSTS, COMMENTS, MICROBLOGS, ETC.)
<br>
ABSTRACT<br>
Toxic online content has become a major issue in
today’s world due to an exponential increase in the use of internet
by people of different cultures and educational background.
Differentiating hate speech and offensive language is a key
challenge in automatic detection of toxic text content. <br>


PROBLEM STATEMENT<br>
In this project,approach is proposed to  classify tweets
on Twitter into offensive tweet or not using logistic regression algorithm.<br>

MOTIVATION<br>
Detecting such language on online platform can help identify such users and the hateful speech.this method can benefit the betterment of the society and preventing create hatism on online platforms.this area is less researched and sholud be worked on more that’s why i chose this topic as my project. 
<br>

DATASET
<br>
offenseval-training-v1.tsv contains tweets in english language with labels whther it is offensive or not.<br>

SOFTWARE AND LIBRARIES<br>
This project uses the following software and Python libraries:<br>

Python 3.7<br>
Scikit-learn<br>
Nltk<br>
Pandas<br>
Pickle<br>
iPython Notebook<br>

BASIC TECHNOLOGY BEHIND THIS PROJECT <br>
Natural language processing (nlp)<br>
It is an area of computer science and artificial intellligence that is concerned with the interaction between computers and humans in natural language. its goal is to enable computers to understand language as well as we do. according to estimates, about 79% of all available data is in the textual form, which is highly unstructured in nature. one of the obstacles to the achievement of proper nlp is that human language is complex and can be abstract. one word can be used to express various different meanings. 
<br>

MODEL IMPLEMENTED<br>
Logistic Regression<br>

WORKFLOW
<br>
•	Imported the necessary libraries.<br>
•	Reading the dataset - the data is retrieved from social media and distributed in tab separated format. <br>
•	after successful reading of this dataset, preprocessing begins.<br>
•	Cleaning the dataset - for each line in the dataset, unnecessary words which are not useful in our classification are removed. apart from this, symbols or emticons are removed. all words are converted into lowercase letters so that there remains no discrepancy between uppercase and lowercase words.<br>
•	Noise removal - after this, all other unnecessary pieces of text like links, urls, industrt-specific words,etc. are removed. to aide in this process, tokenization is used.<br>
•	Tokenization - it is the process of splitting up a larger body of text into smaller lines, words or even creating words for a non-english language. so, it is a process of converting a line or text into tokens. <br>
•	Lexicon Normalisation - another process of removal of textual noise relates to the multiple representations exhibited by a single word. these representations mean different, but contextually all of them are similar. this step converts all these representations into their normalized form( known as lemma).<br>
•	Stemming and Lemmatization - stemming is a rudimentary rule-based process of stripping the suffixes(‘ing’, ‘ly’, ‘es’, etc.). its purpose is to reduce the words to the roots.<br>
•	lemmatization is an organized and step-by-step procedure of obtaining the root form of the word, using vocabulary and morphological analysis.<br>
•	Feature engineering (bag of words) - it is one of a series of techniques from nlp to extract features from text. this occurs by counting the frequency of words in a document. it is called a ‘bag’ of words because any information about the order or structure of words in the document is discarded.<br>
•	Hyperparameter tuning - when all data sources have been exhausted, the next step is model hyperparameter tuning. it relies more on experimental results than theory, and thus is the best method to determine the optimal settings is to try many different combinations evaluate the performance of each model.<br>
•	Model saving - this relates to applying an classifier that will fit and create a decision-based model based on ‘training’ model and then test this created model from the classifier. this process is done using pickles. these operations usually take a long time.<br>
•	Logistic Regression model is used.<br>

RESULTS <br>

accuracy for train set after saving base classifier =  0.9039841389728097<br>
accuracy for test set after saving base classifier =  0.7696374622356495<br>
accuracy for train set after saving tuned classifier =  0.8737726586102719<br>
accuracy for test set after saving tuned classifier  =  0.7673716012084593<br>



