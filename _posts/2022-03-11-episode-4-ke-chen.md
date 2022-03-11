---
layout: post
title: "Episode 4 : Zero-shot Audio Source Separation through Query-based
  Learning from Weakly-Labeled Data"
paper_url: https://arxiv.org/abs/2112.07891
paper_arxiv_code: https://arxiv.org/abs/2112.07891
author_name: Ke Chen
author: Ke Chen and Hugo Sonnery
categories: journal
tags:
  - source-separation
  - audio
  - deep-learning
image: /assets/img/episode-4-ke-chen.png
author_picture: /assets/img/ke-chen.jpeg
illustration: /assets/img/untitled.png
youtubeId: ZRwazaD6vkA
personal_website: https://www.knutchen.com/
laboratory_website: http://dub.ucsd.edu/
scholar_profile: https://scholar.google.com/citations?user=Uxjw_PIAAAAJ&hl=en
slides_url: https://www.knutchen.com/
speaker_bio: "I am currently a Ph.D student in Computer Music at UC San Diego. I am fortunate to be co-advised by Prof. Shlomo Dubnov and Prof. Taylor Berg-Kirkpatrick.
My main interest lies in the inter-disciplinary between music and computer science. My research focuses on: Music Generative System and Music Information Retrieval (including singing melody extraction, music source separation, and music recommender system).
I obtained my Bachelor’s degree in Software Engineering at Fudan University, China, co-advised by Prof. Wei Li and Prof. Gus Xia (at NYU Shanghai Music-X-Lab)."
abstract: "Deep learning techniques for separating audio into different sound sources face several challenges. Standard architectures require training separate models for different types of audio sources. Although some universal separators employ a single model to target multiple sources, they have difficulty generalizing to unseen sources. In this paper, we propose a three-component pipeline to train a universal audio source separator from a large, but weakly-labeled dataset: AudioSet. First, we propose a transformer-based sound event detection system for processing weakly-labeled training data. Second, we devise a query-based audio separation model that leverages this data for model training. Third, we design a latent embedding processor to encode queries that specify audio targets for separation, allowing for zero-shot generalization. Our approach uses a single model for source separation of multiple sound types, and relies solely on weakly-labeled data for training. In addition, the proposed audio separator can be used in a zero-shot setting, learning to separate types of audio sources that were never seen in training. To evaluate the separation performance, we test our model on MUSDB18, while training on the disjoint AudioSet. We further verify the zero-shot performance by conducting another experiment on audio source types that are held-out from training. The model achieves comparable Source-to-Distortion Ratio (SDR) performance to current supervised models in both cases."
supplement: \-
---


# About the speaker

**Bio** : {{ page.speaker_bio }}

Do not hesitate to check out [{{ page.author_name }}]({{ page.scholar_profile }}){:target="_blank"}'s personal [website]({{ page.personal_website }}){:target="_blank"} for latest updates !


# Recording


**Video recording** of the speaker's presentation :

{% include youtubeplayer.html id=page.youtubeId %}



# Paper

![{{ page.paper_name }}]({{ site.github.url }}/assets/img/{{ page.illustration }})

**Abstract** : {{ page.abstract }}



# Supplementary material

**Useful resources** : Courtesy of the speaker, the interested reader may find additional information in the *references* below :
* 🧑‍🔬 {{ page.author_name }}'s [personal website]({{ page.personal_website }}){:target="_blank"}
* 🏫 {{ page.author_name }}'s [laboratory_website]({{ page.laboratory_website }}){:target="_blank"}
* 📚 {{ page.author_name }}'s [google scholar profile]({{ page.scholar_profile }}){:target="_blank"}