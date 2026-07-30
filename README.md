# Python の冒険

## 📖 [オンライン版はこちら（Web サイトで読む）](https://qingruikz.github.io/python-adventure/)

経済学部の学生に向けて書かれた、全 16 章の Python 入門教材です。プログラミングをまったく触ったことのない人でも、Python の基礎から実際の経済データを使った計量分析・機械学習まで、一冊で進められる構成になっています。

## この教材の特徴

**経済学を学ぶ人のための題材**
課税対象所得、消費と所得、少子化率と高齢化率、地域別の病院数といった実際の統計データを教材に取り込み、経済学の分析でそのまま使える形で Python を学びます。プログラミングのための例題ではなく、経済分析の場面で必要になる処理を軸にしています。

**対話形式の本文**
登場人物のやりとりを追いながら読み進める対話形式で執筆しています。つまずきやすい箇所は、疑問が出てくる順番に会話の中で解きほぐしていきます。

**豊富な挿絵**
各章に多数の挿絵を配置しています。挿絵は Gemini で生成した画像をベースに、教材の内容に合わせて加筆・修正したものです。

**扱う範囲**
Python の基礎（変数・文字列・リスト・条件分岐・繰り返し・辞書・関数・モジュール・オブジェクト指向）、データの取得（Web スクレイピングと Web API）、データクリーニング、可視化、記述統計と回帰分析による計量分析、そして機械学習までを扱います。

読むだけなら上のオンライン版か、下の表のタイトルから GitHub 上でそのまま閲覧できます。腰を据えて学習するときは、教材一式を Google Drive にアップロードして Google Colab で開く方法をおすすめします。手順は下の「使い方」に書いてあります。

## 目次

| 章 | タイトル | 実行 |
| --- | --- | --- |
| 第 1 章 | [冒険の始まり！Python と Colab の世界へようこそ](notebooks/01_welcome_%E3%82%88%E3%81%86%E3%81%93%E3%81%9DPython%E3%81%B8.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/01_welcome_%E3%82%88%E3%81%86%E3%81%93%E3%81%9DPython%E3%81%B8.ipynb) |
| 第 2 章 | [魔法の計算術と記憶術！式、演算、そして変数](notebooks/02_expressions_%E5%BC%8F%E3%80%81%E6%BC%94%E7%AE%97%E3%80%81%E3%81%9D%E3%81%97%E3%81%A6%E5%A4%89%E6%95%B0.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/02_expressions_%E5%BC%8F%E3%80%81%E6%BC%94%E7%AE%97%E3%80%81%E3%81%9D%E3%81%97%E3%81%A6%E5%A4%89%E6%95%B0.ipynb) |
| 第 3 章 | [言葉を操る魔法！文字列の活用術を探る](notebooks/03_strings_%E6%96%87%E5%AD%97%E5%88%97.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/03_strings_%E6%96%87%E5%AD%97%E5%88%97.ipynb) |
| 第 4 章 | [集え、データたち！リストとタプルの集団操作術](notebooks/04_lists_%E3%83%AA%E3%82%B9%E3%83%88%E3%81%A8%E3%82%BF%E3%83%97%E3%83%AB.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/04_lists_%E3%83%AA%E3%82%B9%E3%83%88%E3%81%A8%E3%82%BF%E3%83%97%E3%83%AB.ipynb) |
| 第 5 章 | [運命の分かれ道！プログラムの流れを操る条件分岐](notebooks/05_conditionals_%E6%9D%A1%E4%BB%B6%E5%88%86%E5%B2%90.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/05_conditionals_%E6%9D%A1%E4%BB%B6%E5%88%86%E5%B2%90.ipynb) |
| 第 6 章 | [時を操る魔法！？ 繰り返し処理とループの極意](notebooks/06_loops_%E7%B9%B0%E3%82%8A%E8%BF%94%E3%81%97.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/06_loops_%E7%B9%B0%E3%82%8A%E8%BF%94%E3%81%97.ipynb) |
| 第 7 章 | [名前で呼び出す魔法の棚！辞書（ディクショナリ）を使いこなす](notebooks/07_dicts_%E8%BE%9E%E6%9B%B8.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/07_dicts_%E8%BE%9E%E6%9B%B8.ipynb) |
| 第 8 章 | [魔法の呪文を自作する！関数の定義と活用](notebooks/08_functions_%E9%96%A2%E6%95%B0.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/08_functions_%E9%96%A2%E6%95%B0.ipynb) |
| 第 9 章 | [魔法の工房と道具箱！モジュール・パッケージ・ライブラリ活用術](notebooks/09_modules_Python%E3%81%A7%E4%BD%BF%E3%81%88%E3%82%8B%E9%83%A8%E5%93%81%E3%81%9F%E3%81%A1.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/09_modules_Python%E3%81%A7%E4%BD%BF%E3%81%88%E3%82%8B%E9%83%A8%E5%93%81%E3%81%9F%E3%81%A1.ipynb) |
| 第 10 章 | [創造の魔法！自分だけのキャラとアイテムを生み出すオブジェクト指向](notebooks/10_oop_%E3%82%AA%E3%83%96%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%8C%87%E5%90%91.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/10_oop_%E3%82%AA%E3%83%96%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E6%8C%87%E5%90%91.ipynb) |
| 第 11 章 | [宝の真価を引き出せ！データクリーニングという名の秘術](notebooks/11_cleaning_%E3%83%87%E3%83%BC%E3%82%BF%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/11_cleaning_%E3%83%87%E3%83%BC%E3%82%BF%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%8B%E3%83%B3%E3%82%B0.ipynb) |
| 第 12 章 | [データに隠された物語を読み解け！可視化の魔法とグラフ表現](notebooks/12_visualization_%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E5%8F%AF%E8%A6%96%E5%8C%96.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/12_visualization_%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E5%8F%AF%E8%A6%96%E5%8C%96.ipynb) |
| 第 13 章 | [データの本質を数値で語れ！記述統計分析の冒険](notebooks/13_statistics_%E8%A8%98%E8%BF%B0%E7%B5%B1%E8%A8%88%E5%88%86%E6%9E%90.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/13_statistics_%E8%A8%98%E8%BF%B0%E7%B5%B1%E8%A8%88%E5%88%86%E6%9E%90.ipynb) |
| 第 14 章 | [データから法則を見抜け！回帰分析と予測の魔法](notebooks/14_regression_%E5%9B%9E%E5%B8%B0%E5%88%86%E6%9E%90.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/14_regression_%E5%9B%9E%E5%B8%B0%E5%88%86%E6%9E%90.ipynb) |
| 第 15 章 | [インターネットの海から宝（データ）を探し出せ！Web スクレイピングと Web API 活用術](notebooks/15_scraping_Web%E3%82%B9%E3%82%AF%E3%83%AC%E3%82%A4%E3%83%94%E3%83%B3%E3%82%B0%E3%81%A8Web%20API.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/15_scraping_Web%E3%82%B9%E3%82%AF%E3%83%AC%E3%82%A4%E3%83%94%E3%83%B3%E3%82%B0%E3%81%A8Web%20API.ipynb) |
| 第 16 章 | [人工知能の扉を開く！機械学習への招待](notebooks/16_machine-learning_%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92.ipynb) | [Colab で開く](https://colab.research.google.com/github/qingruikz/python-adventure/blob/main/notebooks/16_machine-learning_%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92.ipynb) |

ページが重くて GitHub 上で表示できない章は、[nbviewer](https://nbviewer.org/github/qingruikz/python-adventure/tree/main/notebooks/) からもプレビューできます。

## 使い方

初めての方は第 1 章から順に進めてください。第 1 章〜第 10 章が Python の基礎、第 11 章〜第 16 章がデータ分析と機械学習の実践編です。

### おすすめ：Google Drive にアップロードして Colab で学習する

この教材は Google Colab で学ぶことを前提に作られています。第 11 章以降ではデータファイルを読み込み、分析結果をファイルに書き出すため、**教材一式をまるごと Google Drive に置いてから始める**のがいちばん確実です。次の手順で準備してください。

1. このページの緑色の「Code」ボタンから「Download ZIP」を選び、教材一式をダウンロードする
2. ZIP を展開し、`notebooks` フォルダを丸ごと Google Drive にアップロードする（中の `データ` フォルダも一緒にアップロードされていることを確認してください）
3. Drive 上のノートブックを右クリックし、「アプリで開く」→「Google Colaboratory」で開く
4. ノートブック冒頭の `drive.mount("/content/drive")` のセルを実行し、Google Drive を接続する
5. 続くセルの `CWD` に、そのノートブックが入っているフォルダのパスを貼り付ける（例：`/content/drive/MyDrive/notebooks`）

この形にしておけば、自分で書き加えたコードも実行結果も Drive に保存されるので、次に開いたときに続きから学習できます。第 11 章以降が分析結果を書き出す `出力ファイル` フォルダも自動的に作られます。

### すぐに試したいとき

目次の「実行」列にある Colab リンクからは、ダウンロードなしでその場でノートブックを開けます。ただし読み取り専用で開くため、編集した内容を残すには Colab のメニューから「ドライブにコピーを保存」を選んでください。データを読み込まない第 1 章〜第 10 章のお試しに向いています。

### ローカルで実行する場合

このリポジトリを clone して、Jupyter Notebook または VS Code で開きます。この場合は `CWD` に自分の環境でのフォルダのパスを指定してください。

```bash
git clone https://github.com/qingruikz/python-adventure.git
cd python-adventure
jupyter notebook
```

## 教材で使うデータ

第 11 章以降の演習で読み込む CSV・Excel ファイルは `notebooks/データ/` にまとめてあります。ノートブックは `CWD` を起点にこのフォルダを参照するため、`notebooks` フォルダごとアップロードしていれば追加の設定は要りません。

## オンライン版について

オンライン版は [Jupyter Book](https://jupyterbook.org/) で生成し、GitHub Actions で GitHub Pages に自動公開しています。目次の構成は `myst.yml`、公開の手順は `.github/workflows/deploy.yml` に定義してあります。`main` ブランチに push すると自動で再ビルドされます。

手元でプレビューする場合は次のコマンドを実行します。

```bash
pip install jupyter-book
jupyter-book start
```

## ライセンス

[MIT License](LICENSE) の下で公開しています。授業や自習に自由にご利用ください。
