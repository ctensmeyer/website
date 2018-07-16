+++
draft = true
abstract = "Training state-of-the-art offline handwriting recognition (HWR) models requires large labeled datasets, but unfortunately such datasets are not available in all languages and domains due to the high cost of manual labeling.  We address this problem by showing how high resource languages can be leveraged to help train models for low resource languages.  We propose a transfer learning methodology where we adapt HWR models trained on a source language to a target language that uses the same writing script.  This methodology only requires labeled data in the source language, unlabeled data in the target language, and a language model of the target language.  The language model is used in a bootstrapping fashion to refine predictions in the target language for use as ground truth in training the model.  Using this approach we demonstrate improved transferability among French, English, and Spanish languages using both historical and modern handwriting datasets.  In the best case, transferring with the proposed methodology results in character error rates nearly as good as full supervised training."
abstract_short = "We address the problem of training handwriting recognition (HWR) models for low resource languages by leveraging data from high resource languages with similar scripts through transfer learning. A langauge model in the target language is used to refine a model trained on a source language.  Using this approach we demonstrate improved transferability among French, English, and Spanish languages using both historical and modern handwriting datasets."
authors = ["Chris Tensmeyer", "Curtis Wigington", "Brian Davis", "Seth Stewart", "Tony Martinez", "Bill Barrett"]
date = "2018-08-08"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*4th International Workshop on Historical Document Imaging and Processing*"
publication_short = "*HIP*"
selected = true
title = "Language Model Supervision for Handwriting Recognition Model Adaptation"
#url_code = "https://github.com/ctensmeyer/pagenet"
#url_dataset = "https://scriptnet.iit.demokritos.gr/competitions/5/"
url_pdf = "https://arxiv.org/abs/1709.01618"

[[url_custom]]
name = "Annotations"
url = "https://github.com/ctensmeyer/pagenet"

[[url_custom]]
name = "Docker"
url = "https://hub.docker.com/r/tensmeyerc/icdar2017/tags/"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "pagenet.png"
caption = "PageNet Post Processing"

+++



