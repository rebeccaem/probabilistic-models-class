# Detailed list / Schedule of lectures / Topics

| |Mon|Wed|Fri|
|-|-|-|-|
|Week 0: Jan 16-20 | No class | 1 (Snow day) | 2 (Introductions) |
|Week 1: Jan 23-27 (Probability) | 3 | 4* | 5† |
|Week 2: Jan 30-Feb 3 (Probability) | 6  | 7**  | 8† (HW1 given) |
|Week 3: Feb 6-10 (Bayesian Statistics)  | 9  | 10  | 11††  |
|Week 4: Feb 13-17 (Bayesian Statistics)  | 12  | 13  | 14† (HW2 given, HW1 due)|
|Week 5: Feb 20-24 (Graphical Models)  | 15  | 16  | 17††  |
|Week 6: Feb 27-Mar 3 (Graphical Models) | 18  | 19  |  20† |
|Week 7: Mar 6-10 (Misc Materials Week)  |  21 | 22  | 23† (HW3 given, HW2 due) |
|Week 8: Mar 13-17 (Markov Networks)  | 24  | 25  | 26†  |
|Week 9: Mar 20-24 (Exact Inference)  | 27 | 28  | 29†*** (review final project; short HW4 given, HW3 due) |
|Week 10: Mar 27-31 (Spring Break) | No class  | No class  | No class  |
|Week 11: Apr 3-7 (Approximate Inference)  | 30  | 31  | 32† |
|Week 12: Apr 10-14 (Information Theory)  | 33  |  34 | 35†† (HW5 given, short HW4 due) |
|Week 13: Apr 17-21 (Prediction)  | 36  |  37 | 38† |
|Week 14: Apr 24-28 (Advanced Graphical Models) |  39 | 40  | 41†† (HW5 due) |
|Week 15: May 1-3 (Final Project Presenations) | 42  | 43 |  No class  |
|Week 16: May 7 (finals slot) Project reports due | -  | -  |  -  |


Legend: 
* `*` means last day to add a class (without instructor approval), `**` is last day to drop a class (without a W), `***` is last day to withdraw from a class (student receives a W)  
* `†` means lab class, `††` means guest lecture

### Detailed content of class, Spring 2023:
1. Snow day, class canceled
2. Introductions
    - syllabus review
    - join slack
    - in-class activity (ICA): meet two people and tell me about them, due in a week
3. Lecture: discrete probability intro
    - probability tables, conditioning (example 1.1.2 Barber)
    - how much information to define probability distribution with d variables, each with k_i states?
4. Lecture:
   - definitions
   - independence and conditional independence
   - motivation for probabilistic graphical models
5. Intro to software tools
   - finish counter-examples from class 4
   - Bernoulli and Binomial distributions
6. Lecture: Continuous distributions
   - multivariate normal (MVN)
   - concentration of measure in high dimensions
7. Lecture: Bayes' Rule
   - likelihood for a physics-based model
8. Lab class
   - MVN
   - start homework 1 together
9. Lecture: Naive Bayes classifier
   - ICA (check Canvas! due in 2 days)
10. Lecture: Learning distributions
   - options: full Bayesian posterior, ML, MAP, moment matching
   - flipping a coin
11. Research talk: Tzu-Chi (Statistical community detection)
12. Lecture: MVN (helpful facts)
13. Lecture: regression, Bayes linear models
14. Lecture: Bayes linear models
    - Equivalence between Gaussian (Laplace) priors and L2 (L1) regression
15. Lab class + lecture
    - Bayesian and deterministic regression
    - basic graph concepts (definitions)
16. Lecture: UGs and DGs
    - Definitions (cliques, trees, loopy, etc)
    - Graph representations: Adjacency matrix, clique matrix
    - BNs as DAGs
17. Guest lecture: Tyler Scott (Google Brain, stochastic embeddings)
18. Lecture: Colliders, statements of C.I., d-separation
19. Class canceled (RM has a cold)
20. Lecture: Markov equivalence
21. Lecture: Determining CI in BNs (and MNs) -- an algorithm
    - 3-node canonical examples
    - Intro to MNs factorization and misconception example
22. Lecture (TCY): 
    - structural learning of a pairwise Markov Random Field using covariance selection
    - the graphical lasso algorithm
23. DEMO 03: Sparse inverse covariance estimation (see [notebook](../DEMOs/demo_03-sparse_inverse_covariance_estimation.ipynb))
24. Lecture: Global, local, pairwise Markov properties
    - Misconception example (simplified, numerical)
    - Separator sets
25. Lecture: Misconception example (simplified, numerical (continued))
26. Lecture:
    - Renormalizing MNs to compute marginals
    - BNs -> MNs
    - Definitions: I-map, D-map, perfect map, minimal I-map
27. Lecture: Efficient (exact) inference in trees
28. Lecture: Exact inference:
    - Message passing
    - Why are loops hard?
    - Transition matrices in state space
29. Lecture: Transition matrices (continued) and Final Project review
30. Lecture: Approximate inference: Sampling, univariate sampling
31. Lecture: Sampling: Rejection, Gibbs, Importance
    - Why sample?
32. Lecture: MCMC, Metropolis-Hastings AND DEMO 04: Markov chain Monte Carlo (see [notebook](../DEMOs/demo_04-markov_chain_monte_carlo.ipynb))
33. Lecture: Entropy, relative entropy, mutual information
    - Why do we express entropy with plog(p)?
34. Lecture: Relative entropy = KL divergence
    - Always non-negative
    - Max ent distributions
    - Start deterministic approximate inference: Laplace approximation
35. Guest lecture: Teo and Rileigh (advanced topics in inference: HMC, Kalman inversion)
36. Lecture: Variational inference and EM algorithm
37. Lecture: MAP estimate for attractive binary MNs equivalent to min-cut


### Coming up:
38. DEMO
39. Rebecca's research using graphical models
40. Advanced graphical models (Laplacian, etc)
41. Guest lecture: Nuttida Rungratsameetaweemana (Probabilistic learning in humans and recurrent neural networks)
42. Final presentations
43. Final presentations


<!-- **22.** Paper discussion -->

