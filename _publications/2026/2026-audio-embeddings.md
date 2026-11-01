---
title:          "Estimating the Structure of Low-level Acoustic Attribute Encodings in Pretrained Representations"
date:           2026-09-25 12:00:00 -0500
selected:       true
# pub:            "Advances in Neural Information Processing Systems (NeurIPS)"
pub_pre:        "Submitted to ICASSP"
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
    Pretrained models have become critical tools in audio ma chine learning, yet it remains unclear which aspects of the input audio are preserved in their representations and how these embeddings respond to changes in their inputs. These properties are important to researchers as the representations’ sensitivities and invariances determine which downstream tasks they can be applied to. In this work we characterize the sensitivity of pretrained models’ representations to continu ous, one-dimensional transformations of their input audio by analyzing how the intrinsic dimensionality of the manifolds traced by each transformation in representation space varies across natural sounds. We apply this technique to mod els trained on generative, contrastive, and fully-supervised classification tasks to assess how sensitivity differs across common pretraining tasks. We find that the manifolds gen erated by transformations of common low-level acoustic attributes tend to have relatively low intrinsic dimensionality, despite occupying high dimensional subspaces. The intrin sic dimensionality varies significantly across transformations and embedding model, and shows subtler differences across sound class.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Tanelus A
  - McFee B
links:
  Paper: /assets/etc/2027_icaasp.pdf
  Code: https://github.com/aramist/audio-embeddings
---
