# Lecture Learning Objectives

## Lecture 1 - Multiple Comparisons
1. Review frequentist hypothesis testing.
2. Examine the misuse of $p$-values in scientific literature.
3. Demonstrate the misuse of $p$-values via a simulation.
4. Explain the macro-properties of carrying out many hypothesis tests in the context of a single dataset.
5. Use Bonferroni and False Discovery Rate correction to alter the macro-properties when conducting many hypothesis tests.
6. Contrast the Bonferroni correction with the False Discovery Rate.

## Lecture 2 - Confounding and Randomized versus Non-randomized Studies
1. Define the Simpson's paradox.
2. Illustrate the Simpson's paradox occurrence via simulated and real data.
3. Provide a basic guideline to avoid the Simpson's paradox.
4. Provide a definition of a confounding variable.
5. Argue why evidence from a randomized study is of a higher grade than evidence from an observational study.

## Lecture 3 - Randomization and Blocking
1. Explain foundational concepts of statistical design and analysis of experiments in a Data Science context.
2. Relate A/B and A/B/n testings to common statistical models via ordinary least-squares (OLS).
3. Fit and interpret appropriate OLS models from a factorial experiment.
4. Relate the corresponding ANOVA table to the substantive question of interest.
5. Introduce the concept of blocking in experimental design.
6. Contrast a blocking versus a non-blocking experimental model.

## Lecture 4 - More Blocking and Power
1. Propose the use of control, blocking, randomization, and replication in the design of an A/B testing.
2. Contrast the performance of blocking versus non-blocking designs with increasing overall sample sizes.
3. Relate the statistical notion of power to the real-world utility of an experiment in an A/B testing sample size computation.
4. Contrast the performance of blocking versus non-blocking designs in terms of block homogeneity.

## Lecture 5 - More Power and Early Stopping in A/B Testing
1. Comment on nuances of randomized experiments that arise specifically for website optimization problems.
2. Determine an adequate sample size (i.e., experiment duration) for such problems.
3. Apply clever plotting arrangements to communicate power analyses.
4. Relate the danger of "early stopping" to experiments in A/B testing.
5. Analyze the advantages and disadvantages of aggressive and principled peekings in A/B testing.

## Lecture 6 - Observational Data: Stratifying and Modelling
1. Define a set of variables that control for confounding.
2. Analyze stratified observational data.
3. Interpret regression models fittings for observational data.
4. Supply appropriate caveats for causal claims from fitting regression models to observational data.
5. Comment on the differing goals of regression for prediction versus regression for explanation.

## Lecture 7 - Observational Data: Different Sampling Schemes
1. Introduce the use of different sampling schemes in observational studies.
2. Illustrate the concept of the proxy ground truth to assess different sampling schemes.
3. Apply complete simulation studies to a given sampling scheme via the proxy ground truth.
4. Explore the efficiency of the Case-Control sampling scheme via a modified power analysis.

## Lecture 8 - Matched Case-Control Scheme, Ordinal Regressors, and Final Wrap-Up
1. Describe how case-control sampling and matching can simultaneously be used to design a study.
2. Demonstrate the use of contrasts in ordinal regressors.
3. Relate how data are analyzed to how they are collected.