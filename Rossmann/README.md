## Libbraries required:

#!pip install --quiet pytorch-lightning

#!pip install --quiet tqdm

#!pip install shap

#!pip install lime

#!pip install boruta

#!pip install BorutaShap

as well as the IMV_LSTM.py file


## How to use

- create a folder and store all this files inside it

- creat another set of folders: 00-Baseline_datasets-forecast -> 03-Rossman -> [place Rossmann data here]

- run the Rossmann data exploration script, run the GridSearch_and_effects up to the all features section, full run the Single Run script, run the rest of the GridSearch file

- to change stores to be ran, in the GridSearch just need to change the Rossmann_df = Rossmann_df[Rossmann_df['Store'] == XXX ]  on the 6th cell, and on the Single Run is the same thing on the beginning of the 6th cell as well as the df_og = df_og [df_og ['Store'] == XXX ] on the third to last cell
