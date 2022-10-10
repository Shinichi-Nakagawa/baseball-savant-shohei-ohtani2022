# Baseball Data Analytics sample for Baseball Savant

[Baseball Savant Search](https://baseballsavant.mlb.com/statcast_search)から取得したデータを可視化・分析するためのサンプル

## Install

poetry もしくは pip で導入.

Python 環境は venv で予め作成することを推奨.

```shell
$ python3 -m venv .venv
$ source .venv/bin/activate
(.venv)$
```

### Poetry

```shell
(.venv)$ poetry install
```

### pip

[Google Colab](https://colab.research.google.com)等を使う場合はこちら.

```shell
(.venv)$ pip install -r requirements.txt
```

## Run

```shell
(.venv)$ jupyter lab
```

## code

- [打撃データ分析サンプル(notebook/batting.ipynb)](./notebook/batting.ipynb)
- [投球データ分析サンプル(notebook/pitching.ipynb)](./notebook/pitching.ipynb)

## sample data

- [大谷翔平さんの打球データ（2022/04/07 - 2022/10/05）](./notebook/dataset/20221005_baseball-savant-shohei-ohtani-atbat.csv)
- [大谷翔平さんの投球データ（2022/04/07 - 2022/10/05）](./notebook/dataset/20221005_baseball-savant-shohei-ohtani-pitch.csv)

## データ項目について

意味については以下のドキュメントを参考にしてください.

なお, sample data には予め km/h および m に単位換算済みのカラムが含まれています.

- [オリジナルのデータ仕様](https://baseballsavant.mlb.com/csv-docs)
- 上記オリジナル仕様の翻訳・解説
  - https://shinyorke.hatenablog.com/entry/statcast-csv-docs-ja
  - [日本語解説（Google Spreadsheet）](https://docs.google.com/spreadsheets/d/1P-5cK13FHlvjQIAxNbpAfzTEF-xoiIw8jyIuOZ5X8kA/edit?usp=sharing)
