---
layout: distill
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
## Check out our [Preprint](https://arxiv.org/pdf/2509.23941)!
### Abstract
Large language models (LLMs) have revolutionized human-machine interaction, and have been extended by embedding diverse modalities such as images into a shared language space. Yet, neural decoding has remained constrained by static, non-interactive methods. We introduce CorText, a framework that integrates neural activity directly into the latent space of an LLM, enabling open-ended, natural language interaction with brain data. Trained on fMRI data recorded during viewing of natural scenes, CorText generates accurate image captions
and can answer more detailed questions better than controls, while having access to neural data only. We showcase that CorText achieves zero-shot generalization beyond semantic categories seen during training. In-silico microstimulation experiments, which enable counterfactual prompts on brain activity, reveal a consistent, and graded mapping between brain-state and language output. These advances mark a shift from passive decoding toward generative, flexible interfaces between brain activity and language.  

<div align="center">
<img src="/assets/img/cortext_architecture_chat.png" alt="CorText Architecture" style="width: 600px; max-width: 100%; height: auto;">

</div>  

---


      

#### Further resources:
[PDF of the extended abstact presented at CCN 2026](/assets/pdf/Bosch_et_al_CorText_CCN_2026_Extended_Abstracts.pdf)

[PDF of the short paper and poster presented at CCN 2025](/assets/pdf/CorText_QA_CCN2025.pdf)

[PDF of the short paper presented at CCN 2024.](/assets/pdf/Cortext_Bosch_CCN2024.pdf)
