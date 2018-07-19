+++
draft = false
abstract = "Convolutional Neural Networks (CNNs) are state-of-the-art models for document image classification tasks.  However, many of these approaches rely on parameters and architectures designed for classifying natural images, which differ from document images. We question whether this is appropriate and conduct a large empirical study to find what aspects of CNNs most affect performance on document images.  Among other results, we exceed the state-of-the-art on the RVL- CDIP dataset by using shear transform data augmentation and an architecture designed for a larger input image. Additionally, we analyze the learned features and find evidence that CNNs trained on RVL-CDIP learn region-specific layout features."
abstract_short = "Convolutional Neural Networks (CNNs) are state- of-the-art models for document image classification tasks.  However, many of these approaches rely on parameters and architectures designed for classifying natural images, which differ from document images. We question whether this is appropriate and conduct a large empirical study to find what aspects of CNNs most affect performance on document images."
authors = ["Chris Tensmeyer", "Tony Martinez"]
date = "2017-08-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*International Conference on Document Analysis and Recognition (ICDAR)*, IEEE."
publication_short = "*ICDAR 2017*"
selected = true
title = "Analysis of Convolutional Neural Networks for Document Image Classification"
url_code = "https://github.com/ctensmeyer/caffe"
url_dataset = "http://scs.ryerson.ca/~aharley/rvl-cdip/"
url_pdf = "https://arxiv.org/abs/1708.03273"

[[url_custom]]
name = "Poster"
url = "https://drive.google.com/open?id=1oPdjEfc4ORN4pvfavXA-t3S-5H4AfvhB"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "cnn_filters.png"
caption = "Region Specific CNN filters appear when trained to discriminate document layout types"

+++

