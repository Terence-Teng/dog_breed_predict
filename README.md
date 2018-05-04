步骤
克隆存储库并打开下载的文件夹。
git clone https://github.com/udacity/cn-deep-learning.git
cd cn-deep-learning/dog-project
下载狗狗数据集 ，并将数据集解压大存储库中，地点为项目路径/dogImages.

下载人类数据集。并将数据集解压大存储库中，位置为项目路径/lfw。

为狗狗数据集下载 VGG-16关键特征 并将其放置于存储库中，位置为项目路径/bottleneck_features。

安装必要的 Python 依赖包

对于 Mac/OSX：

conda env create -f requirements/dog-mac.yml
source activate dog-project
KERAS_BACKEND=tensorflow python -c "from keras import backend"
对于 Windows：

conda env create -f requirements/dog-windows.yml
activate dog-project
set KERAS_BACKEND=tensorflow
python -c "from keras import backend"
打开 notebook

jupyter notebook dog_app.ipynb
