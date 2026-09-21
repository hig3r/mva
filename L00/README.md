# L00 準備

## L00_01 
- 個人課題
- 提出物なし

まだ訪れていない人は，科目のGemini Notebookを訪れ，今日の授業内容について質問してみましょう


## L00_02
- 個人課題
- 提出物なし

Moodleにログインしましょう

https://learn.hig3.net の練習問題の練習を実行しましょう

## L00_03
- 個人課題
- 提出物なし

### 説明 Google Colaboratory
プログラミング言語としてPythonを使います．Cを`hello.c`に書くように，Pythonを`hello.py`に書いて実行することは3年3Q ネットワーク及び演習で扱います．

ここでは，Pythonを，Notebook環境でのみ扱います．Notebook環境としてはGoogle Colaboratoryを使います．

Google Colaboratoryは，データ分析では，実行して眺めるものとして使っていましたが，ここでは，やりたいことに応じて，自分でサンプルを加工したり，自分でサンプルを選択してゼロから書き換えたりできることが目標です．

「（Jupyter) Notebook環境で使う」は，まあ，「Cをエディタで編集して実行する」と同格です．`*.c` に相当するのは `*.ipynb` です．

「Google Colaboratoryを使う」は，まあ，「CをVisual Studio Codeで書いて実行する」と同格です．Google Colaboratory では，`*.ipynb`をGoogleドライブ内に保存します．

Notebook環境では，編集するコードと実行結果が一組の「コードセル」として表示されます．コードセル単位でも，Notebook全体でも実行できます．1行ずつ実行するような環境をREPL(レプル)と呼びますが，まあその例になっています．


### 手順
1. ここにある [mva_L00_03_REPL.ipynb](mva_L00_03_REPL.ipynb) を開き，「Google Colaboratoryで開く」を選択しましょう．このファイルは，Google Drive のどこどこに保存されます．
2. Google Drive ([Gmail](https://mail.google.com/a/mail.ryukoku.ac.jp)で▦アイコンからGoogle Driveを選ぶ)の`Colab Notebooks`フォルダを選んでファイルを見ましょう．
3. [mva_L00_03_REPL.ipynb](mva_L00_03_REPL.ipynb)を読みながら各セルを実行しましょう．

## L00_04
- チーム課題
- 提出物 .ipynb ファイル(2026-09-30水13:30)

1. 臨時の2名チームを作りましょう．
1. メンバーのうち1名が，https://learn.hig3.net のL00_04から3変量データのCSVファイルをダウンロードします．
1. [mva_L00_04_Pandas_Regression.ipynb](mva_L00_04_Pandas_Regression.ipynb)を開いて実行し，ダウンロードしたCSVファイルを読み込みます．
2. 目的変数$y$ を`height`，説明変数$x$ を `width` として，散布図を描き，回帰係数 $y=\beta_1 x + \beta_0$ の $\beta_0, \beta_1$ を推定しましょう．
3. 推定した回帰係数を，Notebookの先頭に記しましょう．
4. 完成したNotebookを `.ipynb` ファイルとしてダウンロードし，チームメンバーと，Teams chatまたはメール添付で共有します．
5. 各チームメンバーは，Moodle に `.ipynb` ファイルを提出します．
