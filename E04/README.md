# E04

## E04_00
- 提出不要

[訓練データと検証・テストデータへの分割](../doc/説明_訓練データと検証・テストデータへの分割.md) を読んで，訓練データ，検証データ，テストデータの意味を理解しよう．

[E04_00_train_validate_test_split.ipynb](E04_00_train_validate_test_split.ipynb)を実行し，`test_train_split` の使い方，訓練データ，テストデータの分割の方法を確認しよう．

## E04_01　決定係数，自由度調整済み決定係数
- 提出締切: 2026-10-28水13:30
- Moodleに`.ipynb`ファイルをアップロード

[E04_01_R2_score.ipynb](E04_01_R2_score.ipynb)  を理解しよう．

下に追記で，課題E02_02のデータを読み込み，重回帰分析を行い，決定係数と自由度調整済み決定係数を求めよう．求めた値を先頭に書こう．


## E04_02　回帰係数の分布
- 提出不要

w04.pdf によれば，線形重回帰モデル（真の回帰係数${\mathbf{\beta}}$ を固定し，目的変数\(Y\)を確率変数とみなすとき，回帰係数の推定量\(\hat{\beta}\)もまたは確率変数で，多変量正規分布$N(\mathbf{\beta}, \sigma^2 (X^\top X)^{-1})$に従うことが知られている．

[E04_02_distribution_of_regression_coefficients.ipynb](E04_02_distribution_of_regression_coefficients.ipynb) を実行し，
このことを，\(Y\)のサイズが\(n\)の標本を\(m\)回生成し，それぞれの標本に対して重回帰分析を行い，回帰係数の推定量\((\hat{\beta_0},\hat{\beta_1})\)の標本を得て散布図を描くことで確認しよう．
