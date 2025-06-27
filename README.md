# VCR: Video Representation for Contextual Retrieval
Authors: Oron Nir&nbsp;· Idan Vidra&nbsp;· Avi Neeman&nbsp;· Barak Kinarti&nbsp;· Ariel Shamir

![Our Topics-Map](https://github.com/oronnir/VCR/blob/main/ArchiveExplorer-04.png?raw=true "Our Topics-Map")

## Abstract
Streamlining content discovery within media archives requires integrating advanced data representations and effective visualization techniques for clear communication of video topics to users. The proposed system addresses the challenge of efficiently navigating large video collections by exploiting a fusion of visual, audio, and textual features to accurately index and categorize video content through a text-based method. Additionally, semantic embeddings are employed to provide contextually relevant information and recommendations to users, resulting in an intuitive and engaging exploratory experience over our topics ontology map using OpenAI GPT-4.

![Our text-based architecture](https://github.com/oronnir/VCR/blob/main/MethodArchitecture.png?raw=true "Text-based Video Embedding")

---

## Demo&nbsp;Video
[![YouTube](https://img.shields.io/badge/Watch%20on%20YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=28_3ntFX2Hs)

---

## Download the TED VCR Data&nbsp;&nbsp;📦
| File | Description | Size | Download |
|------|-------------|------|----------|
| **TED-VCR Dataset**<br>`ted_vcr.zip` | Raw TED talks trimmed, aligned, and curated for our experiments | 4.2 GB | [![Download](https://img.shields.io/badge/TED%20Dataset-DOWNLOAD-blue?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com/uc?export=download&id=1GrxniS1eZch-tUrwex01SpvwX8qrH9uZ) |
| **TED-VCR Embeddings**<br>`ted_vcr_embeddings.zip` | Pre-computed CLIP/Whisper embeddings for fast experimentation | 1.8 GB | [![Download](https://img.shields.io/badge/Embeddings-DOWNLOAD-8E44AD?style=for-the-badge&logo=google-drive&logoColor=white)](https://drive.google.com/uc?export=download&id=1GsrmLP5g0uFfHt4tr4qzs3iTwB8eR-FB) |

> **Note** — Both archives are shared under TED’s *CC BY-NC-ND 4.0 International* license.  
> Commercial use is **not** permitted. Please cite our paper when using the data.

---

## News & Updates
- **2024-04-10** – Our paper has been accepted to *IRESP 2024* &nbsp;[![arXiv](https://img.shields.io/badge/arXiv-2402.07466-b31b1b.svg)](https://arxiv.org/abs/2402.07466)  
- **2024-03-15** – License clarified for TED content (CC BY-NC-ND 4.0).

---

## Coming Soon
- ~~The TED dataset~~ ✔️
- Code release 🎉

---

## Citation
If you find our work useful, please cite:

```bibtex
@inproceedings{10.1145/3661725.3661766,
author = {Nir, Oron and Vidra, Idan and Neeman, Avi and Kinarti, Barak and Shamir, Ariel},
title = {VCR: Video representation for Contextual Retrieval},
year = {2024},
isbn = {9798400716393},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3661725.3661766},
doi = {10.1145/3661725.3661766},
abstract = {Streamlining content discovery in media archives requires advanced data representations and effective visualization techniques for clear communication of video topics to users. The proposed system addresses the challenge of efficiently navigating large video collections by exploiting a fusion of visual, audio, and textual features to accurately index and categorize video content through a text-based method. Additionally, semantic embeddings are employed to provide contextually relevant information and recommendations to users, resulting in an intuitive and engaging exploratory experience over our topics ontology map using LLMs (GitHub).},
booktitle = {Proceedings of the International Conference on Computing, Machine Learning and Data Science},
articleno = {39},
numpages = {9},
keywords = {Archive Exploration, Media Search, Video Representation},
location = {Singapore, Singapore},
series = {CMLDS '24}
}
