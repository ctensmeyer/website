+++
draft = false
abstract = "Binarization of degraded historical manuscript images is an important pre-processing step for many document processing tasks. We formulate binarization as a pixel classification learning task and apply a novel Fully Convolutional Network (FCN) architecture that operates at multiple image scales, including full resolution. The FCN is trained to optimize a continuous version of the Pseudo F-measure metric and an ensemble of FCNs outperform the competition winners on 4 of 7 DIBCO competitions. This same binarization technique can also be applied to different domains such as Palm Leaf Manuscripts with good performance. We analyze the performance of the proposed model w.r.t. the architectural hyperparameters, size and diversity of training data, and the input features chosen."
abstract_short = "Binarization of degraded historical manuscript images is an important pre-processing step for many document processing tasks. We formulate binarization as a pixel classification learning task and apply a novel Fully Convolutional Network (FCN) architecture that operates at multiple image scales, including full resolution. The FCN is trained to optimize a continuous version of the Pseudo F-measure metric and an ensemble of FCNs outperform the competition winners on 4 of 7 DIBCO competitions."
authors = ["Chris Tensmeyer", "Tony Martinez"]
date = "2017-08-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*International Conference on Document Analysis and Recognition (ICDAR)*, IEEE."
publication_short = "*ICDAR 2017*"
selected = true
title = "Document Image Binarization with Fully Convolutional Neural Networks"
url_code = "https://github.com/ctensmeyer/binarization_2017"
url_dataset = "https://vc.ee.duth.gr/dibco2017/"
url_pdf = "https://arxiv.org/abs/1708.03276"
#url_project = "project/deep-learning/"
#url_slides = "#"
#url_video = "#"

[[url_custom]]
name = "Dataset2"
url = "http://amadi.univ-lr.fr/ICFHR2016_Contest/index.php/challenge-1" 

[[url_custom]]
name = "Code2"
url = "https://github.com/ctensmeyer/dibco_2017"

[[url_custom]]
name = "Docker"
url = "https://hub.docker.com/r/tensmeyerc/icdar2017/tags/"

[[url_custom]]
name = "Slides"
url = "https://drive.google.com/open?id=1MY4TA09bx1y13IlrB7Ksrr6MZWjgWe1h"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "Binarization_Network_Arch.png"
caption = "Multi-scale network architecture"

+++

I submitted this binarization algorithm to the 2017 Document Image Binarization Contest (DIBCO 2017) and have made the code and model files for evaluating the network available on [github](https://github.com/ctensmeyer/dibco_2017). This repo has two versions.  One uses a densely connected CRF for post-processing, which improves results a little bit.  The other version uses only the network output.  

The exact models used in this paper are available in a separate [repo](https://github.com/ctensmeyer/binarization_2017) and have an associated [docker image](https://hub.docker.com/r/tensmeyerc/icdar2017/).  These include both models trained on DIBCO 2009-2014 and on the Palm Leaf Manuscripts.  The models I submitted to DIBCO 2017 were trained on DIBCO 2009-2016. 

An earlier version of this algorithm placed first in the binarization task of the [2016 Competition on the Analysis of Handwritten Text in Images of Balinese Palm Leaf Manuscripts](http://amadi.univ-lr.fr/ICFHR2016_Contest/index.php/challenge-1).  

For training the network, I used my [fork](https://github.com/ctensmeyer/caffe) of the popular deep learning library [Caffe](http://caffe.berkeleyvision.org/).  In my fork, you can find my implementation of the loss function presented in this paper in /src/caffe/layers/weighted_fmeasure_loss_layer.cpp (.cu GPU implementation too).
