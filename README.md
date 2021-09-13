![C4TA04910A_experimental](https://user-images.githubusercontent.com/12994311/132538133-dd1161f3-796d-4c7a-b94c-c1cd6eea8bf2.png)

# Annotated IOB-corpus for Analyzing Material Research Trends
This code and data is a companion to the paper, "Analyzing Research Trends in Inorganic Materials Literature Using NLP".

`corpus/*.tsv` contains tokenized and labelled information for 301 synthesis process. Each annotated process are splited as "train.tsv", "devel.tsv", or "test.tsv". This annotated documents contains equal-length arrays of tokens and their respective labels.
`ann` contains raw annotation files in the BRAT annotation format. You can load these into your own instance of BRAT and modify the annotations however you like.

# License agreement
This dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation. You can view a license summary [here](https://creativecommons.org/licenses/by-nc/4.0/).

# Citation
If you use this corpus for your research, please cite our paper.
```
@article{Kuniyoshi2021AnalyzingRT,
  title={Analyzing Research Trends in Inorganic Materials Literature Using NLP},
  author={Fusataka Kuniyoshi and Jun Ozawa and Makoto Miwa},
  journal={ArXiv},
  year={2021},
  volume={abs/2106.14157}
}

@inproceedings{Kuniyoshi2020AnnotatingAE,
  title={Annotating and Extracting Synthesis Process of All-Solid-State Batteries from Scientific Literature},
  author={Fusataka Kuniyoshi and Kohei Makino and J. Ozawa and Makoto Miwa},
  booktitle={LREC},
  year={2020}
}
```
