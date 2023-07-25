---
layout: page
title: Automatic speech recognition (ASR) for dysarthria detection
description: Using ASR for the extraction of acoustic speech biomarkers in neurological diseases
importance: 3
category: work
---

Acoustic analysis of speech and voice is rarely used outside of research settings, owing to its complexity. Specialized software is required and often this software is not even capable of extracting acoustic measures of interest for clinicians; for example, some articulatory gestures are recommended to only be measured during certain parts of speech in order to be clinically valid. This can be difficult to achieve and usually the fallback, in a research setting, is having research assistants manually annotate speech recordings. This project seeks to overcome this critical limitation by using ASR to take the place of the human rater who would otherwise have to perform tedious and time-consuming data processing steps. Given the good baseline performance of ASR systems like [Wav2Vec2Phoneme](https://huggingface.co/docs/transformers/model_doc/wav2vec2_phoneme), and the availability of good-quality clinical datasets from our lab, we hypothesize that the performance of ASR systems can be improved to the point that it assists in detecting severe dysarthria in patients with ALS and Parkinson's disease.
