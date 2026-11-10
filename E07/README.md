# E07 尤度比に基づくベイズ分類

## E07_01
- 提出不要

[E07_01_Bayesian_Classification_GMM2.ipynb](mva_2026_E07_01_Bayesian_Classification_GMM2.ipynb)では，
母分布が混合ガウス分布（2次元$x_1,x_2$）（成分の個数2,$y=1,2$）であるとわかっていて，かつすべての母数もわかっているとき，条件付き確率$P(Y=1|X=x_{\mathrm test}$ を計算して，ベイズ分類で，$y=0$ か $y=1$ かを判別しています．

## E07_02

- 提出 Moodle
- 締切 2026-11-18水13:00

- $(X,y)$ の個人別データと，指定の点Xを取得しよう
- 横軸縦軸$x_1,x_2$の散布図を描こう．
  　- 参考：[E06_03_GMM_generate_visualize.ipynb](../E06/mva_2026_E06_03_GMM_generate_visualize.ipynb)
- [E03_03_multivariate_normal_empirical_data.ipynb](../E03/mva_2026_E03_03_multivariate_normal_empirical_data.ipynb)を参考にして，クラス$y=0,1$の2つの母分布の，$\pi_0,\pi_1$, 毋平均値$\mu_0,\mu_1$と，毋共分散行列$\Sigma_0,\Sigma_1$を推定しよう．推定されるのは標準偏差でなく「母共分散行列」であることに注意．
　 - その母数でデータを生成することはしなくてよい
- その母数を使って，[E07_01_Bayesian_Classification_GMM2.ipynb](mva_2026_E07_01_Bayesian_Classification_GMM.ipynb)をまねて，$P(Y=1|X=指定の点)$ を計算し，クラス$y=0,1$のどちらに属するかを判定しよう．
- 結果（母数の推定結果と，y=1に属する確率）をノートブックの先頭に書こう．


## E07_03
- 提出不要

E07_02 の2ステップ，母数推定と尤度比計算の両方をまとめてやってくれるクラス QuadraticDiscriminantAnalysis が scikit-learn にある．これを使った$(x,y)$データの分析の例が[E07_03_QDA.ipynb](mva_2026_E07_03_QDA.ipynb)にある．

このノートブックを利用して，E07_02 の分析が正しいかどうか（近い結果になるか）確認しよう．