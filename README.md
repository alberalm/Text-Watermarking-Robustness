# Robustness study of current text watermarking techniques

## Description

This repository contains the code used to run all experiments for my Individual Study Option project at Imperial College London as part of the MSc in Computing (Artificial Intelligence and Machine Learning). The aim of the project was to study how well modern text watermarking techniques resist common attacks that try to remove the watermark and evade detection.

## Repository structure

This repository is organised in the following way:

- The instances folder contains all the generated results from each technique applied.
- The llama folder contains how to download the LLaMA-2-7b and LLaMA-2-7b-chat once you have obtained the key from Meta.
- The rest of the folders refer to specific repositories and just contain a file (new_requirements.txt) with the libraries used in the experiments, which may be different from the requirements listed on the official repo. To replicate the expiments, clone the corresponding repository, change the name of its folder and add the new_requirements.txt file. The link for each repo is shown in the following table:

| Folder   | Link |
| -------- | ------- |
| kirchenbauer-lm-watermarking  | https://github.com/jwkirchenbauer/lm-watermarking |
| kuditipudi-watermark | https://github.com/jthickstun/watermark |
| wang-codable-watermarking-for-llm    | https://github.com/lancopku/codable-watermarking-for-llm |
| yang-Text_Watermark | https://github.com/Kiode/Text_Watermark |
| zhao-Unigram-Watermark | https://github.com/XuandongZhao/Unigram-Watermark |

## Installation

Most of the notebooks have been run on Google Colab. The only relevant package you may need outside of it is the deep_translator package for the round-trip translation attacks.

```bash
pip install deep_translator
```

