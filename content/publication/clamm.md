+++
draft = false
abstract = "Classifying pages or text lines into font categories aids transcription because single font Optical Character Recognition (OCR) is generally more accurate than omni-font OCR.  We present a simple framework based on Convolutional Neural Networks (CNNs), where a CNN is trained to classify small patches of text into predefined font classes. To classify page or line images, we average the CNN predictions over densely extracted patches. We show that this method achieves state- of-the-art performance on a challenging dataset of 40 Arabic computer fonts with 98.8% line level accuracy. This same method also achieves the highest reported accuracy of 86.6% in predicting paleographic scribal script classes at the page level on medieval Latin manuscripts. Finally, we analyze what features are learned by the CNN on Latin manuscripts and find evidence that the CNN is learning both the defining morphological differences between scribal script classes as well as overfitting to class-correlated nuisance factors. We propose a novel form of data augmentation that improves robustness to text darkness, further increasing classification performance."
abstract_short = "Classifying pages or text lines into font categories aids transcription because single font Optical Character Recognition (OCR) is generally more accurate than omni-font OCR.  We present a simple framework based on Convolutional Neural Networks (CNNs), where a CNN is trained to classify small patches of text into predefined font classes."
authors = ["Chris Tensmeyer", "Daniel Saunders", "Tony Martinez"]
date = "2017-08-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*International Conference on Document Analysis and Recognition (ICDAR)*, IEEE."
publication_short = "*ICDAR 2017*"
selected = true
title = "Convolutional Neural Networks for Font Classification"
url_code = "https://github.com/ctensmeyer/font_classification"
#url_dataset = "http://clamm.irht.cnrs.fr/"
url_pdf = "https://arxiv.org/abs/1708.03669"

[[url_custom]]
name = "CLaMM Dataset"
url = "http://clamm.irht.cnrs.fr/"

[[url_custom]]
name = "KAFD Dataset"
url = "http://kafd.ideas2serve.net/"

[[url_custom]]
name = "Annotations"
url = "http://axon.cs.byu.edu/clamm/"

[[url_custom]]
name = "Docker"
url = "https://hub.docker.com/r/tensmeyerc/icdar2017/tags/"

[[url_custom]]
name = "Slides"
url = "https://drive.google.com/open?id=1GdHMeW7hVYEBVZDd9rif9YKiQ4LK_nm1"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "font_pic.png"
caption = "Arabic Fonts and Scribal Scripts"

+++

Models and code (with corresponding docker image instructions) for this paper can be found in this [github repo](https://github.com/ctensmeyer/font_classification).  The pixel annotations I created for one set of experiments can be found [here](http://axon.cs.byu.edu/clamm/).

I submitted this method to the [2016](http://clamm.irht.cnrs.fr/icfhr-2016/) and [2017](http://clamm.irht.cnrs.fr/icdar-2017/) Competitions on Classification of Latin Medieval Manuscripts (CLaMM).  Here is the code for my [2016](https://github.com/ctensmeyer/clamm_submission) and [2017](https://github.com/ctensmeyer/clamm_2017) submissions.

In the 2016 competition, I placed 2nd in Task 1 and 3rd in Task 2 [(Results Table)](http://clamm.irht.cnrs.fr/icfhr-2016/results/).  2017 results have yet to be announced.


