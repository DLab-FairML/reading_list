# reading_list

# Renata 
- [ ] Add your recommended articles below

# Avery 
- [ ] Add your recommended articles below

## FairML in general 

- Matt J. Kusner, Joshua R. Loftus, Chris Russell, Ricardo Silva, [Counterfactual Fairness](https://arxiv.org/abs/1703.06856)

- Maximilian Kasy & Rediet Abebe. [Fairness, Equality, and Power in Algorithmic Decision-Making](https://www.cs.cornell.edu/~red/fairness_equality_power.pdf)
  - [Slides](https://maxkasy.github.io/home/files/slides/fairness_equality_power_slides_kasy.pdf)
    - Fairness = !discrimination?
      - Problems: (1) legitimize inequalities justified by "merit", (2) narrowly blacketed; only consider differences, (3) only consider between-group differences 
      - Alternatives: (1) What is the causal impact of the introduction of an algorithm on inequality? (2) Who has the power to pick the objective function of an algorithm?
    - Fairness definitions depend on (1) Treatment (job, credit, incarceration, school admission), (2) A note of merit M (marginal product, credit default, recidivism, test performance), (3) Protected categories A (race, ethnicity, gender) -> become a constrained optimization problem 
    - Reasons for bias: (1) preference-based discrimination, (2) mis-measurement, (3) statistical discrimination 

- Pedro Saleiro, Rayid Ghani et. al. [Aequitas: A Bias and Fairness Audit Toolkit](https://arxiv.org/pdf/1811.05577.pdf)

- Ramaravind Kommiya Mothilal, Amit Sharma, Chenhao Tan. [Explaining Machine Learning Classifiers through Diverse Counterfactual Explanations](https://arxiv.org/abs/1905.07697)

  - [Python package](https://github.com/interpretml/DiCE)


## Bias and NLP

- Dirk Hovy & Shannon L. Spruit. [The Social Impact of Natural Language Processing](https://www.aclweb.org/anthology/P16-2096.pdf)
  - Motivation: "Instead, we want to move beyond privacy in our ethical analysis and look at the wider social impact NLP may have. In particular, we want to explore the impact of NLP on social justice, i.e., equal opportunities for individuals and groups (such as minorities) within society to access resources, get their voice heard, and be represented in society." (p.591)
  - New terms: "exclusion, overgeneralization, bias confirmation, topic under- and overexposure, and dual use." (p.592)
    - Exclusion: demographic bias (data side-effect) 
    - Overgeneralization & Bias confirmation: false positives -> overgeneralization & bias confirmation (modeling side-effect) "Would a false answer would be worse than no answer?"
    - Topic underexposure -> availability heuristics -> discrimination
    - Topic overexposure -> Negative impact evaluation 
    - Dual use (unintended consequences)
