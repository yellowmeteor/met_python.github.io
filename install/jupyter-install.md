# Jupyter Notebookの導入

Pythonはスクリプト言語です。  
なので，例えばtest.pyというスクリプトファイルを作成して，

```
$ python test.py
```

というコードを実行すれば，Pythonを使用することができます。  
しかし，1度スクリプトを記述しただけで希望する結果が得られることはほとんどなく，スクリプトを微調整していくことになるでしょう。  
test.pyの内容を微調整しては，このコードを実行する，ということを繰り返すよりも良い方法があります。  
その1つが，Jupyter Notebookを使用することです。

## Jupyter Notebookのインストール

Jupyter Notebookのインストールは，[Pythonの導入](python-install.md)を済ませた後であれば，下のコマンドを実行するだけで可能です。

```
$ conda install -c conda-forge jupyter
```

インストールが終了したら，

```
$ jupyter notebook
```

と実行します。  
Jupyter Notebookのデフォルトのポートは8888となっていますので，任意のブラウザを起動して，URL欄に "http://localhost:8888" と入力すると，ブラウザで実行できるようになります。

## Jupyter Notebookの基本的な使い方

Jupyter Notebookの基本的な使い方は，BlogCatさんのこちらのページを参考にしてみて下さい。

[Jupyter Notebook の使い方](https://python.atelierkobato.com/jupyter-basic/)

私はオートセーブ機能まで変更していないのですが，基本的な使い方が簡単にまとまっています。  
Filesの画面で右上隅からNew▼をクリックし，Python 3を選択すると，Filesで表示されているディレクトリに，Untitled.ipynbというJupyter用のファイルが作成されます。  
希望のディレクトリ下でipynbのファイルを作成したい場合には，Filesの画面でディレクトリを選択し，希望のディレクトリに移動してから，New▼をクリックし，Python 3を選択してください。

[ホームへ戻る](https://yellowmeteor.github.io/met_python.github.io/)