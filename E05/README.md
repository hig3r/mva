# E05　多項式回帰と変数選択

## E05_01　多項式回帰
- 提出締切: 2026-11-04水13:30
- Moodleに`.ipynb`ファイルをアップロード

- [mva_2026_E05_01_dummy_polynomial_variables.ipynb](https://github.com/hig3r/mva/blob/2026/E05/mva_2026_E05_01_dummy_polynomial_variables.ipynb)の例を参考にして，個人別にMoodleで与えられたデータを分析しよう．
- 線形重回帰モデルに，項$x_1^2$ を導入して，説明変数の多項式回帰モデルを作成し，それぞれ自由度調整済み決定係数を求めよう．

次はやらなくてよい（カテゴリ変数がないから）
- 線形重回帰モデルに，ダミー変数を導入して，説明変数の多項式回帰モデルを作成し，それぞれ自由度調整済み決定係数を求めよう．

## E05_02　変数選択，モデル選択
- 提出締切: 2026-11-04水13:30
- Moodleに`.ipynb`ファイルをアップロード
- Moodleに結果を解答

[mva_2026_E05_02_variable_selection.ipynb](https://github.com/hig3r/mva/blob/2026/E05/mva_2026_E05_02_variable_selection.ipynb)を参考にして，個人別にMoodleで与えられたデータに対して，説明変数を次として（重）回帰分析を行い，それぞれ自由度調整済み決定係数を求めよう．

- $x_1$
- $x_2$
- $x_3$
- $x_1, x_2$
- $x_1, x_3$
- $x_2, x_3$
- $x_1, x_2, x_3$

## E05_03　多重共線性の観察
- 提出: なし

[E05_03_multicolinearity.ipynb](mva_2026_E05_03_multicolinearity.ipynb) を実行し，多重共線性があると，回帰係数の推定値が不正確になることを確認しよう．
