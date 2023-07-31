# CRISPR-DIPOFF
## Introduction
CRISPR-DIPOFF is Interpretable Deep Learning Approach for CRISPR Cas-9 Off-Target Prediction. It has outperformed the previous studies by significant margin.
## Released Models
1. LSTM model trained with 4-channel encoding
2. Finetuned ELECTRA model (Will be published soon)
## Usage for Prediction
### Requirements 
* Python 3.8
* pandas 1.5.3
* numpy 1.22.4
* pytorch 2.0.1+cu118
* notebook 6.4.8
### Prediction with LSTM Model
1. Put the input file in `Sample Input` directory 
2. Follow the input format of `Sample Input\sample_input.csv`.
3. Run the notebook `Predict with LSTM Model.ipynb`. 
### Prediction with Finetuned ELECTRA Model
Will be published soon
