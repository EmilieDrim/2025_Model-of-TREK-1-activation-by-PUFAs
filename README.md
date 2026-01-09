README

This repository contains the Python code and supporting material used to generate the simulations presented in Figure 7 of our submitted manuscript: “Gating shift to an ohmic mode of TREK-1 channel induced by docosahexaenoic acid”.

Figure 7, titled “Mathematical model to explain TREK-1 channels recruitment by PUFAs”, is based directly on the computational approach implemented here. This repository allows readers to examine the exact workflow we used to model and simulate the data.
We show that the variability of TREK-1 activation by PUFAs is an intrinsic property of the channel’s behavior, which depends on its initial level of activity. In our model, this variability can emerge from fluctuations in the channel’s open probability, offering a mechanistic explanation for the heterogeneity observed experimentally.

The repository is organized into 3 main components:
1)	Glossary of biophysical parameters: a reference list detailing all biophysical parameters used to describe the behavior of an ion channel.
2)	Theorical definition of model parameters: summarizing our observations of the biological system, specifically the activation of TREK-1 channel by PUFAs, and explaining how these observations were translated into mathematical model.
3)	Python simulation script “2026_01_V4f_Simu_strong_weak_PUFAs_effect_EN.ipyn” : the core script used to simulate the biophysical behavior of TREK-1. Running the script in a Python console will generate datasets that are similar, though not identical, because the model incorporates probabilistic elements. For reproducibility, we also provide in the CSV file “V4f_Simu_PUFA_strong_weak.csv” the exact dataset used for Figure 7 in the manuscript submission.

Using this script, we propose a model that describes TREK-1 activation and its variability, by at least 2 groups of PUFAs: strong and weak activators.
