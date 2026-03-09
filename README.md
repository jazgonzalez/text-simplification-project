# Text Simplification Project

This repository contains the development and evaluation of various Natural Language Processing (NLP) models focused on Text Simplification

## Overview

The goal of this project is to transform complex sentences into simpler, more readable versions while preserving the original meaning. We experimented with different Transformer-based architectures, including T5 and BART, fine-tuned on standard simplification datasets like TurkCorpus and ASSET.

## Notebooks and Resources

* **T5 Models**: Implementation and training of T5-base and T5-small models.
* **BART Models**: Large-scale simplification using BART-large architectures.
* **Evaluation**: Scripts for measuring performance using datasets from HuggingFace.

## Tech Stack

* **Language**: Python 3.x
* **Libraries**: Pandas, HuggingFace Transformers, PyTorch.
* **Datasets**: TurkCorpus and ASSET via HuggingFace Hub.

## Usage

1. Clone the repository:
   `git clone https://github.com/jazgonzalez/text-simplification-project.git`
2. Install dependencies:
   `pip install -r requirements.txt`
3. Run the Jupyter Notebooks to see the training and inference logs.
