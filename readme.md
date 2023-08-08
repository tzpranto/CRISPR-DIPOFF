# CRISPR-DIPOFF (Deep Interpretable Predictors for OFF-targets)
## Introduction
CRISPR-DIPOFF is an Interpretable Deep Learning Approach for CRISPR Cas-9 Off-Target Prediction. It has outperformed the previous studies by a significant margin.
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

## Citation
If you use this code for publication, please cite the original paper.
```
@article {Toufikuzzaman-crispr2023,
	author = {Md. Toufikuzzaman and Md Abul Hassan Samee and M. Sohel Rahman},
	title = {CRISPR-DIPOFF: An Interpretable Deep Learning Approach for CRISPR Cas-9 Off-Target Prediction},
	elocation-id = {2023.08.05.552139},
	year = {2023},
	doi = {10.1101/2023.08.05.552139},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/early/2023/08/06/2023.08.05.552139},
	eprint = {https://www.biorxiv.org/content/early/2023/08/06/2023.08.05.552139.full.pdf},
	journal = {bioRxiv}
}
```

## Contact
For help or issues using this codebase, please submit a GitHub issue.

For personal communication related to this codebase, please contact Md. Toufikuzzaman (md.toufikzaman@gmail.com).
