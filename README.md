# dog_breed_predict
一个实现基于卷积神经网络的狗品种识别开源项目




### 步骤
1. 下载存储库并打开下载的文件夹。

2. 下载[狗狗数据集](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd101/v4-dataset/dogImages.zip)，将数据集解压大存储库中，地点为项目路径/dogImages.

3. 下载[人类数据集](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd101/v4-dataset/lfw.zip)，并将数据集解压大存储库中，位置为项目路径/lfw。

4. 为狗狗数据集下载 [VGG-16关键特征](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd101/v4-dataset/DogVGG16Data.npz)，并将其放置于存储库中，位置为项目路径/bottleneck_features。

安装必要的 Python 依赖包

###### 对于 Mac/OSX：

`conda env create -f requirements/dog-mac.yml`

`source activate dog-project`

`KERAS_BACKEND=tensorflow python -c "from keras import backend"`

###### 对于 Windows：

`conda env create -f requirements/dog-windows.yml`

`activate dog-project`

`set KERAS_BACKEND=tensorflow`

`python -c "from keras import backend"`

打开 notebook

jupyter notebook dog_app_Open.ipynb
