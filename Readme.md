# Outs Above Average for Shortstops

## Overview
According to the Statcast, Outs Above Average (OAA) is a range-based metric of skill that shows how many outs a player has saved. For example, a fielder who catches a 25% catch probability play gets +0.75; one who fails to make the play gets -0.25. Prior to 2020, OAA was an outfield-only metric. OAA is calculated differently for outfielders and infielders. Therefore, the purpose of this project is to develop a framework which is capable of estimating out probability for each in-play ground ball first fielded by shortstop and further calculating OAA for each shortstop. This project is basically composed of four parts as follows:

1. Feature engineering
2. Model building (k-NN, random forest, and XGBoost) and parameter tuning (cross validation and grid search)
3. Probability calibration (Platt scaling and isotonic regression)
4. Model evaluation (overall accuracy, confusion matrix, and reliability diagram)


## Link to the Project
1. https://nbviewer.jupyter.org/github/KUANCHENGFU/Outs-Above-Average-for-Shortstops/blob/main/Outs_above_average_for_shortstops.ipynb
