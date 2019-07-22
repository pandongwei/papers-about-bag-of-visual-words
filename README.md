# papers-about-bag-of-visual-words
Some papers and maybe their summery relative to bag of visual words in the last 5 years.

[Paper](#Paper)

- [2019](#2019)
- [2018](#2018)
- [2017](#2017)
- [2016](#2016)
- [2015](#2015)


# Paper

## 2019

* [Approximating CNNs with Bag-of-local-Features models works surprisingly well on ImageNet](https://arxiv.org/abs/1904.00760)<br>

Classification: combination of Neural Network and BOVW<br>

Innovation point: use the main idea of BOVW and apply it in the Neural Network, in order to explain how a DNN works.<br>

创新点：<br> 
DNN可解释性差，用图片划分成32*32的小图片，再放进去DNN中进行分类，得到一个类别向量，一张图片中所有类别向量相加，，得到这张图片的总的类别向量，根据类别向量的最大值进行分类。唯一不同的是，划分之后放进去DNN中分类，用DNN代替了K-means 


## 2018

* [Spatially Enhanced Bags of Visual Words Representation to Improve Traffic Signs Recognition](https://link.springer.com/article/10.1007/s11265-017-1324-9)<br>

Classification: improvement of the BOVW method<br>

Innovation point: In the first step, the region of interest is extracted using a scanning window with a Haar cascade detector and an AdaBoost classifier to reduce the computational region in the hypothesis generation step.  Second, the regions are represented with BoVW and spatial information for classification. Experimental<br>

创新点：<br> 
使用Cascade是为了减少计算量，将特征提取分成多个stages。图像分成一个个窗，每个窗都提取Haar算子，最后，每个stages中同样窗的Haar都显示为object，这个窗中就判定为有object，这个窗就是ROI<br> 

## 2017

* [Bag of Visual Words Model with Deep Spatial Features for Geographical Scene Classification](https://www.hindawi.com/journals/cin/2017/5169675/)<br>

Classification: combination of Neural Network and BOVW<br>

创新点：<br>
在CNN进行场景分类时，在最后一层卷积层之后，得到的三维输出，看做是n张AxB的图，然后对这个输出使用标准的BoVW方法去计算。最后得到的结果，准确度有一些提升

## 2016

## 2015
