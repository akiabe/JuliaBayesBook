# JuliaBayesBook

# 「Juliaで作って学ぶベイズ統計学」
本書の内容を写経し、理解する。

## 第5章　統計モデリングと推論
- ベルヌーイ分布
- カテゴリ分布
- ポアソン分布
- ガウス分布
- 多次元ガウス分布
- 線形回帰
- ロジスティック回帰

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
