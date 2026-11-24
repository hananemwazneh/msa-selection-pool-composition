# Robustness of Deep-Learning MSA Selection to Candidate-Pool Composition

Code and data for the CMPS 355 paper by Hanane Wazneh and Zahraa Hussein (AUB, 2026).

## Notebooks
- `MSA_Selection.ipynb` – main analysis (simulation, candidates, features, 3,500 pools, Model 2 vs fixed reference vs SoP)
- `MSA_Selection_Revision.ipynb` – revision analyses (realistic reference, reference composition and size, 12 SoP settings, adding candidates, feature distributions)

## Data
- `*_features.csv` – 153 features and dseq for the 1,200 candidates of each dataset
- `SIM0*_indelible_control.txt`, `SIM0*_tree.txt`, `SIM0*_settings_and_seed.json` – simulation files for the new datasets

## Results
- `per_pool_results_3500.csv` – regret of each method in every pool
- `Supplementary_Table_S1_bootstrap_intervals.csv` – per-dataset 95% bootstrap intervals
- `check_A_implementation.csv` – implementation check
- `revision_perpool.csv`, `revision_stats.csv` – revision results for all references and SoP settings
- `revision_fix_vs_mixing.csv` – adding candidates vs fixed reference
- `fig_feature_distributions.png` – Figure 3

Model 2 and the feature code come from https://github.com/nimrodSerokTAU/sp_alternative (commit 766a6a6).
