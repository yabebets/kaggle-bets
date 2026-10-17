# kaggle-bets

Kaggle を題材に機械学習を学ぶためのリポジトリ。

## セットアップ

```bash
uv sync
# Kaggle API トークンを ~/.kaggle/access_token に置いた上で
uv run kaggle competitions download -c titanic -p data/titanic
unzip data/titanic/titanic.zip -d data/titanic && rm data/titanic/titanic.zip
```

## ノートブック

| # | 内容 |
|---|---|
| [01](notebooks/01_titanic_first_submission.ipynb) | Titanic：EDA、前処理、ランダムフォレスト、交差検証、最初の提出 |
