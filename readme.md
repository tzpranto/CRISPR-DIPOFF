# CRISPR-DIPOFF (Deep Interpretable Predictors for OFF-targets)
## Introduction
CRISPR-DIPOFF is an Interpretable Deep Learning Approach for CRISPR Cas-9 Off-Target Prediction. It has outperformed the previous studies by a significant margin.
The related paper can be found [here](https://academic.oup.com/bib/article-pdf/25/2/bbad530/56625790/bbad530.pdf).
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
2. Follow the input format of `Sample Input/sample_input.csv`.
3. Run the notebook `Predict with LSTM Model.ipynb`. 
### Prediction with Finetuned ELECTRA Model
Experiments are ongoing. Will be published soon.

## Experiments
### RNN-Based Experiments with Genetic Algorithm
Data available in `RNN Experiments/Data/Sequence`
Scripts available in `RNN Experiments`
Steps:
1. Run Preprocessing Script `RNN Experiments/Preprocessing.ipynb`
2. Run Genetic Algorithm `RNN Experiments/Genetic_Algorithm_RNNs V3.ipynb`
3. Run Model Interpretation `RNN Experiments/BEST_Model_Interpretation.ipynb`
4. Run Interpretation Visualizer `RNN Experiments/Data Analysis.ipynb`

### ELECTRA-Based Experiments
Experiments are ongoing. Will be published soon.

## Citation
If you use this code for publication, please cite the original paper.
```
@article{toufikuzzaman2024crispr,
  title={CRISPR-DIPOFF: an interpretable deep learning approach for CRISPR Cas-9 off-target prediction},
  author={Toufikuzzaman, Md and Hassan Samee, Md Abul and Sohel Rahman, M},
  journal={Briefings in Bioinformatics},
  volume={25},
  number={2},
  pages={bbad530},
  year={2024},
  publisher={Oxford University Press}
}
```

## Contact
For help or issues using this codebase, please submit a GitHub issue.

For personal communication related to this codebase, please contact Md. Toufikuzzaman (md.toufikzaman@gmail.com).
