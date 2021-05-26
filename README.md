# LPLSG
* Predicting lncRNA-protein interactions based on network similarity

# Requirements
* ues python 3.6.12
* numpy 1.19.2
* pandas 1.1.1 
* scipy 1.5.2
* sklearn 
* pytorch 1.4
* matplotlib 3.3.1

# Data description
* 24_protein.xlsx: list of protein names.
* 982_lncRNaA.xlsx: list of lncRNA names.
* 4152_interaction.xlsx：proteins and lncRNAs association network.

# Code description
* calcul_height_score.py: the protein set to obtain the highest score of the lncRNA set in the predicted results
* k_5_verifi.py: 5-k cross validation method involved in the experiment.

# Result description
* pred_score_4152_lncRNA_protein.xlsx: The predicted scores of lncRNA and protein were calculated by LPLSG.
* predict_10_LPI.xlsx: The predicted scores of top 10 lncRNAs corresponding to proteins.

# Supplementary materials.pdf
* Supporting materials involved in the article.

# If you have any questions, please contact：
* wangyongqing422@gmail.com
