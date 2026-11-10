# E07 尤度比に基づくベイズ分類


## E07_01
- 提出不要

[E07_01_multivariate_normal_empirical_data.ipynb](mva_2026_E07_01_multivariate_normal_empirical_data.ipynb)では，
母分布が混合ガウス分布（成分の個数2）であるとわかっていて，かつすべての母数もわかっているとき，条件付き確率$P(Y=1|X=x_{\mathrm test}$ を計算して，ベイズ分類で，$y=0$ か $y=1$ かを判別しています．

## E07_02

- 提出 Moodle
- 締切 2026-11-18水13:00

- $(x_1,x_2,y)$ の個人別データを取得しよう
- [E03_03_multivariate_normal_empirical_data.ipynb](../E03/mva_2026_E03_03_multivariate_normal_empirical_data.ipynb)を参考にして，クラス\(y=0,1\)の2つの母分布の，\(\pi_0,\pi_1\), 毋平均値\(\mathbf{\mu}_0,\mathbf{\mu}_1\)と，毋共分散行列\(\Sigma_0,\Sigma_1\)を推定しよう．
　 - その母数でデータを生成することはしなくてよい
- その母数を使って，[E07_01_multivariate_normal_empirical_data.ipynb](mva_2026_E07_01_multivariate_normal_empirical_data.ipynb)をまねて，$P(Y=1|X=(-1,0))$ を計算し，クラス\(y=0,1\)のどちらに属するかを判定しよう．
　- 1次元正規分布を `stats.norm()` で得ているところを`stats.multivariate_normal()` を使うように書き換える必要がある．
　- 横軸$x$, 縦軸密度のグラフを，等高線または鳥瞰図に変更する必要がある．
- 結果をノートブックの先頭に書こう．

# E07_03
- 提出不要

E07_02 の2ステップ，母数推定と尤度比計算の両方をまとめてやってくれるクラス QuadraticDiscriminantAnalysis が scikit-learn にある．これを使った分析の例が[E07_03](E07_03_QDA.ipynb)にある．

このノートブックを利用して，E07_02 の分析が正しいかどうか（近い結果になるか）確認しよう．