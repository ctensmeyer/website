+++
draft = false
abstract = "When digitizing a document into an image, it is common to include a surrounding border region to visually indicate that the entire document is present in the image. However, this border should be removed prior to automated processing. In this work, we present a deep learning based system, PageNet, which identifies the main page region in an image in order to segment content from both textual and non-textual border noise. In PageNet, a Fully Convolutional Network obtains a pixel-wise segmentation which is post-processed into the output quadrilateral region. We evaluate PageNet on 4 collections of historical handwritten documents and obtain over 94% mean intersection over union on all datasets and approach human performance on 2 of these collections. Additionally, we show that PageNet can segment documents that are overlayed on top of other documents."
abstract_short = "In this work, we present a deep learning based system, PageNet, which identifies the main page region in an image in order to segment content from both textual and non-textual border noise. In PageNet, a Fully Convolutional Network obtains a pixel-wise segmentation which is post-processed into the output quadrilateral region."
authors = ["Chris Tensmeyer", "Brian Davis", "Curtis Wigington", "Iain Lee", "Bill Barrett"]
date = "2017-09-10"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*4th International Workshop on Historical Document Imaging and Processing*"
publication_short = "*HIP 2017*"
selected = true
title = "PageNet: Page Boundary Extraction in Historical Handwritten Documents"
url_code = "https://github.com/ctensmeyer/pagenet"
url_dataset = "https://scriptnet.iit.demokritos.gr/competitions/5/"
url_pdf = "https://arxiv.org/abs/1709.01618"

[[url_custom]]
name = "Annotations"
url = "https://github.com/ctensmeyer/pagenet"

[[url_custom]]
name = "Docker"
url = "https://hub.docker.com/r/tensmeyerc/icdar2017/tags/"

[[url_custom]]
name = "Slides"
url = "https://drive.google.com/open?id=12hOwhew3HWbBvsaOUTAxpxw6Y8rwDXBq"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "pagenet.png"
caption = "PageNet Post Processing"

+++



