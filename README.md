# Term Tagger

This project is based in term recognition using BERT for the NLP domain. To see more of our methodology, results and analysis, see the [report](https://github.com/averieso/nlp-term-tagger/blob/main/terminology_paper.pdf). 

By [Averie Ho Zoen So](https://github.com/averieso) and [Silviya Silwal](https://github.com/ssilwalcode)

## Installation

Use the requirements.txt file to install all necessary packages.

```bash
$ pip install -r requirements.txt
```

## Usage

- Use `python bert_pipeline.py` to run experiments for bert. Hyperparameters are pre-defined in the code.
- Use `python nltk_spacy_iob.py` to run off-the-shelf baseline experiments.
- Use `python max_rule_baseline.py` to run the max rule baseline.
- Use `python ner_span_eval.py` to conduct span-based evaluation and error analysis. 
- Use `python cohens_kappa.py` to measure inter-annotator agreement. 





