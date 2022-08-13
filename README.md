# ASTeC-detailed-results

Check the [detailed-results.csv](detailed-results.csv) for the detailed results.

## Columns definitions

- Dataset: Dataset used
- Cv: Wich test/train cross-validation pair was used
- Method: Which method was used
- Duration (Seconds): Duration in seconds required for training and prediction
- Micro F1: F1 score calculated using [scikit learn f1_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) with `average = 'micro'`
- Best Pipeline: Best pipeline found by ASTeC.

## Citing us

```
@INPROCEEDINGS{224390,
    AUTHOR="Douglas Nunes de Oliveira and Luiz Henrique de Campos Merschmann",
    TITLE="An Auto-ML Approach Applied to Text Classification",
    BOOKTITLE="WebMedia 2022 () ",
    ADDRESS="",
    DAYS="7-11",
    MONTH="nov",
    YEAR="2022",
    KEYWORDS="AI, Machine Learning and Deep Learning; Data Mining; Natural Language Processing",
    URL="http://XXXXX/224390.pdf"
}
```
