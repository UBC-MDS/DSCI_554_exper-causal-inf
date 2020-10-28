# DSCI 554: Experimentation and Causal Inference

Statistical evidence from randomized experiments versus observational studies. Applications of randomization, e.g., A/B testing for website optimization.

## Course Learning Outcomes

By the end of the course, students are expected to be able to:

1. Distinguish between experimentally-generated data and observational data, with particular reference to the strength of ensuing statistical conclusions.
2. Fit and interpret regression models for observational data, with particular reference to adjustment for potential confounding variables. 
3. Apply the principle of “block what you can, randomize what you cannot” in designing an A/B testing experiment.
4. Choose appropriately between fixed-effect and random-effect regression models.


## Lecture Schedule

| Lecture | Topic | Pre-Readings |
|---------|-------|------|
| 1 | Multiple comparisons and Bonferonni correction. | [This chapter](http://www.biostathandbook.com/multiplecomparisons.html) from Handbook of Biological Statistics by McDonald |
| 2 | Confounding (Simpson's paradox), observation versus randomized intervention demos, A/B testing as a special instance of  randomized experimentation. | <ul><li>section 1.3.5 - 1.5.2, inclusive (pages 19 - 26), from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Improving Library User Experience with A/B Testing: Principles and Process](https://quod.lib.umich.edu/w/weave/12535642.0001.101?view=text;rgn=main)</li></ul> |
| 3 | Regression/ANOVA applied to data from a randomized experiment.   Experimental design terminology, blocking, statistical properties of inference in a randomized experiment. |
| 4 | More blocking. Power calculations (in a click-thru context). The possibility of early stopping. | <ul><li>section 5.4 (pages 239 - 245), from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Stopping rules and regression to the mean](https://www.statisticsdonewrong.com/regression.html)</li></ul> |
| 5 | Continual monitoring and early stopping, principled peeking with Bonferonni correction. |
| 6 | Observational study motivations. Association marginally, versus stratified. Logistic regression as model-based alternative to stratification. Conditions under which "causal spin" is allowed. Prediction vs. explanation. |  <ul><li>section 8.4 (pages 386 - 395)  from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Confounding in Observational Studies Explained](https://benthamopen.com/contents/pdf/TOEPIJ/TOEPIJ-5-18.pdf)</li></ul> |
| 7 | Plasmode simulation. Regular cohort versus (unmatched) case-control studies. Matched pairs. |
| 8 | Big picture issues around confounding, take-away themes. |


## General Reference Material

* Seltman HJ, [Experimental Design and Analysis](http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf), 2015
* Oehlert GW, [A First Course in Design and Analysis of Experiments](http://users.stat.umn.edu/~gary/book/fcdae.pdf), 2010.
* O’Neil, Cathy and Schutt, Rachel. "Causality," Ch. 11 of Doing Data Science: Straight Talk from the Frontline, O’Reilly Media, 2013.
* Tang, Diane, et al. "Overlapping Experiment Infrastructure: More, Better, Faster Experimentation." Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, ACM, 2010.

Further reading:

* Work by Judea Pearl, such as "The Book of Why".

## Policies

Please see the general [MDS policies](https://ubc-mds.github.io/policies/).


## Lecture-Specific Learning Goals

1\. Multiple comparisons and Bonferroni correction.  
By the end of the lecture students will be able to:

* Explain the macro-properties of carrying out many hypothesis tests in the context of a single dataset.
* Use Bonferroni correction to alter the macro-properties when carrying out many hypothesis tests.

2\. Confounding, observation versus intervention.  
By the end of the lecture students will be able to:

* Give a definition of a confounding variable.
* Produce an instance of Simpson's paradox.
* Argue why evidence from a randomized study is of higher grade than evidence from an observational study.

3\. Regression-based analysis of experimental data.  
By the end of the lecture students will be able to:

* Fit and interpret appropriate regression models for data from a factorial experiment.
* Relate the corresponding ANOVA table to the substantive question of interest.

4\.  Blocking and power.  
By the end of the lecture students will be able to:

* Propose the use of control, blocking, randomization, and replication in the design of an experiment.
* Relate the statistical notion of power to the real-world utility of an experiment.

5\.  More on randomized experiments.  
By the end of the lecture students will be able to:  

* Comment on nuances of randomized experiments that arise specifically for website optimization problems.
* Determine an adequate sample size (experiment duration) for such problems.
* Relate the danger of "early stopping" of experiments.

6\.  Confounding in observational data.  
By the end of the lecture students will be able to:

* Give a definition of a set of variables that controls for confounding.
* Analyze stratified observational data.
* Interpret regression models fit to observational data.
* Supply appropriate caveats for causal claims from fitting regression models to observational data.
* Comment on the differing goals of regression for prediction versus regression for explanation.

7\. Study designs based on outcome-dependent sampling.  
By the end of the lecture students will be able to: 

* Describe the duality property of odds-ratios.
* Implement a simple case-control analysis.
* Describe how outcome-dependent sampling and matching can simultaneously be used to design a study.

8\. Big picture of data collection and analysis.  
By the end of the lecture students will be able to:

* Critique a range of study designs aimed at a given scientific question.
* Comment on the differing goals of regression for prediction versus regression for explanation.
* Relate the manner in which data are analyzed to the manner in which they are collected.
