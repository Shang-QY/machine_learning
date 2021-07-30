## README

- *机器学习调参记录.md* 文件是我们的调参记录。 

- Code 目录包含了我们的模型代码，一共有四个文件，分别是：
  - *SE125Proj2_baseline.ipynb*：是调参后最优的代码
  - *SE125Proj2_attention.ipynb*：是我们视频中提到的 *attention decoder* 模型（即将baseline decoder换成attention）
  - *SE125Proj2_transformerEncoder.ipynb*：视频中提到的 *transformer encoder* 模型（即将baseline encoder换成 transformer的 encoder）
  - *SE125Proj2_transformer_attention _final.ipynb*：项目最终的模型，使用了*transformer encoder + attention decoder*

- *checkpoint_iter0.pkl* 是我们最终模型对应的checkpoint文件