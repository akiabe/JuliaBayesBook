# JuliaBayesBook

# 「Juliaで作って学ぶベイズ統計学」
本書の第6〜7章のJuliaコードの動作を確認・一部改変し、近似推論の手法、統計モデル、Julia実装について理解する。

## 第6章　勾配を利用した近似推論手法
- ラプラス近似
  - 線形回帰
    - [単一パラメータ](https://github.com/akiabe/JuliaBayesBook/blob/main/src/lr_param_LA.ipynb)
    - [複数パラメータ](https://github.com/akiabe/JuliaBayesBook/blob/main/src/lr_params_LA.ipynb)
  - [ロジスティック回帰](https://github.com/akiabe/JuliaBayesBook/blob/main/src/logistics-regression_laplace.ipynb)
　
- マルコフ連鎖モンテカルロ
  - 線形回帰
    - [メトロポリスヘイスティングス法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/linear-regression_GMH.ipynb)
    - [ハミルトニアンモンテカルロ法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/linear-regression_HMC.ipynb)
  - ロジスティック回帰
    - [メトロポリスヘイスティングス法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/logistic-regression_GMH.ipynb)
    - [ハミルトニアンモンテカルロ法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/logistic-regression_HMC.ipynb)

## 第7章　発展的な統計モデル
- ポアソン回帰
  - [ハミルトニアンモンテカルロ法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/poisson-regression_HMC.ipynb)
- 階層ベイズモデル
  - [ハミルトニアンモンテカルロ法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/hierarchical-bm_HMC.ipynb)
- 状態空間モデル
  - [ハミルトニアンモンテカルロ法](https://github.com/akiabe/JuliaBayesBook/blob/main/src/state-space-model_HMC.ipynb)
