# Neural-Sequence-Decoder-for-Speech-BCI

This repository contains info for training a neural sequence decoder, based on the work involving speech brain-computer interfaces (BCIs) as described in related publications and repositories.

## Overview

The code implements a GRU-based decoder model (GRUDecoder) using PyTorch to translate neural signals into sequences (e.g., phonemes for speech synthesis). It includes scripts for data processing, model training, and evaluation.

This work utilizes and references the following resources:
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

