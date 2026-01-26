---
title: 'Wan-Move: Motion-controllable Video Generation via Latent Trajectory Guidance'
authors:
- Ruihang Chu*
- Yefei He*
- Zhekai Chen*
- Shiwei Zhang
- Xiaogang Xu
- Bin Xia
- Dingdong Wang
- Hongwei Yi
- Xihui Liu
- Hengshuang Zhao
- ' others'
date: '2025-04-01'
publishDate: '2026-01-26T08:09:14.295688Z'
publication_types:
- article-journal
publication: '**NeurIPS 2025**'

abstract: We present Wan-Move, a simple and scalable framework that brings motion control to video generative models. Existing motion-controllable methods typically suffer from coarse control granularity and limited scalability, leaving their outputs insufficient for practical use. We narrow this gap by achieving precise and high-quality motion control. Our core idea is to directly make the original condition features motion-aware for guiding video synthesis. To this end, we first represent object motions with dense point trajectories, allowing fine-grained control over the scene. We then project these trajectories into latent space and propagate the first frame's features along each trajectory, producing an aligned spatiotemporal feature map that tells how each scene element should move. This feature map serves as the updated latent condition, which is naturally integrated into the off-the-shelf image-to-video model, e.g., Wan-I2V-14B, as motion guidance without any architecture change. It removes the need for auxiliary motion encoders and makes fine-tuning base models easily scalable. Through scaled training, Wan-Move generates 5-second, 480p videos whose motion controllability rivals Kling 1.5 Pro's commercial Motion Brush, as indicated by user studies. To support comprehensive evaluation, we further design MoveBench, a rigorously curated benchmark featuring diverse content categories and hybrid-verified annotations. It is distinguished by larger data volume, longer video durations, and high-quality motion annotations. Extensive experiments on MoveBench and the public dataset consistently show Wan-Move's superior motion quality. Code, models, and benchmark data are made publicly available.

url_pdf: https://arxiv.org/pdf/2512.08765
url_code: https://github.com/ali-vilab/Wan-Move
url_dataset: ''
url_poster: ''
url_project: https://wan-move.github.io/
url_slides: ''
url_source: ''
url_video: https://www.youtube.com/watch?v=_5Cy7Z2NQJQ
---
