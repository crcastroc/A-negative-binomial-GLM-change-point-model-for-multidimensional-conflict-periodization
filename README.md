Paper- A negative binomial GLM change-point model for multidimensional conflict periodization

Introduction

Internal armed conflicts generate highly variable and non-stationary patterns of violence, making objective temporal characterization difficult. Reliable periodization is essential for understanding conflict evolution and supporting evidence-based decision-making; however, traditional approaches often rely on subjective judgments or arbitrary temporal units. Previous models, such as those based on Poisson processes or Gaussian distributions, frequently fail because they do not capture the large fluctuations and overdispersion—where variance substantially exceeds the mean—typical of violent events in these contexts.

Beyond statistical limitations, conventional analyses tend to focus exclusively on deaths, ignoring other dimensions such as displacement or coercive control. They also often utilize absolute victim counts, neglecting long-term demographic shifts and providing a limited characterization of actual population-level risk. To address these gaps, the sources propose a multidimensional statistical framework that utilizes a Negative Binomial Generalized Linear Model (NB-GLM) to automatically detect change points in the escalation and de-escalation of violence.

Materials and Methods

The study was based on official records from the National Center for Historical Memory (CNMH) of Colombia, spanning from January 1958 to December 2022 with monthly resolution. The analyzed database comprised over 352,786 documented cases of collective violence and 411,934 victims, with events classified into selective and indiscriminate violence. For each category, time series were constructed to integrate multiple dimensions: number of cases versus number of victims, and absolute figures versus rates adjusted for national population size.

Methodologically, a weighted Kolmogorov-Smirnov (KS) homogeneity test was first applied to formally confirm the existence of structural changes in the distribution of violence. Subsequently, change points were estimated using the Pruned Exact Linear Time (PELT) algorithm, which allows for globally optimal and efficient segmentation. The final model employs an NB-GLM structure that separates large-scale temporal evolution (escalation and de-escalation) from changes driven by demographic dynamics, using the Bayesian Information Criterion (BIC) to select model complexity.

Results and Discussion

The results demonstrate that the Negative Binomial model is superior to Poisson and Gaussian alternatives, achieving substantially lower AIC and BIC values across all segments of the Colombian conflict. The analysis identified multiple statistically coherent regimes, revealing that violence evolves asynchronously depending on the dimension analyzed; for example, selective and indiscriminate violence present distinct regime boundaries. Furthermore, the proposed model locates regime changes significantly closer to empirical violence peaks, with an average error of 19 months compared to 39 months for the baseline model.

In the discussion, it is highlighted that explicitly modeling escalation and de-escalation trends produces more parsimonious segmentations and avoids over-segmentation caused by stochastic noise. Although the study acknowledges limitations such as the independent estimation of each indicator and the use of constant dispersion, the NB-GLM framework succeeds in capturing transitions that were previously hidden in unidimensional approaches. Finally, the sources conclude that this method provides a solid statistical foundation for decision support and for understanding conflict as a multidimensional process influenced by demographic exposure.

