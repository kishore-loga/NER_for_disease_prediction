# Project Overview

This project demonstrates two different approaches to Named Entity Recognition (NER) for disease prediction:

1. Dictionary-based matching using the sci_sm Spacy model.
2. Pretrained NER model (bc5cdr) to predict disease names in biomedical text.


# Dependencies
Make sure to install the following dependencies to run the notebook:

- pip install spacy
- pip install scispacy
- pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_core_sci_sm-0.5.4.tar.gz
- pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_ner_bc5cdr_md-0.5.4.tar.gz


# Required Libraries:
spacy
scispacy
en_core_sci_sm (Spacy model for biomedical text)
en_ner_bc5cdr_md (Pretrained NER model for disease recognition)


# How to Run
1. Clone the repository or download the notebook.
2. Create a python Environment
3. Install the dependencies listed above.
4. Run the notebook to see the output of both dictionary-based and pretrained model-based NER approaches.
