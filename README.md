# ASTeC-detailed-results

Check the [detailed-results.csv](detailed-results.csv) for the detailed results.

The following diagram shows the experiment pipeline for the Intent Recognition study
![pipe_experiments](https://user-images.githubusercontent.com/51092246/235915299-d490bb1d-0778-4798-95db-e419acd30fd3.png)


## Columns definitions

- Dataset: Dataset used
- Cv: Wich test/train cross-validation pair was used
- Method: Which method was used
- Duration (Seconds): Duration in seconds required for training and prediction
- Micro F1: F1 score calculated using [scikit learn f1_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html) with `average = 'micro'`
- Best Pipeline: Best pipeline found by ASTeC.

## Citing us

```
@inproceedings{224390,
  author    = {Douglas Nunes de Oliveira and Luiz Henrique de Campos Merschmann},
  title     = {An Auto-ML Approach Applied to Text Classification},
  booktitle = {WebMedia '22: Brazilian Symposium on Multimedia and the Web, Curitiba, Paran{\'{\a}}, Brazil, November 7-11, 2022},
  publisher = {{ACM}},
  year      = {2022},
  doi       = {10.1145/3539637.3557054}
}
```
