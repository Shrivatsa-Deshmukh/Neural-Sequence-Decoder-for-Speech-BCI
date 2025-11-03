# Neural Decoder for Real-Time Speech Synthesis BCI

This repository provides documentation and curates external links pertaining to a GRU-based neural sequence decoder (GRUDecoder). The referenced projects utilize PyTorch to map neural signals to sequential outputs (e.g., phonemes for speech synthesis) and detail the necessary scripts for data processing, model training, and evaluation.

## Overview

* GitHub Repo: [cffan/neural_seq_decoder](https://github.com/cffan/neural_seq_decoder/tree/master)
* GitHub Repo: [fwillett/speechBCI](https://github.com/fwillett/speechBCI)
* Paper: [A High-Performance Speech Neuroprosthesis](https://www.nature.com/articles/s41586-023-06377-x) 
* Dataset: [Data](https://datadryad.org/dataset/doi:10.5061/dryad.x69p8czpq)

## Code Structure
* train_model.py: Main script to start training.
* neural_decoder_trainer.py: Core training and evaluation logic.
* model.py: Defines the GRUDecoder model architecture.
* dataset.py: Handles dataset loading and preprocessing.
* augmentations.py: Contains data augmentation functions.
* formatCompetitionData.ipynb: Notebook for initial data formatting.

