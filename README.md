# Named Entity Recognition
Named Entity Recognition (NER) is a traditional task used for many information retrieval applications such as indexing and text mining. The aim of NER systems is to locate important names and proper names in a given text and to categorize them into a set of predefined classes. Three main classes are usually used for named entity labeling : persons, locations and organizations.

NER techniques can be gathered in two groups: rule-based methods and machine learning based approaches. For rule-based methods, 
rules are extracted manually. They are related to linguistic descriptions, trigger words and lexicons of proper names. 
These rules use patterns and regular expressions in order to locate named entities and classify them. The machine-leaning approaches, on the other hand, aim to extract rules autonomously using large corpora.

In the NewsEye project we are interested to recognizing named entities through historical documents stored on digital libraries. 
These document are almost digitized and indexed through their OCRed version and include numerous errors.
In the presence of these errors, rule-based methods are clearly very disoriented to override the degradation generated by the OCR in the extracted text. On the other hand, machine learning methods present a sufficient flexibility to be adapted to process noisy texts. For this reason, we use in this project machine learning systems to recognize named entities both on clean and noisy texts. 

# Systems
Core-NLP : https://github.com/stanfordnlp/CoreNLP/tree/master/doc/ner
BidLSTM-CRF : https://github.com/guillaumegenthial/sequence_tagging
BidLSTM-CNN : https://github.com/kamalkraj/Named-Entity-Recognition-with-Bidirectional-LSTM-CNNs
BidLSTM-CNN-CRF : https://github.com/UKPLab/emnlp2017-bilstm-cnn-crf

# Data
In order to simulate OCRed documents, we have used the available corpora of CoNLL-2002 and CoNLL-2003; we added to them artificial types and levels of OCR degradations.

# Models
