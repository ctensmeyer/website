+++
draft = false
abstract = "Despite decades of research, offline handwriting recognition (HWR) of degraded historical documents remains a challenging problem, which if solved could greatly improve the searchability of online cultural heritage archives.  HWR models are often limited by the accuracy of the preceding steps of text detection and segmentation.  Motivated by this, we present a deep learning model that jointly learns text detection, segmentation, and recognition using mostly images without detection or segmentation annotations.  Our Start, Follow, Read (SFR) model is composed of a Region Proposal Network to find the start position of text lines, a novel line follower network that incrementally follows and preprocesses lines of (perhaps curved) text into dewarped images suitable for recognition by a CNN-LSTM network.  SFR exceeds the performance of the winner of the ICDAR2017 handwriting recognition competition, even when not using the provided competition region annotations."
abstract_short = "We present a deep learning model that jointly learns text detection, segmentation, and recognition using mostly images without detection or segmentation annotations.  Our Start, Follow, Read (SFR) model is composed of a Region Proposal Network to find the start position of text lines, a novel line follower network that incrementally follows and preprocesses lines of (perhaps curved) text into dewarped images suitable for recognition by a CNN-LSTM network.  SFR achieves state-of-the-art results on ICDAR2017 handwriting recognition competition dataset, even without using the provided region annotations."
authors = ["Curtis Wigington", "Chris Tensmeyer", "Brian Davis", "Bill Barrett", "Brian Price", "Scott Cohen"]
date = "2018-09-08"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*European Conference on Computer Vision (ECCV)"
publication_short = "*ECCV 2018*"
selected = true
title = "Start, Follow, Read: End-to-End Full Page Handwriting Recognition"
#url_code = "https://github.com/ctensmeyer/pagenet"
#url_dataset = "http://www.fki.inf.unibe.ch/databases/iam-handwriting-database"
#url_pdf = "https://drive.google.com/file/d/1yB-ioG7mBtF8nbdpbYNRmRGMf6xtRuPF/view?usp=sharing"

[[url_custom]]
name = "ICDAR 2017 Dataset"
url = "https://scriptnet.iit.demokritos.gr/competitions/~icdar2017htr/"

[[url_custom]]
name = "ICDAR 2016 Dataset"
url = "https://scriptnet.iit.demokritos.gr/competitions/4/"

[[url_custom]]
name = "IAM Dataset"
url = "http://www.fki.inf.unibe.ch/databases/iam-handwriting-database"

[[url_custom]]
name = "Rimes Dataset"
url = "http://www.a2ialab.com/doku.php?id=rimes_database:start"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "line_follower.png"
caption = "Line Follower Network"

+++



