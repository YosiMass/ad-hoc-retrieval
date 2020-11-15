# ad-hoc-retrieval

This package contains the generated paraphrases for the three ad-hoc datasets (TREC-COVID, WSK and AP) used in the EMNLP'20 paper "Ad-hoc Document Retrieval using Weak-Supervision with BERT and GPT2"

The package contains the following files  

- TREC-Covid-paraphrases-filtered.tsv
- WSJ-paraphrases-filtered.tsv
- AP-paraphrases-filtered

The three files are the generated paraphrases for each of the three datasets used in the paper.
Those paraphrases have passed the filter as described in the paper. 

Each line in those files contains two fields that are tab separated

- The original title from the document
- A generated paraphrase

For example -

```Clinical review: A systematic review of corticosteroid use in infections	Strong evidence for the use of corticosteroids in septic shock```


If you use the data please include citations to the following paper:

```
Yosi Mass, Haggai Roitman, 2020,
Ad-hoc Document Retrieval using Weak-Supervision with BERT and GPT2,
in proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing, Nov 16-20
```
