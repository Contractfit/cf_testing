# cf_testing

This subrepository contains the instructions and data required to test and extract phrasal verbs from English running text. 

### DATA ###

*wiki.valid.raw* 

3K+ lines of text scraped from English Wikipedia entries. 

### DESCRIPTION ###

IMPORTANT: The code should be written in Python v3+
You are free to consult the internet and use any libraries as needed. 

A phrasal verb is well described on Wikipedia ;) 
https://en.wikipedia.org/wiki/Phrasal_verb

As per example: 

She *ran into* some issues while running the first code. 
He consulted a copy of the NLP bible by Jurafsky and Martin before *giving up on* the assignment.

We want you to extract as many and as accurately as possible the phrasal verbs present in 


### SUGGESTED APPROACH ###

You can use any of the open-source available NLP packages to parse the text line per line
=> textblob, nltk, spacy, stanfordNLP 

Return a csv with 4 (or more) columns containing the following information: 

1. sentence_id
2. sentence
3. phrasal verb encountered
4. textual span in sentence
*optionals*

e.g. 

0.0   ;   She ran into some issues while running the first code.     ;     (4,12)  ;   *run into*  ;   95
1. 1   ;   He consulted a copy of the NLP bible by Jurafsky and Martin before giving up on the assignment.     ;     (67,79)  ;   *give up on*  ;   80
2. 2   ;   The dog *was sick of* fetching the stick.    ;   (12,19)    ;   /   ;   5 (NOT a phrasal verb construction)


Bonus: 
* Derive the lemmatized form of an extracted phrasal verb construction
* Calculate the confidence that an extraction construction is indeed a phrasal verb


### DELIVERABLE ###

Send an email to provisioned mail address XXX@contract.fit with the following in 1 ZIP:

* Your code
* Instructions to run the code
* The csv with extracted phrasal verbs
* Achieved results (small report: use appropriate descriptions!, max 2 paragraphs)
