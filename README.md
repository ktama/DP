# Deep Learning勉強用
個人の勉強用リポジトリです。

基本方針は下記のとおり。

* Microsoft Cognitive Toolkitのチュートリアルを順番に進める。
* 理解確認も含めて、なるべく訳してまとめなおす。
* メモ書きは下記の分類でそれぞれのファイルに記載する。
    * Python：[Python.md](Python.md)
    * Microsoft Cognitive Toolkit：[CNTK.md](CNTK.md)
    * Jupyter Notebook：[JN.md](JN.md)

## Python

### ライブラリのバージョン確認方法
importしたライブラリのバージョンは__version__で確認できる。
cntkの場合は下記のコードでできる。

    import cntk
    print('cntk:', cntk.__version__)

### PATHの話
Pythonのパスは、下記の順序で優先して読み込まれる。

[PythonMatrixJp || Pythonのモジュールインポートのしくみ](http://python.matrix.jp/pages/tips/import.html)

1. 実行中のファイルと同じディレクトリ
1. カレントディレクトリ
1. PYTHONPATHのディレクトリ
1. sys.pathにあるディレクトリ

## Microsoft Cognitive Toolkit

### チュートリアルプログラムの実行
本リポジトリのCNTKTutorialディレクトリのコードは下記のページにあるリポジトリのTutorialディレクトリから取得した。
環境によるファイルの変更ならびに、日本語で要約している。

[GitHub Microsoft Cognitive Toolkit](https://github.com/Microsoft/CNTK)

#### ロジスティック回帰（CNTK_101_LogisticRegression）
