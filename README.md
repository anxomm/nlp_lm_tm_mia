# Introduction

This repository contains a list of notebooks that deal with typical NLP and LM tasks. There is no specific goal in any of them beyond learning how to apply the techniques and learning the technologies.

# Content
There a total of six different notebooks. Three of them are related to Natural Language Understanding, one of them aimed to design a basic Language Model, and the other three deal with Text Mining tasks:

- [NLU_PoS_Tagging](notebooks/NLU_PoS_Tagging.ipynb): also called grammatical tagging, is the process of marking up a word in a corpus as corresponding to a particular part of speech, based on both its definition and its context. For example, it involves the identification of nouns, verbs, adjectives, verbs, etc. It can be considered as a classification task for a machine learning model.

- [NLU_Dependency_Parsing](notebooks/NLU_Dependency_Parsing.ipynb): is the task of extracting a dependency parse of a sentence that represents its grammatical structure and defines the relationships between "head" words and words, which modify those heads.

- [LM_toyML](notebooks/LM_toyML.ipynb): a Language Model is a model that assigns  probabilities to sequences of words, being able to predict the next word in the sequence given the words that precede it. For example, ChatGPT.

- [TM_Sparse_Dense_Retrieval](notebooks/TM_Sparse_Dense_Retrieval.ipynb): Sparse information retrieval leverages tokenized representation of the senteces to retrieve the most relevant documents based on mathematical functions that scores the similarity between a document and a set of tokens (words). It is based on Bag-of-Words techniques. Dense retrieval, on the other hand, opts to learn a dense representation of the words (meaningful vectors that captures the semantic information).

- [TM_Sentiment_Analysis_Twitter](notebooks/TM_Sentiment_Analysis_Twitter.ipynb): sentiment analysis models from HuggingFace are leveraged to detect the polarity of tweets in different topics.

- [TM_Scalable_QA_System](notebooks/TM_Scalable_QA_System.ipynb): use Haystack to build a Question & Answering (QA) system on the PubMed corpus in order to answer medical questions and obtain accurate responses in natural language.
