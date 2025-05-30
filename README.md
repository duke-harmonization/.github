# Data Harmonization and Stroke Risk Prediction

Stroke is the fifth most prevalent cause of death in the U.S. afflicting nearly 800,000 per year. About three
quarters of strokes are first events, underscoring the importance of primary prevention. Designing optimal
preventive strategies requires identification of risk factors and estimation of the risk of stroke. The most recent
American Heart Association (AHA)/American Stroke Association Guidelines for the Primary Prevention of
Stroke conclude that “an ideal stroke risk assessment tool that is simple, is widely applicable and accepted,
and takes into account the effects of multiple risk factors does not exist.” One of the most commonly
recommended predictive models is the Framingham Stroke Profile, developed and updated more than 25
years ago. Newer models have been proposed (including the Self-Reported Stroke Risk Stratification tool from
the REGARDS study) but have not been thoroughly validated. Consequently, the Primary Prevention of Stroke
guidelines call for more research “to validate risk assessment tools across age, sex, and race/ethnic groups”
and “to evaluate whether any of the more recently identified risk factors add to the predictive accuracy of
existing scales”.

We propose to address these gaps by aggregating and harmonizing existing patient-level data collected as
part of longitudinal cohort studies supported by the NINDS and NHLBI. The data will be obtained through a
partnership with the coordinating center for the REGARDS Study at the University of Alabama at Birmingham
and by a request submitted to the NIH dbGap repository to obtain data from the Framingham Offspring, ARIC
and MESA cohorts. At the same time, we will expand the advanced machine learning techniques developed
as part of our currently funded NIH BD2K award to Duke. We will apply these models to the harmonized data
to facilitate development and validation of prediction tool for primary strokes. These complex analyses will
require advanced computational resources that will utilize the AHA’s Precision Medicine Platform (PMP), built
based on Amazon Web Services. 

Manual Harmonization of Cohorts [(dbGaP)](https://github.com/duke-harmonization/manual_harmonization) [(BioLINCC)](https://github.com/duke-harmonization/manual_harmonization_biolincc): Process for converting dbGaP phenotype data (Framingham, MESA and ARIC) from raw to final SAS analysis datasets.

[[PMP Website]](https://precision.heart.org/duke-ninds): Stroke Risk Prediction Using a Harmonized Dataset of Framingham, MESA, ARIC, & REGARDS (Pilot).

## Publications
1. [[xCI]](https://github.com/duke-harmonization/equitable-stroke-risk-prediction) Engelhard M., Wojdyla D., Wang H., Pencina M., Henao R. Exploring trade-offs in equitable stroke risk prediction with parity-constrained and race-free models. *Artificial Intelligence in Medicine*. 2025 Apr 10:103130.
2. [[SONAR]](https://medinform.jmir.org/2025/1/e54133/authors) Yang D., Zhou D., Cai S., Gan Z., Pencina M., Avillach P., Cai T., Hong C. Robust Automated Harmonization of Heterogeneous Data Through Ensemble Machine Learning: Algorithm Development and Validation Study. *JMIR Med Inform* 2025 Jan 22; 13:e54133.
3. [[ADEPT]](https://github.com/duke-harmonization/ADEPT) Hickey J., Henao R., Wojdyla D., Pencina M., Engelhard M. Adaptive Discretization for Event PredicTion (ADEPT) in *Proceedings of the International Conference on Artificial Intelligence and Statistics* (2024).
4. [[TransBalance]](https://github.com/duke-harmonization/Transbalance) Hong C., Liu M., Wojdyla D.M., Hickey J., Pencina M., Henao R. Trans-Balance: Reducing demographic disparity for prediction models in the presence of class imbalance. *Journal of biomedical informatics*. 2024 Jan 1;149:104532.
5. [[PMP]](https://precision.heart.org/duke-ninds) Mallya, P., Stevens, L.M., Zhao, J., Hong, C., Henao, R., Economou-Zavlanos, N., Wojdyla, D.M., Schibler, T., Manchanda, V., Pencina, M.J. and Hall, J.L. Facilitating harmonization of variables in Framingham, MESA, ARIC, and REGARDS studies through a metadata repository. *Circulation: Cardiovascular Quality and Outcomes*. 2023 16(11), p.e009938.
6. [[RALIF]](https://github.com/duke-harmonization/Active-Learning) Xia M., Henao R. Reliable active learning via influence functions. *Transactions on Machine Learning Research*. 2023.
7. [[SGHP]](https://github.com/duke-harmonization/sghp) Isik Y., Chapfuwa P., Davis C., Henao R. Hawkes Process with Flexible Triggering Kernels in *Proceedings of the Machine Learning for Healthcare Conference* (2023).
8. [[Evaluation]](https://github.com/duke-harmonization/CensoredMAE) Qi S.A., Kumar N., Farrokh M., Sun W., Kuan L.H., Ranganath R., Henao R., Greiner R. An effective meaningful way to evaluate survival models in *Proceedings of the 40th International Conference on Machine Learning*. (2023).
9. [[Predictive Accuracy]](https://github.com/duke-harmonization/stroke-risk-prediction-models) Hong C., Pencina M.J., Wojdyla D.M., Hall J.L., Judd S.E., Cary M., Engelhard M.M., Berchuck S., Xian Y., D’Agostino R., Howard G., Kissela B., and Henao R. Predictive Accuracy of Stroke Risk Prediction Models Across Black and White Race, Sex, and Age Groups. *JAMA*. 2023 Jan 24;329(4):306-17.
10. [[Latent ODE]](https://github.com/duke-harmonization/structured_latent_ODEs) Chapfuwa, P., Rose, S., Carin, L., Meeds, E. and Henao, R. Capturing Actionable Dynamics with Structured Latent Ordinary Differential Equations in *Proceedings of the 38th Conference on Uncertainty in Artificial Intelligence* (2022).
11. [[MCM]](https://github.com/duke-harmonization/dnmc) Engelhard, M. and Henao, R. Disentangling Whether from When in a Neural Mixture Cure Model for Failure Time Data in *Proceedings of The 25th International Conference on Artificial Intelligence and Statistics* (2022).
12. [[GIL]](https://github.com/duke-harmonization/gradient-importance-learning) Gao, Q., Wang, D., Amason, J. D., Yuan, S., Tao, C., Henao, R., Hadziahmetovic, M., Carin, L. and Pajic, M. Gradient Importance Learning for Incomplete Observations in *Proceedings of the 10th International Conference on Learning Representations* (2022).
13. [[SC]](https://github.com/duke-harmonization/counterfactual_survival_analysis) Chapfuwa, P., Assaad, S., Zeng, S., Pencina, M., Carin, L. and Henao, R. Enabling Counterfactual Survival Analysis with Balanced Representation in *Proceedings of the ACM Conference on Health, Inference, and Learning* (2021).
14. [[ECRT]](https://github.com/duke-harmonization/ECRT) Chen, J., Xiu, Z., Goldstein, B., Henao, R., Carin, L. and Tao, C. Supercharging Imbalanced Data Learning With Causal Representation Transfer in *Advances in Neural Information Processing Systems 35* (2021).
15. [[VIE]](https://github.com/duke-harmonization/VIE) Xiu, Z., Tao, C., Gao, M., Davis, C., Goldstein, B. and Henao, R. Variational Disentanglement for Rare Event Modeling in *Proceedings of the 35th AAAI Conference on Artificial Intelligence* (2021).

## Support

This research is by NIH/NINDS R61-NS120246.

<img src="https://user-images.githubusercontent.com/10777813/182640577-aeb1236b-186c-4fbe-aecf-1d0633f83860.png" width="200"> <img src="https://user-images.githubusercontent.com/10777813/182640606-fe32e791-eeb3-42d8-958a-350a31527abc.png" width="200">
