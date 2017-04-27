# MNIST-image-handle
从MNIST数据文件提取为图片
http://yann.lecun.com/exdb/mnist/

MNIST 数据集是一个由 7 万张手写数字灰度图像构成的存储库 [5]。
每张图像的尺寸为 28´28。该数据集基于两个 NIST 数据集，一个由 Census Bureau 的员工收集，另一个由高中生收集。
为了加大数据的差异，最终的 MNIST 集在每个数据集中收集 3 万张图像用于训练，5 千张图像用于测试。

转变为intel深度学习SDK可用的文件存储格式，用于手写识别示例
intel深度学习SDK示例：
https://software.intel.com/zh-cn/articles/case-study-using-the-intel-deep-learning-sdk-for-training-image-recognition-models

MNIST-image.ipynb为jupyter notebook文件
t10k-images.idx3-ubyte，train-images.idx3-ubyte为image文件
t10k-labels.idx1-ubyte，train-labels.idx1-ubyte为lable文件
