---
layout: project
title: "FoundHand: Large-Scale Domain-Specific Learning for Controllable Hand Image Generation"
authors:
  - author:
      name: "Kefan Chen"
      affiliation: "1,2"
      link: "https://scholar.google.com/citations?user=HAtfBjoAAAAJ&hl=en&oi=ao"
  - author:
      name: "Chaerin Min"
      affiliation: "1"
      link: "https://chaerinmin.github.io/"
  - author:
      name: "Linguang Zhang"
      affiliation: "2"
      link: "https://lg-zhang.github.io/"
  - author:
      name: "Shreyas Hampali"
      affiliation: "2"
      link: "https://shreyashampali.github.io/"
  - author:
      name: "Cem Keskin"
      affiliation: "2"
      link: "https://scholar.google.co.uk/citations?user=9HoiYnYAAAAJ&hl=en"
  - author:
      name: "Srinath Sridhar"
      affiliation: "1"
      link: "https://cs.brown.edu/people/ssrinath/"
affiliations:
  - "<sup>1</sup> Brown University"
  - "<sup>2</sup> Meta Reality Lab"
  - "*[Equal Contribution]"
journal: 
redirect_from:
  - add redirect_path here
  - another path here
---

{% include icons.html paper="" demo(Jan 25)="" code(Jan 25)="" %}


## Overview

{% include full_image.html path="/assets/images/projects/foundhand/teaser.jpg" %}

Despite remarkable progress in image generation models, generating realistic hands remains a persistent challenge due to their complex articulation, varying viewpoints, and frequent occlusions. We present FoundHand, a large-scale domain-specific diffusion model for synthesizing single and dual hand images. To train our model, we introduce FoundHand-10M, a large-scale hand dataset with 2D keypoints and segmentation mask annotations. Our insight is to use 2D hand keypoints as a universal representation that encodes both hand articulation and camera viewpoint. FoundHand learns from image pairs to capture physically plausible hand articulations, natively enables precise control through 2D keypoints, and supports appearance control. Our model exhibits core capabilities that include the ability to repose hands, transfer hand appearance, and even synthesize novel views. This leads to zero-shot capabilities for fixing malformed hands in previously generated images, or synthesizing hand video sequences. We present extensive experiments and evaluations that demonstrate state-of-the-art performance of our method.



## Citation


## Acknowledgements
Part of this work was done during Kefan (Arthur) Chen’s internship at Meta Reality Lab. 
This work was additionally supported by NSF CAREER grant #2143576, NASA grant #80NSSC23M0075, and an Amazon Cloud Credits Award.

## Contact

Kefan (Arthur) Chen kefan_chen@brown.edu
