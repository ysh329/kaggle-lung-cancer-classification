# 基于肺部CT扫描图像的医学图像分类

这个项目来自[Kaggle-DSB2017比赛](https://www.kaggle.com/c/data-science-bowl-2017/)，该比赛是要解决肺部CT扫描图像分类的问题。

这里给出我在实现该问题时候的Jupyter Notebook，得到了最后的结果，提交上去最好的loss结果是0.55左右。当然超参数还有进一步的优化空间。具体的做法在ipnb里写的很清楚。

方法主要来自社区(mxnet+xgboost,mxnet+xgboost-v2,说白了就是resnet+bagged)，并基于社区的方法做了一些预处理上的修改(preprocessing+mxnet+xgboost)。还有一些方法没有尝试或者走了一半，比方3D-CNN或者其他的视频分类方法。