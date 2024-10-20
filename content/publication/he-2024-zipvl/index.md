---
title: 'ZipVL: Efficient Large Vision-Language Models with Dynamic Token Sparsification
  and KV Cache Compression'
authors:
- Yefei He
- Feng Chen
- Jing Liu
- Wenqi Shao
- Hong Zhou
- Kaipeng Zhang
- Bohan Zhuang
date: '2024-10-01'
publishDate: '2024-10-12T03:09:02.404724Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2410.08584*'

abstract: In this paper, we present ZipVL, an efficient inference framework designed for LVLMs that resolves both computation and memory bottlenecks through a dynamic ratio allocation strategy of important tokens. This ratio is adaptively determined based on the layer-specific distribution of attention scores, rather than fixed hyper-parameters, thereby improving efficiency for less complex tasks while maintaining high performance for more challenging ones. Then we select important tokens based on their normalized attention scores and perform attention mechanism solely on those important tokens to accelerate the prefill phase. To mitigate the memory bottleneck in the decoding phase, we employ mixed-precision quantization to the KV cache, where high-bit quantization is used for caches of important tokens, while low-bit quantization is applied to those of less importance. Our experiments demonstrate that ZipVL can accelerate the prefill phase by 2.6× and reduce GPU memory usage by 50.0%, with a minimal accuracy reduction of only 0.2% on Video-MME benchmark over LongVA-7B model, effectively enhancing the generation efficiency of LVLMs.

url_pdf: https://arxiv.org/pdf/2410.08584
url_code: ''
url_dataset: ''
url_poster: ''
url_project: https://hexy.tech/zipvl/
url_slides: ''
url_source: ''
url_video: ''
---
