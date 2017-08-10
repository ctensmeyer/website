+++
draft = false
abstract = "Classifying pages or text lines into font categories aids transcription because single font Optical Character Recognition (OCR) is generally more accurate than omni-font OCR.  We present a simple framework based on Convolutional Neural Networks (CNNs), where a CNN is trained to classify small patches of text into predefined font classes. To classify page or line images, we average the CNN predictions over densely extracted patches. We show that this method achieves state- of-the-art performance on a challenging dataset of 40 Arabic computer fonts with 98.8% line level accuracy. This same method also achieves the highest reported accuracy of 86.6% in predicting paleographic scribal script classes at the page level on medieval Latin manuscripts. Finally, we analyze what features are learned by the CNN on Latin manuscripts and find evidence that the CNN is learning both the defining morphological differences between scribal script classes as well as overfitting to class-correlated nuisance factors. We propose a novel form of data augmentation that improves robustness to text darkness, further increasing classification performance."
abstract_short = "Classifying pages or text lines into font categories aids transcription because single font Optical Character Recognition (OCR) is generally more accurate than omni-font OCR.  We present a simple framework based on Convolutional Neural Networks (CNNs), where a CNN is trained to classify small patches of text into predefined font classes."
authors = ["Chris Tensmeyer", "Daniel Saunders", "Tony Martinez"]
date = "2017-08-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*International Conference on Document Analysis and Recognition (ICDAR)*, IEEE. (To Appear)"
publication_short = "*ICDAR* (To Appear)"
selected = true
title = "Convolutional Neural Networks for Font Classification"
url_code = "https://github.com/ctensmeyer/clamm_2017"
url_dataset = "http://axon.cs.byu.edu/clamm/"
#url_pdf = "#"

[[url_custom]]
name = "Dataset2"
url = "http://kafd.ideas2serve.net/"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "clamm.png"
caption = "Some non-textual content can be used to classify fonts in Latin Manuscripts."

+++

