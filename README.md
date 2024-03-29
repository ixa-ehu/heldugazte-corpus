# Heldugazte Corpus

This repository contains 6 million tweets in Basque, obtained from  for analysis of *informal and formal* use of Basque language in Tweets. The repository is divided in two parts, the anotated corpus and the full corpus.

## Annotated corpus 

+ 1000 tweets each classified as formal or informal, based on the writing stile of the text of the tweet (eu-heldugazte.tsv). These 1000 tweets had been splited into:

+ eu-heldugazte-train.tsv, containing 650 manually annotated tweets for training.
+ eu-heldugazte-test.tsv, containing 350 manually annotated tweets for test.

The data of the corpus consists on the class and the text of the tweet. The class is formal (for) or informal (inf). This corpus was used to train and test classifiers for formal and informal use of language.

## Full corpus

The entire corpus is formed by more than 6 million tweets in Basque from 7.977 different users, obtained during Spring/Summer of 2018. This corpus is available in the following link: http://ixa2.si.ehu.es/heldugazte-corpus/heldugazte-osoa.tar.gz.

The format provided is one file per user containing the IDs of every tweet by that specific user. The file is named using the ID of each user.

# How to use

Please cite the following publication if you use any of the versions of the Heldugazte corpus:

```
@Article{info10060212,
  AUTHOR = {Fernandez de Landa, Joseba and Agerri, Rodrigo and Alegria, Iñaki},
  TITLE = {Large Scale Linguistic Processing of Tweets to Understand Social Interactions among Speakers of Less Resourced Languages: The Basque Case},
  JOURNAL = {Information},
  VOLUME = {10},
  YEAR = {2019},
  NUMBER = {6},
  ARTICLE-NUMBER = {212},
  URL = {https://www.mdpi.com/2078-2489/10/6/212},
  ISSN = {2078-2489},
  DOI = {10.3390/info10060212}
}
```
