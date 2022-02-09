Jigsaw Rate Severity of Toxic Comments
==============================

Kaggleコンペ　Jigsaw Rate Severity of Toxic Commentsのリポジトリ

Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make


--------

## やったことを簡単に記載
|ファイル名|Model|概要|
|:-----:|:-----|:-----|
|015_exp|RoBERTa-Base|jigsaw-classsification のデータを学習|
|016_exp|Toxic-BART|-----------|
|017_exp|RoBERTa-Base|Ruddit のデータを学習|
|018_exp|RoBERTa-Base|---------|
|019_exp|-------|Detoxifyの予測ラベル+Ruddit TF-IDFのEnsemble|
|020_exp|-------|Detoxifyの予測ラベル(all)+Ruddit TF-IDFのEnsemble|
|021_exp|-------|-------|
|022_exp|-------|Detoxifyの予測ラベル+Ruddit TF-IDF をless/moreの回数で線形回帰|
|023_exp|RoBERTa-Base|Wiki-Attack　のデータを学習|
|024_exp|Luke-Base|Wiki-Attack　のデータを学習|
|025_exp|Luke-Base|Wiki-Attack　のデータを学習|
|026_exp|DeBERTa-Base|jigsaw-classsificationのデータを学習&Attentionの可視化|
|027_exp|DeBERTa-Base|jigsaw-unbiasedのデータを学習&Attentionの可視化|
|028_exp|RoBERTa-Base|jigsaw-unbiasedのデータを学習|
|029_exp|RoBERTa-Base|Toxic-spanのデータを学習|
|030_exp|RoBERTa-Base|Toxic-spanのデータを学習|
|031_exp|Toxic-BERT|Ruddit　のデータを学習&Attentionの可視化|
|032_exp|HATE-BERT|OLID のデータを学習|
|033_exp|HATE-BERT|jigsaw-classsificationのデータを学習|
|034_exp|-------|当たってないデータ確認|
|035_exp|HATE-BERT|jigsaw-classificationのデータにSpellCheckerを追加|
|036_exp|HATE-BERT|TFIDF x kNN|
|037_exp|RoBERTa-Base|less < moreでMarginRankingLoss学習|
|038_exp|RoBERTa-Base|less < moreでMarginRankingLoss学習&tito CV|
|039_exp|albert-Base|less < moreでMarginRankingLoss学習&tito CV|
|040_exp|funnel-small|less < moreでMarginRankingLoss学習&tito CV|
|041_exp|DeBERTa-Base x MultiHead|less < moreでMarginRankingLoss学習&tito CV|
|045_exp|Electra-Base x MultiHead|less < moreでMarginRankingLoss学習&tito CV|
|046_exp|GPT-2|less < moreでMarginRankingLoss学習&tito CV|
|047_exp|RoBERTa-Base x MaxPooling|less < moreでMarginRankingLoss学習&tito CV|
|048_exp|RoBERTa-Base x Conv1D|less < moreでMarginRankingLoss学習&tito CV|
|050_exp|GPT-2 x layer concat|less < moreでMarginRankingLoss学習&tito CV|
|051_exp|RoBERTa-Basex layer concat|less < moreでMarginRankingLoss学習&tito CV|
|052_exp|GPT-2 x layer concat x MultiHead|less < moreでMarginRankingLoss学習&tito CV|
|053_exp|Funnel-Base x layer concat|less < moreでMarginRankingLoss学習&tito CV|