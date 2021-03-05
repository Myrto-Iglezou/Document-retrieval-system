#  Document retrieval system

### Project description

This exercise is about developing a document retrieval system to return titles of scientific
papers containing the answer to a given user question. You will use the first version of
the COVID-19 Open Research Dataset (CORD-19) in your work (articles in the folder comm use subset).
</br>
For example, for the question “What are the coronaviruses?”, your system can return the
paper title “Distinct Roles for Sialoside and Protein Receptors in Coronavirus Infection”
since this paper contains the answer to the asked question.
</br>
To achieve the goal of this exercise, you will need first to read the paper Sentence-BERT:
Sentence Embeddings using Siamese BERT-Networks, in order to understand how you
can create sentence embeddings. In the related work of this paper, you will also find other
approaches for developing your model. For example, you can using Glove embeddings,
etc. In this link, you can find the extended versions of this dataset to test your model, if
you want. You are required to:
</br>
1. Preprocess the provided dataset. You will decide which data of each paper is useful
to your model in order to create the appropriate embeddings. You need to explain
your decisions.
2. Implement at least 2 different sentence embedding approaches (see the related work
of the Sentence-BERT paper), in order for your model to retrieve the titles of the
papers related to a given question.
3. Compare your 2 models based on at least 2 different criteria of your choice. Explain
why you selected these criteria, your implementation choices, and the results. Some
questions you can pose are included here. You will need to provide the extra questions
you posed to your model and the results of all the questions as well.

