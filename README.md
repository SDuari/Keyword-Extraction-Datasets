# Keyword-Extraction-Datasets

This repository contains seven annotated datasets for automatic keyword extraction task. Every dataset contains a document (.txt or .abstr) and its corresponding gold-standard keywords list (.key or .uncontr). These datasets were used for our study of supervised and unsupervised keyword extraction. Following are the links to our published works.

1. "sCAKE: Semantic Connectivity Aware Keyword Extraction" [![DOI:10.1016/j.ins.2018.10.034](https://zenodo.org/badge/DOI/10.1016/j.ins.2018.10.034.svg)](https://doi.org/10.1016/j.ins.2018.10.034) [![Generic badge](https://img.shields.io/badge/Full%20Article-ScienceDirect-orange.svg)](http://www.sciencedirect.com/science/article/pii/S0020025518308521) [![Generic badge](https://img.shields.io/badge/Preprint-arXiv-orange.svg)](https://arxiv.org/pdf/1811.10831.pdf)

2. "Complex Network based Supervised Keyword Extractor."[![DOI:10.1016/j.eswa.2019.112876](https://zenodo.org/badge/DOI/10.1016/j.eswa.2019.112876.svg)](https://doi.org/10.1016/j.eswa.2019.112876) [![Generic badge](https://img.shields.io/badge/Full%20Article-ScienceDirect-orange.svg)](https://www.sciencedirect.com/science/article/pii/S095741741930586X) [![Generic badge](https://img.shields.io/badge/Preprint-arXiv-orange.svg)](https://arxiv.org/pdf/1909.12009.pdf)


Following are the datasets and the original papers which proposed them.

1. **Hulth2003**: Contains abstracts from *Inspec* dataset. Originally downloaded from https://github.com/snkim/AutomaticKeyphraseExtraction.
2. **WWW** and **KDD**: CS abstracts from KDD and WWW conferences. We have only kept those documents that contain at least two sentences and atleast one gold-standard keyword. Originally downloaded from https://www.dropbox.com/s/3c57qar1b0xseob/kpshare.tgz?dl=0 (Link is not available now). Full dataset can be downloaded from https://github.com/LIAAD/KeywordExtractor-Datasets/tree/master/datasets.
3. **Marujo2012**: News articles. Originally downloaded from https://github.com/snkim/AutomaticKeyphraseExtraction.
4. **Krapivin2012**: ACM full papers. Originally downloaded from https://github.com/snkim/AutomaticKeyphraseExtraction.
5. **Semeval2010**: ACM full papers. Originally downloaded from https://github.com/snkim/AutomaticKeyphraseExtraction.
6. **NLM500**: PubMed documents. Originally downloaded from https://github.com/zelandiya/keyword-extraction-datasets. ***Created for abstractive KE task.***

## Dataset details and collection statistics

| Dataset | \|D\| | L<sub>avg</sub> | N<sub>avg</sub> | K<sub>avg</sub> | KP<sub>avg</sub>| Description |
| :---         |     :---:      |     :---:      |     :---:      |     :---:      |          :--- |
| Hulth2003   | 1500 |  129   | 23 | 10 | 90.07 | Abstracts from *Inspec* dataset
| WWW     | 1248 |  174 | 9 | 5 | 64.97 | Abstracts from CS articles published in KDD conference
| KDD    | 704 | 204 | 8  4 | 68.12 | Abstracts from CS articles published in WWW conference
| Marujo2012     | 450 | 427 | 69 | 48 | 99.31 | Online news articles
| Krapivin2009     | 2304 | 7961 | 11 | 5 | 96.91 | Full scientific articles from ACM
| SemEval2010     | 244 |  8085 | 34 | 16 | 95.89 | Full scientific articles from ACM, created for SemEval2010 Task 5
| NLM500     | 500 |  4854  | 27 | 14 | 71.35 | Full papers from *PubMed* database

\|D\|: Number of documents.
L<sub>avg</sub>: Average document length, in words.
N<sub>avg</sub>: Average gold-standard keywords (unigrams) assigned per document.
K<sub>avg</sub>: Average gold-standard keyphrases (*n*-grams) assigned per document.
KP<sub>avg</sub>: Average percentage of keyphrases present in the text

## Citations:
Following are the citations for original papers.

### Hulth2003
```tex
@inproceedings{hulth2003improved,
title = "Improved Automatic Keyword Extraction given more Linguistic Knowledge",
author = "Hulth, Anette",
booktitle = "Proceedings of the 2003 Conference on EMNLP",
pages = "216--223",
year = "2003",
organization = "ACL"
}
```

### Krapivin2009
```tex 
@article{krapivin2009large,
title="Large Dataset for Keyphrases Extraction",
author="Krapivin, Mikalai and Autaeu, Aliaksandr and Marchese, Maurizio",
journal="Technical Report DISI-09-055",
year="2009",
publisher="University of Trento"
}
```

### NLM500
```tex 
@inproceedings{aronson2000nlm,
title="The NLM Indexing Initiative",
author="Aronson and others",
booktitle="Proceedings of the AMIA Symposium",
pages="17",
year="2000",
organization="American Medical Informatics Association"
}
```

### SemEval2010
```tex
@inproceedings{kim2010semeval,
title="Semeval-2010 Task 5: Automatic Keyphrase Extraction from Scientific Articles",
author="Kim, Su Nam and Medelyan, Olena and Kan, Min-Yen and Baldwin, Timothy",
booktitle="Proceedings of the 5th International Workshop on Semantic Evaluation",
pages="21--26",
year="2010",
organization="Association for Computational Linguistics"
}
```

### Marujo2012
```tex
@inproceedings{marujo2012supervised,
title="Supervised Topical Key Phrase Extraction of News Stories using Crowdsourcing, Light Filtering and Co-reference Normalization",
author="Marujo, Lu{\'\i}s and Gershman, Anatole and Carbonell, Jaime and Frederking, Robert and Neto, Joa{\`I}ƒo P",
booktitle="Proceedings of the Eighth International Conference on Language Resources and Evaluation (LREC-2012)",
year="2012"
}
```

### WWW and KDD
```tex
@inproceedings{gollapalli2014extracting,
title={Extracting keyphrases from research papers using citation networks},
author={Gollapalli, Sujatha Das and Caragea, Cornelia},
booktitle={Twenty-Eighth AAAI Conference on Artificial Intelligence},
year={2014}
}
```
