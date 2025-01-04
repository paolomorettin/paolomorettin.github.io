---
title: ""
permalink: /pcgml/
author_profile: true
redirect_from:
  - /pcgml
---

{% include base_path %}


## Procedural content generation via ML


In the free time, I enjoy studying game development and I'm particularly
intrigued by the use of AI techniques for the automated generation of
content.

My focus is on the generation of functional (as opposed to cosmetic)
content. Simply put, game levels or rules rather than textures or
sound effects. The challenge with functional content is that it must
satisfy very complex constraints.

![A SMB level!](/images/pcgml.jpg "SMB")

*For instance, unsurpassable obstacles like huge gaps or walls can
make a platformer level impossible to complete. Contrarily to the
generation of images, a single bit change could turn a playable level
into an unplayable one.*

As a joint research effort with multiple thesis students, we developed
Constrained Adversarial Networks
([paper](https://proceedings.neurips.cc/paper/2020/file/a87c11b9100c608b7f8e98cfa316ff7b-Paper.pdf
'canpaper')), a neuro-symbolic deep generative model that was used,
among other things, for the generation of playable Super Mario
Bros. levels and stable molecules.
