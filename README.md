# Europe-Crustal-GMM
Codes for A Hybrid Non-Parametric Ground Motion Model for Shallow Crustal Earthquakes in Europe

The data provided correspond to the developed ground motion models using machine learning models for predicting ground motion parameters and response spectra to ESM database.
Sreenath Vemula, Bhargavi Podili, Raghukanth STG

Manuscript DOI: https://doi.org/10.1002/eqe.3845
Code DOI: https://doi.org/10.6084/m9.figshare.21229034

Abstract: In the current study, ground motion models (GMMs) are derived using the European Strong Motion (ESM) database for pseudo-spectral acceleration (PSA), peak ground acceleration (PGA), peak ground velocity (PGV), peak ground displacement (PGD), cumulative absolute velocity (CAV), arias intensity (Ia), and significant duration. In addition to addressing random effects associated with ground motion regression, such as inter-event, inter-site, inter-locality, and inter-region variabilities, the current study also aims at reducing the standard deviations (STDs) of the GMMs through development of a hybrid non-parametric GMM. The hybrid model is derived through an ensemble-weighted method of five non-parametric machine learning models: shallow neural network, deep neural network (DNN), gated recurrent unit (GRU), support vector, and random forest (RF) regression techniques; with weights based on model performances. The resulting hybrid model, which also accounts for epistemic uncertainty, is compared against other regional models and is found superior for all output variables. The inter-event, inter-site, inter-locality, and inter-region deviations, and total ergodic sigma of PSA for the ensemble model lies between 0.3164–0.4478, 0.4156–0.5339, 0.1449–0.3687, 0.0819–0.2421, and 0.668–0.8545, respectively. The coefficient of determination (R2) between predicted and recorded values lies between 0.8435–0.9114 for all the output variables.
