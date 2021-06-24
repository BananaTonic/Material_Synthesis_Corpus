# NLP resorces for inorganic materials science
This code and data is a companion to the paper, "Analyzing Research Trends in Inorganic Materials Literature Using NLP".

# Demo
`demo_ner.ipynb` contains a Python demo showcasing the NER tagger introduced in this paper. `demo_train.ipynb` also provided an example of training the NER models.

# Annotated IOB-corpus for NER
`corpus/*.tsv` contains tokenized and labelled information for 301 synthesis process. Each annotated process are splited as "train.tsv", "devel.tsv", or "test.tsv". This annotated documents contains equal-length arrays of tokens and their respective labels.
`ann` contains raw annotation files in the BRAT annotation format. You can load these into your own instance of BRAT and modify the annotations however you like.

# Pretrained model
Along with this work, we also open-source pre-trained NER tagger using our corpus. Links to the NER tagger is follows: https://figshare.com/articles/dataset/Synthesis_NER_Tagger/14832798
