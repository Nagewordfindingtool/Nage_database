# Nage_database
'Target-Description' data collected from crowd-sourcing.

- Folder 'checking_in_process' shows half raw data after POS and manual filtering after checking step 1&2.
- Folder 'pretraining_dataset' contains training dataset for our Chinese-bert-wwm model fine-tuning works, in which tag '1' means true 'target-descriptions' pair values, and tag '0' represents the negtive pairs obtained from [wrong descriptions replacement] and [wrong 'target-descriptions' pairing].
- File 'desc_sort_by_dim_frequency.csv'  shows statistical results on descriptions grouped by their hyper dimensions after manual processing.
- File 'desc_to_targets.csv' shows the bottom descriptions and their paring target words without dimension classification after manual processing.
- File 'target_desc_single_pairs.csv' lists all single 'target-dimension-description' pairs after manual processing.
