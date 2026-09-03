---
layout: page
title: CorText
description: Brain-language fusion enables interactive neural readout
img: assets/img/cortext_thumbnail.png
importance: 1
category: work
visible: false
related_publications: cortext_preprint


# toc:
#   - name: Background
#   - name: Architecture
---

CorText enables query of visually evoked brain activity using natural language. It maps fMRI recording into an LLM’s language embedding space end-to-end, moving neural decoding from static labels toward flexible interaction with brain activity. The resulting interface allows testing how changes in neural data affect semantic output.

#### What CorText does
- Interactive neural readout: CorText answers open-ended and follow-up questions about perceived scenes.
- Zero-shot generalisation: It handles concepts and requests beyond those explicitly encountered during training.
- Counterfactual experimentation: In-silico microstimulation produces consistent, graded changes in language output.  

#### About the project
 CorText is the core project of my PhD research, where I have led the central development, implementation and analysis of the model. This project is supervised by Prof. Dr. Tim C Kietzmann at the University of Osnabrück, in collaboration with Daniel Anthes, Adrien Doerig, Sushrut Thorat, and Peter König.  

#### [Read the preprint →](https://arxiv.org/pdf/2509.23941)    

  

<!--### Abstract
Large language models (LLMs) have revolutionized human-machine interaction, and have been extended by embedding diverse modalities such as images into a shared language space. Yet, neural decoding has remained constrained by static, non-interactive methods. We introduce CorText, a framework that integrates neural activity directly into the latent space of an LLM, enabling open-ended, natural language interaction with brain data. Trained on fMRI data recorded during viewing of natural scenes, CorText generates accurate image captions
and can answer more detailed questions better than controls, while having access to neural data only. We showcase that CorText achieves zero-shot generalization beyond semantic categories seen during training. In-silico microstimulation experiments, which enable counterfactual prompts on brain activity, reveal a consistent, and graded mapping between brain-state and language output. These advances mark a shift from passive decoding toward generative, flexible interfaces between brain activity and language.  -->

<div align="center">
<img src="/assets/img/cortext_architecture_chat.png" alt="CorText Architecture" style="width: 600px; max-width: 100%; height: auto;">

</div>  

---
 

#### Resources and project evolution
- Extension of CorText to macaque intracranial recordings (CCN 2026 [abstract](/assets/pdf/Bosch_et_al_CorText_CCN_2026_Extended_Abstracts.pdf) and [poster](/assets/pdf/CorTextCCN2026.pdf)
- Development of Q&A functionality in CorText, direct decoder-only fusion. Short paper and poster presented at CCN 2025. [PDF](/assets/pdf/CorText_QA_CCN2025.pdf)
- Caption decoding with encoder-decoder architecture, the first short paper presented at CCN 2024. [PDF](/assets/pdf/Cortext_Bosch_CCN2024.pdf)


<!--Main preprint. [link](https://arxiv.org/pdf/2509.23941)-->
