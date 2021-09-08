# Annotated IOB-corpus for NER
This code and data is a companion to the paper, "Analyzing Research Trends in Inorganic Materials Literature Using NLP".

`corpus/*.tsv` contains tokenized and labelled information for 301 synthesis process. Each annotated process are splited as "train.tsv", "devel.tsv", or "test.tsv". This annotated documents contains equal-length arrays of tokens and their respective labels.
`ann` contains raw annotation files in the BRAT annotation format. You can load these into your own instance of BRAT and modify the annotations however you like.
