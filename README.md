# MIPA: Mutual Information Based Paraphrase Acquisition via Bilingual Pivoting

Our paraphrase acquisition method, called MIPA, first acquires lexical paraphrase pairs by bilingual pivoting and then reranks them by pointwise mutual information and distributional similarity.
The complementary nature of information from bilingual corpora and from monolingual corpora makes our paraphrase acquisition method robust.

The English version of the paraphrase database was constructed from French-English bilingual corpus of [Europarl-v7](http://www.statmt.org/europarl/) and English monolingual corpus of [English Gigaword 5th Edition](https://catalog.ldc.upenn.edu/LDC2011T07).
The Japanese version of the paraphrase database was constructed from English-Japanese bilingual corpora of [The Kyoto Free Translation Task](http://www.phontron.com/kftt/index.html) and [Tanaka Corpus](http://www.edrdg.org/wiki/index.php/Tanaka_Corpus) and Japanese monolingual corpus of [BCCWJ](http://pj.ninjal.ac.jp/corpus_center/bccwj/en/).

The form of each line in the paraphrase database:
  `original word <TAB> paraphrase <TAB> MIPA score`

Use and/or redistribution of the paraphrase database is permitted under the conditions of [Creative Commons Attribution-Share-Alike License 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

For questions, please contact [Tomoyuki Kajiwara at Tokyo Metropolitan University](https://sites.google.com/site/moguranosenshi/).
