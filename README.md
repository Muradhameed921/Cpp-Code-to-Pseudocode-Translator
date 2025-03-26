# C++ Code to Pseudocode Translation using Transformer (Seq2Seq)

## Overview
This project implements a Transformer-based Sequence-to-Sequence (Seq2Seq) model from scratch to convert C++ code into pseudocode. The model is trained without using any pretrained models and is deployed using a Streamlit web application.

## Features
- Custom Transformer-based Seq2Seq model for C++ to pseudocode translation.
- Data preprocessing and tokenization.
- Model training and evaluation.
- Streamlit web application for interactive usage.
- End-to-end workflow from data preparation to deployment.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/CodeToPseudo.git
   cd CodeToPseudo
   ```
2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```


## Dataset Preparation
- The dataset consists of C++ code snippets and their corresponding pseudocode.
- Ensure the dataset is stored in `data/dataset.csv`.
- Preprocess the data by tokenizing both C++ and pseudocode before training.


## Future Improvements
- Enhance dataset size and quality.
- Optimize model architecture for better accuracy.
- Extend to multiple programming languages.
- Deploy as a cloud-based API.


## Results
![C++ Code to Pseudocode Screenshot](https://github.com/Muradhameed921/Sudoku-Puzzle-Solver/blob/main/O1.jpg)
