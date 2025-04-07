---
title: Neighboring Autoregressive Modeling for Efficient Visual Generation
authors:
- Yefei He
- Yuanyu He
- Shaoxuan He
- Feng Chen
- Hong Zhou
- Kaipeng Zhang
- Bohan Zhuang
date: '2025-03-01'
publishDate: '2025-04-07T10:32:04.916010Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2503.10696*'

abstract: In this paper, we propose Neighboring Autoregressive Modeling (NAR), a novel paradigm that formulates autoregressive visual generation as a progressive outpainting procedure, following a near-to-far "next-neighbor prediction" mechanism. Starting from an initial token, the remaining tokens are decoded in ascending order of their Manhattan distance from the initial token in the spatial-temporal space, progressively expanding the boundary of the decoded region. To enable parallel prediction of multiple adjacent tokens in the spatial-temporal space, we introduce a set of dimension-oriented decoding heads, each predicting the next token along a mutually orthogonal dimension. During inference, all tokens adjacent to the decoded tokens are processed in parallel, substantially reducing the model forward steps for generation. Experiments on ImageNet 256 x 256 and UCF101 demonstrate that NAR achieves 2.4x and 8.6x higher throughput respectively, while obtaining superior FID/FVD scores for both image and video generation tasks compared to the PAR-4X approach. When evaluating on text-to-image generation benchmark GenEval, NAR with 0.8B parameters outperforms Chameleon-7B while using merely 0.4% of the training data.

url_pdf: https://arxiv.org/pdf/2503.10696
url_code: https://github.com/ThisisBillhe/NAR
url_dataset: ''
url_poster: ''
url_project: https://yuanyu0.github.io/nar/
url_slides: ''
url_source: ''
url_video: https://youtu.be/pnHADYVLuO4
---
