## About
This repository holds the 2nd release of the data for the EMNLP 2019 paper "In Plain Sight: Media Bias Through the Lens of Factual Reporting". The first release can be found [here](https://github.com/marshallwhiteorg/emnlp19-media-bias).

## Paper Link
[In Plain Sight: Media Bias Through the Lens of Factual Reporting](https://arxiv.org/abs/1909.02670)

## Contents
- articles/: original news articles
- annotations/: gold-standard annotations
- dataset.zip: a version of the dataset that combines articles and their gold-standard annotations for easy processing


## Annotation Updates
We made the following changes to correct potentially mislabled annotations in the first release of BASIL data. The new annotations in this release are consistent with the [original annotation protocol](https://github.com/marshallwhiteorg/emnlp19-media-bias/blob/master/annotation-protocol.pdf). A complete list of detailed changes can be found [here](annotation_changes.txt).

| Type | Count |
|-------|---------|
| Bias type (lexical v.s. informational) fix | 2 |
| Speaker of quote fix | 9 |
| Polarity fix | 8 |



Other minor changes are:
- We include quotation marks when the biased sentence is marked as a quote (if applicable).
- We remove duplicated annotations (possibly due to file saving errors).
- We fix inconsistencies between start/end indices and texts.
