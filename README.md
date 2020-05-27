# EC 607, Spring 2020

Welcome to **Economics 607: Econometrics III** (Spring 2019) at the University of Oregon (taught by Dr. [Ed Rubin](https://edrub.in)).

## Schedule

**Lecture** Monday and Wednesday 10:00pm–11:50pm, Zoom ([See Canvas](https://canvas.uoregon.edu/courses/155809))

**Lab** Friday 12:00pm–12:50pm, Zoom ([See Canvas](https://canvas.uoregon.edu/courses/155809))

**Office hours**

- **[Ed Rubin](https://edrub.in)** TBD, Zoom ([See Canvas](https://canvas.uoregon.edu/courses/155809))
- **[Colleen O'Briant](https://economics.uoregon.edu/profile/cobriant/)** TBD, Zoom ([See Canvas](https://canvas.uoregon.edu/courses/155809))

## Books

We will mainly use two books.

**[Mostly Harmless Econometrics: An Empiricist's Companion](http://www.mostlyharmlesseconometrics.com/)** *(MHE)*
<br>*by Angrist and Pischke*
<br>Your new best friend. Read it.


**[Microeconometrics](https://www.cambridge.org/us/academic/subjects/economics/econometrics-statistics-and-mathematical-economics/microeconometrics-methods-and-applications?format=HB&isbn=9780521848053)** *(C&T)*
<br>*by Cameron and Trivedi*
<br>Also very readable and accessible.

Runner up (the standard):

**[Econometric Analysis](https://www.pearson.com/us/higher-education/program/Greene-Econometric-Analysis-8th-Edition/PGM334862.html)** *(Greene)*
<br>*by Greene*
<br>Encyclopedic resource for all (most?) of the questions MHE does not answer.

## Lecture slides

*Note:* The linked slides (below) are `.html` files that will only work properly if you are connected to the internet. If you're going off grid (camping + metrics?), grab the PDFs. You'll miss out on gifs and interactive plots, but the equations will actually show up. I've removed the within-slide (incremental) pauses in the *(no pauses)* PDF slides.

The content of the lectures mainly follows *MHE* and [Michael Anderson](https://are.berkeley.edu/~mlanderson/ARE_Website/Home.html)—with additional inspiration from [Max Auffhammer](https://www.auffhammer.com) and many other sources.

*Another note on the notes:* I create the slides with [`xaringan`](https://github.com/yihui/xaringan/wiki) in [R](cran.r-project.org). Thanks to [Grant McDermott](grantmcdermott.com/) for encouraging me to make this switch.

**[Lecture 01: Research + R + You = 💖](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/01-research-r/01-research-r.html)**

1. An introduction to empirical research via applied econometrics.
1. R: Light introduction—objects, functions, and help.

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/01-research-r/01-research-r.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/01-research-r/01-research-r.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/01-research-r/01-research-r-nopause.pdf) |
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/01-research-r/01-research-r.Rmd)
<br>**Readings:** MHE preface + MHE chapter 1

**[Lecture 02: The Experimental Ideal](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/02-the-ideal/02-the-ideal.html)**

1. Neyman potential outcomes framework (Rubin causal model)
1. Selection bias and experimental variation in treatment
1. R: Object types/classes and package management.

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/02-the-ideal/02-the-ideal.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/02-the-ideal/02-the-ideal.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/02-the-ideal/02-the-ideal-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/02-the-ideal/02-the-ideal.Rmd)
<br>**Readings:** MHE chapter 2

**[Lecture 03: Why Regression?](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/03-why-regression/03-why-regression.html)**

1. What's the big deal about least-squares (population) regression?
2. What does the CEF tell us?
3. How does least-squares regression relate to the CEF?

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/03-why-regression/03-why-regression.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/03-why-regression/03-why-regression.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/03-why-regression/03-why-regression-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/03-why-regression/03-why-regression.Rmd)
<br>**Readings:** MHE chapter 3.1

**[Lecture 04: Inference and Simulation](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/04-inference/04-inference.html)**

1. How do we move from populations to samples?
2. What matters for drawing basic statistical inferences about the population?
3. How can we learn about inference from simulation?
4. How do we run (parallelized) simulations in R?

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/04-inference/04-inference.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/04-inference/04-inference.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/04-inference/04-inference-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/04-inference/04-inference.Rmd)
<br>**Readings:** MHE chapter 3

**[Lecture 05: Regression Stuff](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/05-regression-stuff/05-regression-stuff.html)**

1. Saturated models
1. When is regression causal?
1. The conditional-independence assumption

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/05-regression-stuff/05-regression-stuff.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/05-regression-stuff/05-regression-stuff.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/05-regression-stuff/05-regression-stuff-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/05-regression-stuff/05-regression-stuff.Rmd)
<br>**Readings:** Still MHE chapter 3

**[Lecture 06: Controls](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/06-controls/06-controls.html)**

1. Omitted-variable bias
1. Good and bad controls

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/06-controls/06-controls.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/06-controls/06-controls.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/06-controls/06-controls-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/06-controls/06-controls.Rmd)
<br>**Readings:** Still MHE chapter 3

**[Lecture 07: Matching](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/07-matching/07-matching.html)**

1. Matching estimators: Nearest neighbor and kernel
1. Propensity-score methods: Regression control, treatment-effect heterogeneity, blocking, weighting, *doubly robust*

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/07-matching/07-matching.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/07-matching/07-matching.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/07-matching/07-matching-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/07-matching/07-matching.Rmd)
<br>**Readings:** MHE chapter 3 + C&T section 25.4

**[Lecture 08: Instrument Variables](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/08-iv/08-iv.html)**

1. General research designs
1. Instrumental variables
1. Two-stage least squares
1. Heterogeneous treatment effects and the LATE

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/08-iv/08-iv.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/08-iv/08-iv.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/08-iv/08-iv-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/08-iv/08-iv.Rmd)
<br>**Readings:** MHE chapter 4 + C&T sections 4.8–4.9

**[Lecture 09: Regression Discontinuity](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/09-rd/09-rd.html)**

1. Sharp regression discontinuities
1. Fuzzy regression discontinuities
1. Graphical analyses

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/09-rd/09-rd.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/09-rd/09-rd.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/09-rd/09-rd-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/09-rd/09-rd.Rmd)
<br>**Readings:** MHE chapter 6 + C&T sections 25.6

**[Lecture 10: Inference: Clustering](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/10-clustering/10-clustering.html)**

1. General inference
1. Moulton
1. Cluster-robust standard errors

**Note formats:** [.html](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/10-clustering/10-clustering.html) |
[.pdf](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/10-clustering/10-clustering.pdf) |
[.pdf (no pauses)](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/10-clustering/10-clustering-nopause.pdf) | 
[.Rmd](https://raw.githack.com/edrubin/EC607S20/master/notes-lecture/10-clustering/10-clustering.Rmd)
<br>**Readings:** MHE chapter 8

**Lecture 11: Inference: Resampling and Randomization**

1. Resampling
1. The bootstrap
1. Permutation tests (Fisher)
1. Randomization inference (Neyman-Pearson)

**Readings:** MHE chapter 6 + C&T sections 25.6

**Lecture 12:** There's more?

## Lab slides

*Note:* From previous iteration of our class.

**[Lab 01: R Intro/Review](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01RBasics.html)**

1. Object types/classes/structures
1. Package management
1. Math and stat. in R
1. Indexing

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01RBasics.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01RBasics_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01RBasics.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01RBasics_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01RBasics.Rmd)
<br>
**Solutions:**
[.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01Solution.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/01RBasics/01Solution.pdf)

**[Lab 02: Data in/and R](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/02RData/02RData.html)**

1. Data frames
1. Data work with `dplyr`

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/02RData/02RData.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/02RData/02RData_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/02RData/02RData.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/02RData/02RData_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/02RData/02RData.Rmd)

**[Lab 03: RStudio + Data i/o with R](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/03RInput/03RInput.html)**

1. RStudio
1. Getting data into and out of R

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/03RInput/03RInput.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/03RInput/03RInput_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/03RInput/03RInput.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/03RInput/03RInput_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/03RInput/03RInput.Rmd)

**[Lab 04: Regression in R](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/04RReg/04RReg.html)**

1. `lm()` and `lm` objects
1. `estimatr` and `lm_robust()`
1. Other regressions, *e.g.*, `glm()`

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/04RReg/04RReg.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/04RReg/04RReg_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/04RReg/04RReg.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/04RReg/04RReg_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/04RReg/04RReg.Rmd)

**[Lab 05: Plotting in R](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/05RPlot/05RPlot.html)**

1. Default `plot()` methods
1. `ggplot2`

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/05RPlot/05RPlot.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/05RPlot/05RInput_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/05RPlot/05RPlot.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/05RPlot/05RPlot_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/05RPlot/05RPlot.Rmd)

**[Lab 06: Simulation in R](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/06RSim/06RSim.html)**

1. General simulation strategies
1. Simulating IV in finite samples

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/06RSim/06RSim.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/06RSim/06RSim_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/06RSim/06RSim.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/06RSim/06RSim_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/06RSim/06RSim.Rmd)

**[Lab 07: Miscellaneous R Tips and Tricks](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/07RMisc/07RMisc.html)**

1. The `apply` family
1. `for()` loops
1. Lists
1. Logical vectors and `which()`

**Note formats:** [.html](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/07RMisc/07RMisc.html) | [.html (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/07RMisc/07RMisc_NoPause.html) | [.pdf](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/07RMisc/07RMisc.pdf) | [.pdf (no pause)](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/07RMisc/07RMisc_NoPause.pdf) | [.Rmd](https://raw.githack.com/edrubin/EC525S19/master/NotesLab/07RMisc/07RMisc.Rmd)

## Problem sets

2–5 problem sets combining econometric theory and R.

[**Problem set 1**](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/001/001-problems.pdf)

[**Problem set 2**](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/002/002-problems.pdf)

[**Problem set 3**](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/003/003-problems.pdf) with [dataset 1](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/003/data/2mile.dta), [dataset 2](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/003/data/allcovariates.dta), [dataset 3](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/003/data/allsites.dta), and [more data](https://raw.githack.com/edrubin/EC607S20/master/problem-sets/003/data/sitecovariates.dta).

## Project

Building a research project/proposal.

Step 1: **Research question (causal relationship of interest) and motivation.**

- *Assignment:* Pitch a project—including the causal question of interest, the motivation, and (optional) how you could answer the question.
- This project should be something you could turn into a legitimate research project.
- Length: Between 2 sentences and 2 paragraphs (think *abstract*—read abstracts if necessary).

**Due 15 April 2020 ([Canvas](https://canvas.uoregon.edu))** 

[Step 2: **Project proposal**](https://raw.githack.com/edrubin/EC607S20/master/project/002/project-002.pdf)

**Due 27 May 2020 ([Canvas](https://canvas.uoregon.edu))** 

Step 3: **Presentation of project pitch**
<br>Includes discussion from 2 peers

## Practice problems

1. Inference and simulation
1. Matching
1. Instrumental variables
1. Regression discontinuity
1. Inference: Clustering and resampling

## Exams

**Final** There will definitely be a take-home final exam.

  **Midterm** We *may* have a take-home midterm exam.

## Grades

**Assignments** Each assignment is worth 10% of your course grade.

**Project** The parts of the group project are jointly worth 25% of your course grade.

**Exams** The exams will cover the remainder of the points for the course.

- If there are multiple exams, then they will split the remainder equally.
- *Example:* With 3 assignments, the residual = 100% - (3×10% + 25%) = 45%.
    - If we only have a final exam, it would be worth 45%.
    - If we have a final exam *and a midterm exam*, each would be worth 22.5%.

## Resources

**Metrics books**

- [Hayashi's *Econometrics*](https://press.princeton.edu/titles/6946.html)
- [Kennedy](https://www.wiley.com/en-us/A+Guide+to+Econometrics)
- [*Mastering 'Metrics*](http://masteringmetrics.com/) (undergrad version of *Mostly Harmless*)
- [Stock and Waston](https://www.pearson.com/us/higher-education/product/Stock-Introduction-to-Econometrics-3rd-Edition/9780138009007.html)
- [Wooldridge ("Baby")](https://www.cengage.com/c/introductory-econometrics-a-modern-approach-6e-wooldridge/9781305270107)
- [Wooldridge (Adult?)](https://mitpress.mit.edu/books/econometric-analysis-cross-section-and-panel-data-second-edition)

**R resources**

- [RStudio: *Finding Your Way To R*](https://education.rstudio.com/learn/)
- [My EC525 Economics & Machine Learning Course at UO](https://github.com/edrubin/ec525)
- [Grant McDermott's *Data Science of Economists* course](https://github.com/uo-ec607)
- [DataCamp's Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r)
- [*R for Data Science*](https://r4ds.had.co.nz/)
- [*Advanced R*](http://adv-r.had.co.nz/)

**Metrics and R**

- [Website from last year](https://github.com/edrubin/EC525S19)
- [Section notes from a previous PhD-level class](https://edrub.in/ARE212).
- [Lecture notes from a previous undergrad class](https://github.com/edrubin/EC421W20).
