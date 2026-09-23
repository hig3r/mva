# E00 準備

## E00_01 
- 個人課題
- 提出なし

まだ訪れていない人は，科目のGemini Notebookを訪れ，今日の授業内容について質問してみましょう

## E00_02
- 個人課題
- 提出 それぞれMoodle

- Moodleにログインし，コース[多変量解析☆演習](https://learn.hig3.net/moodle/course/view.php?id=23)のE00に進みましょう．
  - 初回アンケートに答えましょう．
  - 説明を聞いた後，学習履歴データ分析への同意のお願いに回答しましょう．
  - 練習問題の練習を実行しましょう．
  - （今後は毎回は書きませんが，来週までにL01パートの練習問題L01を実行してTrialL01に備えましょう）

## E00_03
- チーム課題
- 提出 Moodleに各個人が `.ipynb` ファイルを提出(2026-09-24木13:30)

### 説明 Google Colaboratory
プログラミング言語としてPythonを使います．Cを`hello.c`に書くように，Pythonを`hello.py`に書いて実行することは3年3Q ネットワーク及び演習で扱います．

ここでは，Pythonを，Notebook環境でのみ扱います．Notebook環境としてはGoogle Colaboratory(Colab)を使います．

「(Jupyter) Notebook環境で使う」は，まあ，「Cをエディタで編集して実行する」と同格です．`*.c` に相当するのは `*.ipynb` です．

「Colabを使う」は，まあ，「CをVisual Studio Codeで書いて実行する」と同格です．Colabでは，`*.ipynb`をGoogleドライブ内に保存します．

Colabは，科目データ分析では，実行して眺めるものとして使っていましたが，この科目では，やりたいことに応じて，自分でサンプルを加工したり，自分でサンプルを選択してゼロから書き換えたりできることが目標です．

Notebook環境では，編集するコードと実行結果が一組の「コードセル」として表示されます．コードセル単位でも，Notebook全体でも実行できます．1行ずつ実行するような環境をREPL(レプル)と呼びますが，まあその例になっています．

### 手順
1. 臨時の2名チームを作りましょう．
2. 1名がドライバーとなって，リポジトリにある [mva_E00_03_REPL.ipynb](mva_E00_03_REPL.ipynb) をWebで表示し，「Open in Colab」アイコンをクリックしましょう．
3. もう1名は，ナビゲーターとなってつっこみを入れましょう．
4. このファイルは，Google Drive の，`マイドライブ/Colab Notebooks`に保存されたはずです．そのことを確かめましょう．[Google Drive](https://drive.google.com/drive/u/1/my-drive) の`Colab Notebooks`フォルダを選んでファイルを見ましょう．このファイルは，Google Drive内で移動して整理してもかまいません．
    1. [Gmail](https://mail.google.com/a/mail.ryukoku.ac.jp)で▦アイコンからGoogle Driveを選ぶことでも到達できます．
    2. 作業を途中で中断し，後から再開する場合は，Google Driveの`Colab Notebooks`フォルダから，このNotebookを開きましょう．
5. コードセルを1つずつ実行してみましょう．
6. 最後の方のコードセルに計算式を書いて計算しましょう．
7. 完成したNotebookを `.ipynb` ファイルとしてダウンロードし，チームメンバーと，Teams chatまたはメール添付で共有します．
8. 2名が同一の `.ipynb` ファイルを，Moodleにそれぞれ提出します．

## E00_04
- チーム課題
- 提出 Moodleに`.ipynb` ファイルを提出(2026-09-30水13:30)

1. MoodleのL04_04出題から3変量データのCSVファイルをダウンロードします．
3. [mva_E00_04_Pandas_Regression.ipynb](mva_E00_04_Pandas_Regression.ipynb)を開いて前半を実行します．
4. 3変量ファイルについて同様の分析を，`.ipynb`ファイルの後半で実行します．
   - ダウンロードしたCSVファイルを読み込みます．
   - `width`と`height`の散布図を描きます．
   - 説明変数$x$ を `width` ，目的変数$y$ を`height`，として，回帰係数 $y=\beta_1 x + \beta_0$ の $\beta_0, \beta_1$ を推定しましょう．
推定した回帰係数を，Notebookの先頭に記しましょう．
5. 個人でMoodle に `.ipynb` ファイルを提出します．
