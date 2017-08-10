+++
draft = false
abstract = "Identifying the type of a scanned form greatly facilitates processing, including automated field segmentation and field recognition. Contrary to the majority of existing techniques, we focus on unsupervised type identification, where the set of form types are not known apriori, and on noisy collections that contain very similar document types. This work presents a novel algorithm: CONFIRM (Clustering Of Noisy Form Images using Robust Matching), which simultaneously discovers the types in a collection of forms and assigns each form to a type. CONFIRM matches type-set text and rule lines between forms to create domain specific features, which we show outperform Bag of Visual Word (BoVW) features employed by the current state-of-the-art. To scale to large document collections, we use a bootstrap approach to clustering, where only a small subset of the data is clustered directly, while the rest of the data is assigned to clusters in linear time. We show that CONFIRM reduces average cluster impurity by 44% compared to the state-of-the art on 5 collections of historical forms that contain significant noise. We also show competitive performance on the relatively clean NIST tax form collection."
abstract_short = "Identifying the type of a scanned form greatly facilitates processing, including automated field segmentation and field recognition. Contrary to the majority of existing techniques, we focus on unsupervised type identification, where the set of form types are not known apriori, and on noisy collections that contain very similar document types. This work presents a novel algorithm: CONFIRM (Clustering Of Noisy Form Images using Robust Matching), which simultaneously discovers the types in a collection of forms and assigns each form to a type. CONFIRM matches type-set text and rule lines between forms to create domain specific features, which we show outperform Bag of Visual Word (BoVW) features employed by the current state-of-the-art."
authors = ["Chris Tensmeyer"]
date = "2016-05-01"
image_preview = ""
math = true
publication_types = ["4"]
publication = "Master's Thesis"
publication_short = "MS Thesis"
selected = true
title = "CONFIRM: Clustering of Noisy Form Images Using Robust Matching"
url_code = "https://github.com/ctensmeyer/formCluster"
url_dataset = "https://www.nist.gov/srd/nist-special-database-2"
url_pdf = "http://scholarsarchive.byu.edu/cgi/viewcontent.cgi?article=7054&context=etd"
#url_slides = "#"

[[url_custom]]
name = "Dataset2"
url = "https://www.nist.gov/srd/nist-special-database-6"
# Optional featured image (relative to `static/img/` folder).
[header]
image = "form.jpg"
caption = ""

+++

Currently in submission to a regular journal.
