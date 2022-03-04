---
layout: post
title: "Episode 3 : Error Detection in Symbolic Music for OMR Preprocessing"
paper_url: "#"
paper_arxiv_code: "#"
author_name: Timothy de Reuse
author: Timothy de Reuse and Hugo Sonnery
categories: journal
tags:
  - digital-humanities;music-understanding;music-transcription
image: episode-3-timothy-de-reuse.png
author_picture: timothy-de-reuse.jpeg
illustration: illustration-timothy-de-reuse.png
youtubeId: https://youtu.be/aNxtX6Gkl9c
personal_website: https://ddmal.music.mcgill.ca/lab_members/phd/timothy_dereuse/
laboratory_website: https://ddmal.music.mcgill.ca/
scholar_profile: https://scholar.google.ca/citations?user=vRKhaogAAAAJ&hl=en
slides_url: "#"
speaker_bio: >-
  I am a Ph.D. student working under Ichiro Fujinaga in the Music Technology
  Area of the Schulich School of Music, McGill University. My research interests
  center around analysis of repeated material in symbolic music; in particular,
  how machine-learning models can learn from long-term dependencies in music
  (e.g., verse-chorus forms, sonata forms) to make predictions and correct
  errors in scores. I also research musical pattern discovery algorithms, and
  how existing examples of annotated patterns can be used as examples to filter
  the large number of patterns that these algorithms often retrieve.\

  Before my arrival at McGill, I was a research assistant in the Computational Epidemiology Research Laboratory at the University of North Texas, where I investigated models of traffic flow in disaster response scenarios.
abstract: This presentation outlines a machine-learning method for detecting
  errors in symbolic music scores using a Transformer network. The outputs of
  most Optical MusicRecognition (OMR) systems still require manual human
  correction, especially when dealing with complex, polyphonic scores. Given
  that most of the errors introduced into scores by OMR processes are highly
  "non-musical," we propose that this time-consuming correction task could be
  sped up by marking all sections of a score that are likely to contain OMR
  errors as a post-processing step. Using a dataset of Romantic-era string
  quartets, we train a Long Short-Term Universal Transformer (a variant of the
  popular Transformer network architecture) on the task of classifying each
  symbol of each piece as correct or erroneous, based on whether a manual
  correction of that piece would require an insertion, deletion, or replacement
  of a symbol at that location. Since we have a limited amount of data with real
  OMR errors, we employ extensive data augmentation to add errors into string
  quartets in a way that mimics how OMR would modify the score. Our
  best-performing model achieves 98% recall and 64% precision at detecting
  errors, which could significantly reduce the number of measures a human would
  need to check to be assured that they had reviewed all errors in an OMR
  output.
supplement: \-
---
\-