Python learning
========

Here are the notes of self-learning Python. 

（基于Windows系统）

起因是完成模式识别作业，用RNN模型完成image caption；于是乎，有了后面这些事儿


1. 安装：Anaconda, python3.5

常用命令：

conda --version   查看当前conda版本

conda update conda   更新 conda

conda list 查看哪些程序已经安装了

pip install --upgrade matplotlib 安装新程序

注意：在安装TensorFlow的过程中，出现于Python版本不兼容的情况，尽管本地安装的是Python3.5；如下处理可解决

conda create -n tensorflowproject python=3.5 tensorflow ipython

activate tensorflowproject

pip install --upgrade tensorflow

现在，就可以测试了：https://github.com/martin-gorner/tensorflow-mnist-tutorial/blob/master/INSTALL.txt


2. Jupyter notebook （.ipynb文件）

进入notebook网页界面： CMD输入 jupyter notebook

退出notebook：网页上 logout， CMD键入 Ctrl + C


3. Python3 数据处理入门 https://www.gitbook.com/book/bxtkezhan/data_processing_beginner_with_python3/details
