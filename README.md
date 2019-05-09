# Image-SuperResolution-and-Quality-Ehancement-Benchmark
A collection of Image SuperResolution and Quality Ehancement Benchmark


## Image Super Resolution:

### Traditional Methods
- [RAISR: Rapid and Accurate Image Super Resolution](https://arxiv.org/abs/1606.01299) 2016, RAISR, Google， 利用三个key值进行hash，速度很快


### CNN METHODS
- [Fast, Accurate, and Lightweight Super-Resolution with Cascading Residual Network](https://arxiv.org/abs/1803.08664), ECCV 2018, 高效超分网络，CARN，其中CARN-M的计算量比SRCNN的还小，并采用recursive learning机制
- [Zoom to Learn, Learn to Zoom](https://arxiv.org/abs/1803.06641), CVPR2018, qifeng chen组, 本文两个insight,一个是采用单反的raw data,另一个是coBi Loss.文中还提出如何去人工合成Raw Data.[[code]](https://github.com/Artifineuro/zole)
- [Deep Learning for Image Super-resolution: A Survey](https://arxiv.org/pdf/1902.06068.pdf), 2019,关于DL for SR的综述文章
- [Meta-SR: A Magnification-Arbitrary Network for Super-Resolution](https://arxiv.org/abs/1903.00875), CVPR 2019， face++, 针对LR input提供了任意尺度的超分模型
- [Toward Real-World Single Image Super-Resolution:A New Benchmark and A New Model](https://arxiv.org/abs/1904.00523), CVPR 2019, 提出了一种新的真实高分辨率数据集(未公开)，文中有数据集制作及配准算法，以及本文的Lp-kpn模型
- [Feedback Network for Image Super-Resolution](https://arxiv.org/abs/1903.09814),CVPR 2019, 类似DRCN与DRRN的基于RNN的反馈超分网络
- [Deep network interpolation for continuous imagery effect transition](https://arxiv.org/abs/1811.10515), CVPR 2019, 对两个强相关的深度网络的参数插值，简单且有效



## Video Super Resolution:
- [Real-Time Video Super-Resolution with Spatio-Temporal Networks and Motion Compensation](http://openaccess.thecvf.com/content_cvpr_2017/papers/Caballero_Real-Time_Video_Super-Resolution_CVPR_2017_paper.pdf) CVPR2016， Twitter组， 多帧视频超分辨率


## Image/Video Quality Enhancement:
- [decoder-side HEVC quality enhancement with scalable convolutional neural network](http://buaamc2.net/pdf/ICME2017DecoderSide.pdf), ICME, 2017,同时处理I帧及BP帧
- [Enhancing Quality for HEVC Compressed Videos](https://arxiv.org/abs/1709.06734), 2017，同时处理I帧及BP帧,上文的期刊版
- [Deep Joint Demosaicking and Denoising](https://groups.csail.mit.edu/graphics/demosaicnet/data/demosaic.pdf), TOG 2017， DeepJoint, 经典的demosaic文章, 并提出了制作Raw Data的方法
