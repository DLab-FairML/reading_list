
- If you want to hyperlink a paper or book, do [book] (hrf) or [paper] (hrf) and remove the space between [ ] ( ).
- Hyperlink only legally accessible papers and books.

# Reading list for the bias and fiarness in ML

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

## Public Opinion and AI System

- Min Kyung Lee. [Understanding perception of algorithmic decisions: Fairness, trust, and emotion in response to algorithmic management](https://journals.sagepub.com/action/doSearch?target=default&ContribAuthorStored=Lee%2C+Min+Kyung)

## Participatory Approaches to Machine Learning

- [Participatory Approaches to Machine Learning ICML2020 Workshop](https://participatoryml.github.io/) (July 17)

  - [Patton, Desmond U., William R. Frey, Kyle A. McGregor, Fei-Tzin Lee, Kathleen McKeown, and Emanuel Moss. "Contextual Analysis of Social Media: The Promise and Challenge of Eliciting Context in Social Media Posts with Natural Language Processing." In Proceedings of the AAAI/ACM Conference on AI, Ethics, and Society, pp. 337-342. 2020.](https://dl.acm.org/doi/pdf/10.1145/3375627.3375841?casa_token=yZOdrz73Lu4AAAAA:NXBAFttihwjDfo2WRF78Q8F8jZb182VMm_4gVZneDEtbuHN0QkwsAJpFIwJ4GofpH-lnmQd6tD4)
      - CASM approach considers and critiques  the gap between inadequacies in natural language processing tools and differences in geographic, cultural, and age-related variance of social media use and communication.
      - If an NLP system is not trained to understand context, it is unlikely the system will be able to accurately infer and interpret the meaning of the data
      - Data training workflow
          - Step1: Baseline interpretation (training session)
          - Step2: Annotation process
          - Step3: Interpretation and contextual analysis assessment
          - Step4: Labeling
          - Step5: Community validationg and reconciliation

## Popular Literature

### Books

- Cathy O'Neil. [Weapons of Math Destruction](https://www.amazon.com/dp/B01LDFCP0S/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1).

### Articles
