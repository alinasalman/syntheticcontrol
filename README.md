## Causal Inference and Synthetic Control for Evaluating Policy Impact on Conflict Resolution 

This repository contains the Synthetic Control Method (SCM) implementation and analysis for causal inference. SCM is widely used to estimate the effect of an intervention or treatment when randomized control trials are not feasible. This method constructs a synthetic version of the treated unit as a weighted combination of control units.


### Estimation of Treatment Effects and Counterfactual Analysis
#### Propensity Score and Genetic Matching
• Applied propensity score matching and genetic matching methods on the Darfur violence dataset to estimate treatment effects for conflict resolution policies.

• Controlled for selection bias using the Rubin Causal Model, ensuring robust causal inference in evaluating policy effectiveness.

• Utilized statistical programming tools to preprocess data, compute propensity scores, and match treated and control units based on covariates.

#### Synthetic Control Model for Economic Outcomes
• Developed a synthetic control model using the Synth package to create counterfactual predictions for economic outcomes in Baleares (Islas) following a post-intervention policy.

• Designed the synthetic counterpart of Baleares from a weighted combination of control units to analyze the economic impact of the intervention.

• Visualized pre- and post-intervention trends, quantified intervention effects, and performed placebo tests to assess the validity of results.


### Key Skills and Tools:
• Synthetic Control Method

• R (Synth package), Python

• Rubin Causal Model
