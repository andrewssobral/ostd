Last Page Update: **26/01/2016**

# OSTD
Online Stochastic Tensor Decomposition for Background Subtraction in Multispectral Video Sequences

<p align="center"><img src="https://sites.google.com/site/andrewssobral/ostd_demo.png" /></p>

See also:

* [OSTD SlideShare Presentation](http://pt.slideshare.net/andrewssobral/online-stochastic-tensor-decomposition-for-background-subtraction-in-multispectral-video-sequences) 

* [LRSLibrary: Low-Rank and Sparse Tools for Background Modeling and Subtraction in Videos](https://github.com/andrewssobral/lrslibrary)

Abstract
--------
Background subtraction is an important task for visual surveillance systems. However, this task becomes more complex when the data size grows since the real-world scenario requires larger data to be processed in a more efficient way, and in some cases, in a continuous manner. Until now, most of background subtraction algorithms were designed for mono or trichromatic cameras within the visible spectrum or near infrared part. Recent advances in multispectral imaging technologies give the possibility to record multispectral videos for video surveillance applications. Due to the specific nature of these data, many of the bands within multispectral images are often strongly correlated. In addition, processing multispectral images with hundreds of bands can be computationally burdensome. In order to address these major difficulties of multispectral imaging for video surveillance, this paper propose an online stochastic framework for tensor decomposition of multispectral video sequences (OSTD).

Highlights
----------
* An online stochastic framework for tensor decomposition to deal with multi-dimensional and streaming data.
* And, the use of multispectral video sequences instead of standard mono/trichromatic images, enabling a better background subtraction.

Citation
--------
If you use this code for your publications, please cite it as ([Online Reference](https://www.researchgate.net/publication/282770162_Online_Stochastic_Tensor_Decomposition_for_Background_Subtraction_in_Multispectral_Video_Sequences)):
```
@inproceedings{ostd,
author    = {Sobral, Andrews and Javed, Sajid and Ki Jung, Soon and Bouwmans, Thierry and Zahzah, El-hadi},
title     = {Online Tensor Decomposition for Background Subtraction in Multispectral Video Sequences},
booktitle = {IEEE International Conference on Computer Vision Workshops (ICCVW)},
address   = {Santiago, Chile},
year      = {2015},
month     = {December},
url       = {https://github.com/andrewssobral/ostd}
}
```

Source code
-----------
```
hyperspectral/ - hyperspectral image sequences
hyperspectral/fet.py - foreground evaluation tool in python
STOC-RPCA/ - stochastic RPCA
OSTD.m - proposed algorithm
demo.m - demo file
```

License
-------
The source code is available only for academic/research purposes (non-commercial).

Problems or Questions
---------------------
If you have any problems or questions, please contact the author: Andrews Sobral (andrewssobral@gmail.com)
