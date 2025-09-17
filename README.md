# PlanTok
> TL;DR — We introduce PlanTok, an intermediate scene representation for end-to-end autonomous driving planning.

**Status:** under review.  
**Paper:** [PDF coming soon]  
**Project page:** this repository.  
**Code/Weights:** will be released upon acceptance.

## Overview
PlanTok tokenizes multi-view visual features into a compact scene latent that preserves semantic, geometric, and appearance cues for downstream planning.



## Results (nuScenes)
- Collision rate and L2 planning metrics competitive with prior art.
- Information richness remains close to the no-compression baseline from Max to 256 tokens.
(*Detailed tables and plots will be added with the code release.*)

## Release Plan
- Inference demo and pretrained weights: after notification of acceptance.  
- Training code and pseudo-label generator: shortly after camera-ready.  

## Citation
<!-- If double-blind, replace with an anonymous placeholder -->
```bibtex
@article{plantok2025,
  title   = {PlanTok: Planning-ready Scene Latent with Tokenized Intermediate Representation},
  author  = {Anonymous},
  year    = {2025},
  note    = {Under review}
}
