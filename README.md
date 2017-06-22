
[![Analytics](https://ga-beacon.appspot.com/UA-80121379-2/notes-python)](https://github.com/lijin-thu/notes-python)

# 机器学习库学习笔记

> 版本：0.0.1<br>
> 作者：ethanw<br>
> 邮件：ethan_w@aliyun.com<br>

感谢lijin-THU的[中文python笔记](https://github.com/lijin-THU/notes-python/blob/master/README.md)，在这上面学习了Numpy、Scipy、Matplotlib、Pandas等基本库。

接下来打算学习scikit-learn、TensorFlow、keras、nltk等库，计划写成笔记。

注意：`Github` 加载 `.ipynb` 的速度较慢，建议在 [Nbviewer](http://nbviewer.jupyter.org/github/ethanww/machine-learning-tools/tree/master/index.ipynb) 中查看该项目。

---

## 简介

默认安装了 `Python 3.5`，以及相关的第三方包 `ipython`， `numpy`， `scipy`，`pandas`。

> life is short. use python.

推荐使用 [Anaconda](http://www.continuum.io/downloads)，这个IDE集成了大部分常用的包。

笔记内容使用 `jupyter notebook` 来展示。

安装好 `Python` 和相应的包之后，可以在命令行下输入：

```
$ jupyter notebook
```
来进入 `jupyter notebook`。

----

## 基本环境配置

- 安装 [Anaconda](http://www.continuum.io/downloads) 或者 [Miniconda](http://conda.pydata.org/miniconda.html)

- 更新环境
``` 
conda update conda
conda update anaconda
```

---

## 参考

- [中文python笔记](https://github.com/lijin-THU/notes-python/blob/master/README.md)
- [scikit-learn Tutorials](http://scikit-learn.org/stable/tutorial/)

----

## 目录

可以在 Notebook 中打开 `generate static files.ipynb`，或者命令行中运行代码 `generate_static_files.py` 来生成静态的 HTML 文件。

---

- [01. **scikit-learn**](01-scikit-learn)
	 - [01.01 数据集和估计器](01-scikit-learn/01.01-数据集和估计器.ipynb)
	 - [01.02 监督学习：预测数据集的输出](01-scikit-learn/01.02-监督学习：预测数据集的输出.ipynb)
	 - [01.03 选择合适的估计器和参数](01-scikit-learn/01.03-选择合适的估计器和参数.ipynb)
	 - [01.04 非监督学习：寻找数据的表现形式](01-scikit-learn/01.04-非监督学习：寻找数据的表现形式.ipynb)​
	 - [01.05 结合算法](01-scikit-learn/01.05-结合算法.ipynb)
	 - [01.06 选择正确的估计器](01-scikit-learn/01.06-选择正确的估计器.ipynb)

觉得有用打赏一下？

<img src="http://onkpm5zlx.bkt.clouddn.com/wechatpay6.jpg" width="300px" />