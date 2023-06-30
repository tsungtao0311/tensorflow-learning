# tensorflow-learning
notebook for the tensorflow self-learning

here is the reference:   https://github.com/tsungtao0311/tensorflow-learning/wiki  

-----------------------------------------------------------------------------------------------------------------------------------------------------------
关于anaconda中用Conda和Pip安装相同软件的问题，建议统一用conda去装，如果必须用Pip， 那么先conda remove, 再pip uninstall, 把虚拟环境的软件先清理一下，之后再用pip直接装就好。
用pip装的软件包也会出现再anaconda的虚拟环境路径下（anaconda navigator刷新后也能看到，conda list 也能看到）：

(tf_learning) C:\Users\Administrator>pip install tensorflow==2.12.0
(tf_learning) C:\Users\Administrator>pip show tensoflow
WARNING: Package(s) not found: tensoflow

(tf_learning) C:\Users\Administrator>
(tf_learning) C:\Users\Administrator>pip show tensorflow
Name: tensorflow
Version: 2.12.0
Summary: TensorFlow is an open source machine learning framework for everyone.
Home-page: https://www.tensorflow.org/
Author: Google Inc.
Author-email: packages@tensorflow.org
License: Apache 2.0
Location: c:\users\administrator\anaconda3\envs\tf_learning\lib\site-packages
Requires: tensorflow-intel
Required-by:

-----------------------------------------------------------------------------------------------------------------------------------------------------------  

宇宙是几维的，不同的视角所定义的维度也是不同的。 可以说宇宙是三维的，也可以是高纬的。就像相对论一样，要区分广义和狭义。  
描述地球上一个物体的位置，可以用经纬度加海拔三维坐标，但它是以地球本身为参考系的一个粗略的维度定位坐标而已。如果加上地球在太阳系的描述坐标以后，那么地球上的所有物体的坐标就会高于三维。  
所以狭义上是三维空间，广义上我们的世界本身就是非常高维的，而且是非常稀疏的。
