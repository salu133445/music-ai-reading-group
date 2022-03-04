---
layout: post
title: "Episode 2 : Music demixing with the sliCQ Transform"
paper_name: "Music demixing with the sliCQ transform"
paper_url: "https://arxiv.org/abs/2112.05509"
paper_arxiv_code: "arXiv:2112.05509"
author_name: "Sevag Hanssian"
authors: "Sevag Hanssian and Hugo Sonnery"
categories: journal
tags: 
- audio
- source-separation
image: "episode-2-sevag-hanssian.png"
author_picture: "sevag-hanssian.jpeg"
illustration: "illustration-sevag-hanssian.png"
youtubeId: "9X5u8tKUecY"
personal_website: "https://github.com/sevagh"
laboratory_website: "https://ddmal.music.mcgill.ca/"
scholar_profile: "https://deepai.org/profile/sevag-hanssian"
slides_url: "https://lukewys.github.io/"
speaker_bio: "Sevag is a second-year research master's student advised by Prof. Ichiro Fujinaga at McGill University. He's interested in signal processing, time-frequency analysis, and music source separation."
abstract: "Music source separation is the task of extracting an estimate of one or more isolated sources or instruments (for example, drums or vocals) from musical audio. The task of music demixing or unmixing considers the case where the musical audio is separated into an estimate of all of its constituent sources that can be summed back to the original mixture. The Music Demixing Challenge was created to inspire new demixing research. Open-Unmix (UMX), and the improved variant CrossNet-Open-Unmix (X-UMX), were included in the challenge as the baselines. Both models use the Short-Time Fourier Transform (STFT) as the representation of music signals. The time-frequency uncertainty principle states that the STFT of a signal cannot have maximal resolution in both time and frequency. The tradeoff in time-frequency resolution can significantly affect music demixing results. Our proposed adaptation of UMX replaced the STFT with the sliCQT, a time-frequency transform with varying time-frequency resolution. Unfortunately, our model xumx-sliCQ achieved lower demixing scores than UMX."
supplement: ""
---


# About the speaker

**Bio** : {{ page.speaker_bio }}

Do not hesitate to check out [{{ page.author_name }}]({{ page.scholar_profile }}){:target="_blank"}'s personal [website]({{ page.personal_website }}){:target="_blank"} for latest updates !

![{{ page.author_name }}]({{ site.github.url }}/assets/img/{{ page.author_picture }}) 



# Recording


**Video recording** of the speaker's presentation :

{% include youtubeplayer.html id=page.youtubeId %}



# Paper

**Paper** : [{{ page.paper_name }}]({{ page.paper_url }}){:target="_blank"} [{{ page.paper_arxiv_code }}]

![{{ page.paper_name }}]({{ site.github.url }}/assets/img/{{ page.illustration }})

**Abstract** : {{ page.abstract }}



# Supplementary material

**Useful resources** : Courtesy of the speaker, the interested reader may find additional information in the *references* below :
* 🧑‍🔬 {{ page.author_name }}'s [personal website]({{ page.personal_website }}){:target="_blank"}
* 🏫 {{ page.author_name }}'s [laboratory_website]({{ page.laboratory_website }}){:target="_blank"}
* 📚 {{ page.author_name }}'s [google scholar profile]({{ page.scholar_profile }}){:target="_blank"}
* 💡 [Slides]({{ page.slides_url }}){:target="_blank"} used during {{ page.author_name }}'s presentation

{{ page.supplementary_info }}