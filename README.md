# World Model Papers
Selected list of papers on World Models that I found interesting and/or useful in chronological order (mostly 2024 and before). For clarification since the term is overloaded now, world model is mainly referring to a learned representation of a (typically visual) environment that is useful for downstream model-based RL tasks -- not the LLM "world model"! Suggestions and pull requests are welcome and appreciated!

# Areas
  * [General World Models](#general-world-models)
  * [Policy Improvements](#policy-improvements)
  * [Language-oriented](#language-oriented)
  * [Visual and Robotics](#visual-and-robotics)
  

## General World Models
  * D. Ha and J. Schmidhuber, ["Recurrent World Models Facilitate Policy Evolution"](https://arxiv.org/abs/1803.10122), 2018. [[site]](https://worldmodels.github.io/) | [[code]](https://blog.otoro.net/2018/06/09/world-models-experiments/) | [[bibtex]](./world-model-papers.bib#L1-L10)
  * D. Freeman and L. Metz and D. Ha, ["Learning to Predict Without Looking Ahead: World Models Without Forward Prediction"](https://proceedings.neurips.cc/paper_files/paper/2019/file/15cf76466b97264765356fcc56d801d1-Paper.pdf), 2019. [[site]](https://learningtopredict.github.io/) | [[code]](https://github.com/google/brain-tokyo-workshop/tree/master/learntopredict) | [[bibtex]](./world-model-papers.bib#L12-L19)
  * Kipf et al., ["Contrastive Learning of Structured World Models"](https://arxiv.org/abs/1911.12247v2), 2020. [[code]](https://github.com/tkipf/c-swm) | [[bibtex]](./world-model-papers.bib#L21-L28)
  * Zhang et al., ["World Model as a Graph: Learning Latent Landmarks for Planning"](https://arxiv.org/abs/2011.12491), 2021. [[code]](https://github.com/LunjunZhang/world-model-as-a-graph) | [[bibtex]](./world-model-papers.bib#L30-L37)
  * V. Micheli, and E. Alonso and F. Fleuret, ["Transformers are Sample-Efficient World Models"](https://openreview.net/forum?id=vhFu1Acb0xb), 2023. [[code]](https://github.com/eloialonso/iris) | [[bibtex]](./world-model-papers.bib#L39-L46)
  * Deng et al., ["Facing Off World Model Backbones: RNNs, Transformers, and S4"](https://arxiv.org/abs/2307.02064), 2023. [[site]](https://fdeng18.github.io/s4wm/) | [[bibtex]](./world-model-papers.bib#L165-L172)

## Policy Improvements
  * **(DreamerV1)** Hafner et al., ["Dream to Control: Learning Behaviors by Latent Imagination"](https://arxiv.org/abs/1912.01603) 2019. [[code]](https://github.com/google-research/dreamer) | [[bibtex]](./world-model-papers.bib#L48-L55)
  * **(DreamerV2)** Hafner et al., ["Mastering Atari with Discrete World Models"](https://arxiv.org/abs/2010.02193), 2020. [[code]](https://github.com/danijar/dreamerv2) | [[bibtex]](./world-model-papers.bib#L57-L64)
  * **(TransDreamer)** Chen et al., [TransDreamer: Reinforcement Learning with Transformer World Models"](https://arxiv.org/abs/2202.09481), 2022. [[bibtex]](./world-models-papers.bib#L66-L73)
  * **(CASCADE)** Xu et al., [Learning General World Models in a Handful of Reward-Free Deployments](https://arxiv.org/abs/2210.12719), 2022. [[code]](https://github.com/facebookresearch/cascade) | [[site]](https://ycxuyingchen.github.io/cascade/) | [[bibtex]](./world-models-papers.bib#L120-L127)
  * **(DreamerV3)** Hafner et al., ["Mastering Diverse Domains through World Models"](https://arxiv.org/abs/2301.04104), 2023. [[code]](https://github.com/danijar/dreamerv3) | [[bibtex]](./world-models-papers.bib#L75-L82)
  * **(Voyager)** Wang et al., ["Voyager: An Open-Ended Embodied Agent with Large Language Models"](https://arxiv.org/abs/2305.16291), 2023. [[code]](https://github.com/MineDojo/Voyager) | [[site]](https://voyager.minedojo.org) | [[bibtex]](./world-models-papers.bib#L111-L118)

## Language-oriented
  * Cowen-Rivers and Naradowsky, ["Emergent Communication with World Models"](https://arxiv.org/abs/2002.09604), 2020. [[bibtex]](./world-model-papers.bib#L84-L91)
  * **(DECKARD)** Nottingham et al., ["Do Embodied Agents Dream of Pixelated Sheep: Embodied Decision Making using Language Guided World Modelling"](https://arxiv.org/abs/2301.12050), 2023. [[code]](https://github.com/DeckardAgent/deckard) | [[bibtex]](./world-model-papers.bib#L93-L100)
  * **(RAP)** Hao et al., ["Reasoning with Language Model is Planning with World Model"](https://arxiv.org/abs/2305.14992), 2023. [[code]](https://github.com/Ber666/RAP) | [[bibtex]](./world-model-papers.bib#L102-L109)
  * **(LanGWM)** Poudel et al., ["LanGWM: Language Grounded World Model"](https://arxiv.org/abs/2311.17593), 2023. [[bibtex]](./world-model-papers.bib#L147-L154)
  * **(Dynalang)** Lin et al. ["Learning to Model the World with Language"](https://arxiv.org/abs/2308.01399), 2023. [[code]](https://github.com/jlin816/dynalang) | [[site]](https://dynalang.github.io) | [[bibtex]](./world-model-papers.bib#L156-L163)
  * **(Language-guided WM)** Zhang et al. ["Language-Guided World Models: A Model-Based Approach to AI Control"](https://arxiv.org/abs/2402.01695), 2024. [[code]](https://github.com/princeton-nlp/lwm/) | [[site]](https://language-guided-world-model.github.io) | [[bibtex]](./world-model-papers.bib#L174-L181)

## Visual and Robotics
  * **(PathDreamer)** Koh et al. ["PathDreamer: A World Model for Indoor Navigation"](https://arxiv.org/abs/2105.08756v2), 2021. [[code]](https://github.com/google-research/pathdreamer) | [[blog]](https://ai.googleblog.com/2021/09/pathdreamer-world-model-for-indoor.html) | [[bibtex]](./world-model-papers.bib#L129-L136)
  * Seo et al. ["Masked World Models for Visual Control"](https://arxiv.org/abs/2206.14244), 2022. [[code]](https://github.com/younggyoseo/MWM) | [[site]](https://sites.google.com/view/mwm-rl) | [[bibtex]](./world-model-papers.bib#L138-L145)
