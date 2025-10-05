---
layout: distill
title: CorText
description: Brain-language fusion enables interactive neural readout
img: assets/img/cortext_thumbnail.png
importance: 1
category: work
visible: false
related_publications: cortext_preprint

# authors:
#   - name: Victoria Bosch
#     affiliations:
#       name: Osnabrück University
#   - name: Dirk Gütlin
#     affiliations:
#       name: Freie Universität Berlin
#   - name: Adrien Doerig
#     affiliations:
#       name: Osnabrück University
#   - name: Daniel Anthes
#     affiliations:
#       name: Osnabrück University
#   - name: Sushrut Thorat
#     affiliations:
#       name: Osnabrück University
#   - name: Peter König
#     affiliations:
#       name: Osnabrück University
#   - name: Tim C Kietzmann
#     affiliations:
#       name: Osnabrück University
#       email: tim.kietzmann@uos.de


# toc:
#   - name: Background
#   - name: Architecture
---
[Preprint](https://arxiv.org/pdf/2509.23941)

Large language models (LLMs) have revolutionized human-machine interaction, and have been extended by embedding diverse modalities such as images into a shared language space. Yet, neural decoding has remained constrained by static, non-interactive methods. We introduce CorText, a framework that integrates neural activity directly into the latent space of an LLM, enabling open-ended, natural language interaction with brain data. Trained on fMRI data recorded during viewing of natural scenes, CorText generates accurate image captions
and can answer more detailed questions better than controls, while having access to neural data only. We showcase that CorText achieves zero-shot generalization beyond semantic categories seen during training. Furthermore, we present a counterfactual analysis that emulates in-silico cortical microstimulation. These advances mark a shift from passive decoding toward generative, flexible interfaces between brain activity and language.

![CorText Architecture](/assets/img/cortext_architecture.png)


#### Further resources:

Here you can find the PDF of the short paper and poster presented at CCN 2025: [pdf](/assets/pdf/CorText_QA_CCN2025.pdf)

Here you can find the PDF of the short paper presented at CCN 2024: [pdf](/assets/pdf/Cortext_Bosch_CCN2024.pdf)
