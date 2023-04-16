# patient_flow

This repository contains the time-series prediction model and hybrid model scripts for master's thesis with the topic "Potilasvirtojen ennustaminen sairaalaverkostossa" ("Patient flow prediction in hospital network"). The scripts contain transition probabilities analysis, time-series model comparison and hybrid model implementations to predict patient count in two units, children's ER and follow-up ward, on a daily and three-shift basis. 

hybrid_first.ipynb and hybrid_triple_first.ipynb contain descriptions for the notebook's functions of hybrid models. SARIMA-model for L1-ward is missing since the size was too big for this repository. A new model can be trained with the timeseriesanalysis_L1.ipynb script.
