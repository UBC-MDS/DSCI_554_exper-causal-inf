Welcome to DSCI 554: Experimentation and Causal Inference
============================

This frequentist course focuses on statistical evidence from randomized experiments versus observational studies along with applications of randomization, e.g., A/B testing for website optimization.

## High-Level Goals

By the end of the course, students are expected to:

- Distinguish between experimentally-generated data and observational data, with particular reference to the strength of ensuing statistical conclusions regarding causality.
- Fit and interpret regression models for observational data, with particular reference to adjustment for potential confounding variables.
- Apply the principle of “block what you can, randomize what you cannot” in designing an A/B testing experiment.

## Assessments

This is an **assignment-based course**. The following deliverables will determine your course grade:

| Assessment       | Weight  | 
| :---:            | :---:   |
| Lab Assignment 1 | 12%     |
| Lab Assignment 2 | 12%     |
| Lab Assignment 3 | 12%     |
| Lab Assignment 4 | 12%     |
| Quiz 1           | 25%     |
| Quiz 2           | 25%     |
| Lecture Attendance ([iClicker](https://student.iclicker.com/#/login))   | 2%     |

## Lecture Schedule

This course occurs during **Block 6** in the 2023/24 school year.

Course notes can be accessed [**here**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/README.html). Typically, you should review these notes before each lecture. Moreover, there is optional reading material.

| Lecture | Topic | Optional Reading Material |
|:---------:|--------|-----------------|
| 1 | [**Multiple Comparisons**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture1_multiple_comparisons.html) | <ul><li>[This chapter](http://www.biostathandbook.com/multiplecomparisons.html) from Handbook of Biological Statistics by McDonald |
| 2 | [**Confounding and Randomized versus Non-randomized Studies**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture2_simpson_confounding.html) | <ul><li>section 1.3.5 - 1.5.2, inclusive (pages 19 - 26), from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Improving Library User Experience with A/B Testing: Principles and Process](https://quod.lib.umich.edu/w/weave/12535642.0001.101?view=text;rgn=main)</li></ul> |
| 3 | [**Randomization and Blocking**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture3_randomization_and_blocking.html) | <ul><li>[Refresher on ANOVA](http://www.biostathandbook.com/twowayanova.html) from Handbook of Biological Statistics</li><li>section 1.4 Experiments from [OpenIntro Statistics](https://leanpub.com/openintro-statistics)</li></ul> |
| 4 | [**More Blocking and Power**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture4_more_blocking_and_power.html) | <ul><li>section 5.4 (pages 239 - 245), from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li><li>[Stopping rules and regression to the mean](https://www.statisticsdonewrong.com/regression.html)</li></ul> |
| 5 | [**More Power and Early Stopping in A/B Testing**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture5_more_power_early_stopping.html) | <ul><li>[Peeking in A/B testing at Etsy](https://codeascraft.com/2018/10/03/how-etsy-handles-peeking-in-a-b-testing/)</li></ul> |
| 6 | [**Observational Data: Stratifying and Modelling**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture6_obs_stratifying_modelling.html) |  <ul><li>[Confounding in Observational Studies Explained](https://benthamopen.com/contents/pdf/TOEPIJ/TOEPIJ-5-18.pdf)</li><li>section 8.4 (pages 386 - 395)  from [OpenIntro Statistics](https://drive.google.com/file/d/0B-DHaDEbiOGkc1RycUtIcUtIelE/view)</li></ul> |
| 7 | [**Observational Data: Different Sampling Schemes**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture7_obs_sampling_schemes.html) | <ul><li>[BU SPH on case-control sampling](https://sphweb.bumc.bu.edu/otlt/MPH-Modules/EP/EP713_Case-Control/EP713_Case-Control_print.html)</li><li>[Basics of observational study design](reading-resources/sampling-designs-bmj.pdf)</li></ul> |
| 8 | [**Matched Case-Control Scheme, Ordinal Regressors, and Final Wrap-Up**](https://ubc-mds.github.io/DSCI_554_exper-causal-inf/notes/lecture8_match_constrasts_wrapup.html) | |

See the [lecture learning objectives](lecture-learning-objectives.md) for a detailed breakdown of lecture-by-lecture learning objectives.

## Reference Material

* Seltman HJ, [Experimental Design and Analysis](http://www.stat.cmu.edu/~hseltman/309/Book/Book.pdf), 2015.
* Oehlert GW, [A First Course in Design and Analysis of Experiments](http://users.stat.umn.edu/~gary/book/fcdae.pdf), 2010.
* O’Neil, Cathy and Schutt, Rachel. "Causality," Ch. 11 of Doing Data Science: Straight Talk from the Frontline, O’Reilly Media, 2013.
* Tang, Diane, et al. "Overlapping Experiment Infrastructure: More, Better, Faster Experimentation." Proceedings of the 16th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, ACM, 2010.

Further reading:

* Work by Judea Pearl, such as "The Book of Why".

## Recommended Course Reviews

This course is taught in `R` (we will follow the [`tidyverse` style guide](https://style.tidyverse.org/index.html)) and `Stan` with a reasonable mathematical, statistical, and programming basis. We strongly recommend reviewing the following courses:

- [*DSCI 551: Descriptive Statistics and Probability for Data Science*](), for basic statistical and probabilistic concepts, and familiarity with the mathematical notation.
- [*DSCI 552: Statistical Inference and Computation I*](https://github.com/UBC-MDS/DSCI_552_stat-inf-1), for statistical inference concepts with a frequentist approach.
- [*DSCI 561: Regression I*](https://github.com/UBC-MDS/DSCI_561_regr-1), for Ordinary Least-squares (OLS).
- [*DSCI 562: Regression II*](https://ubc-mds.github.io/DSCI_562_regr-2/README.html), for generalized linear models (GLMs).
- [*DSCI 531: Data Visualization I*](https://github.com/UBC-MDS/DSCI_531_viz-1), for plotting tools using the package `ggplot2`.

## Policies

See the general [MDS policies](https://ubc-mds.github.io/policies/).

## Attribution
    
The course is built upon previous years' materials developed by previous instructors.

## License

© 2024 G. Alexi Rodríguez-Arelis, Daniel Chen, Benjamin Bloem-Redd, Tiffany Timbers, and Vincenzo Coia

Software licensed under [the MIT License](https://spdx.org/licenses/MIT.html), non-software content licensed under [the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). See the [license file](LICENSE.md) for more information.
