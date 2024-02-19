# links
As it is not possible for an organization to star/follow repositories/organizations, here is a list of potentially interesting github repositories/organizations/users and links to various other things that might be of interest (e.g. guidelines, papers, ...).

## [SCTO Organisation](https://github.com/SwissClinicalTrialOrganisation)
  * [SecuTrial R package](https://github.com/SwissClinicalTrialOrganisation/secuTrialR)
  * [SecuTrial Recipes (Enhanced version)](https://swissclinicaltrialorganisation.github.io/secuTrial_recipes/)
  * [SecuTrial Recipes (GitHub version)](https://github.com/SwissClinicalTrialOrganisation/secuTrial_recipes)


  * [CTU Basel](https://github.com/CTU-Basel)
  
## Stata
  * [markdoc - literate programming for Stata](https://github.com/haghish/markdoc)
  * [weaver - more dynamic docs from Stata (more like a log file though)](https://github.com/haghish/weaver)
  * [github - install Stata packages from github](https://github.com/haghish/markdoc)
  * [rcall - call R from within Stata](https://github.com/haghish/rcall)
  * [ftools - faster variant of Stata's collapse/by/egen (particularly useful for larger datasets)](https://github.com/sergiocorreia/ftools)
  * [gtools - even faster variant of Stata's collapse/by/egen (particularly useful for larger datasets)](https://github.com/mcaceresb/stata-gtools)
  * [fastreshape - a faster variant of reshape (syntax is almost identical to reshape)](https://github.com/mdroste/stata-fastreshape)
  * [World banks iefieldkit - commands for data collection](https://github.com/worldbank/iefieldkit)
  * [World banks ietoolkit - commands for impact evaluation](https://github.com/worldbank/ietoolkit)
  * [World banks stata-linter](https://github.com/worldbank/stata-linter) for tidying code/highlighting poor coding practices
  * [CodeMap - MAC application for examining dependencies in R or Stata analyses](https://github.com/haghish/CodeMap)
  * Power calculation
    * [Simon's two stage design](https://ideas.repec.org/c/boc/bocode/s457081.html)
  * equivalent of R's here package for Stata: [here](https://github.com/korenmiklos/here)
  
#### Validation
  
  * [Stata installation qualification tool](https://www.stata.com/support/installation-qualification/)
  * [Stata and FDA regulatory compliance](https://www.stata.com/stata-fda-compliance/)
  
## R
  * Packages
    * [`Gmisc` - package that includes a nice approach to creating flowcharts](https://github.com/gforge/Gmisc)
      * [Link to vignette](https://cran.r-project.org/web/packages/Gmisc/vignettes/Grid-based_flowcharts.html)
    * [flowchart - Alan's flowchart package - create flowcharts without needing to play around with the layout (much)](https://github.com/CTU-Bern/flowchart)
    * Predictions from mixed models, with SEs are available in the [`AICcmodavg`](https://cran.r-project.org/web/packages/AICcmodavg/index.html) package
    * [`atable`](https://cran.r-project.org/web/packages/atable/index.html) package for baseline tables. Very flexible.
    * [`gtsummary`](http://www.danieldsjoberg.com/gtsummary/index.html) also for baseline tables. Also flexible.
    * [`metamisc`](https://cran.r-project.org/web/packages/metamisc/index.html) 'Facilitate meta-analysis of diagnosis and prognosis research studies. It includes functions to summarize multiple estimates of prediction model discrimination and calibration performance, as described by Debray et al. (2019) <doi:10.1177/0962280218785504>. It also includes functions to evaluate funnel plot asymmetry, as described by Debray et al. (2018) <doi:10.1002/jrsm.1266>. Finally, the package provides functions for developing multivariable prediction models from datasets with clustering. '
    * [`ipcwswitch`](https://www.sciencedirect.com/science/article/abs/pii/S0010482519302082?via%3Dihub) 'Inverse Probability of Censoring Weights to Deal with Treatment Switch in Randomized Clinical Trials'
    * [`margins`](https://cran.r-project.org/web/packages/margins/vignettes/Introduction.html) ports much of Stata's margins function to R
    * Power calculation:
      * [`presize` - precision based sample size calculation](https://github.com/CTU-Bern/presize)
        * [shiny app](https://shiny.ctu.unibe.ch/presize)
      * [Simon's two stage design and various Bayesian approaches for single arm studies](https://cran.r-project.org/web/packages/EurosarcBayes/index.html)
      * [`pmsampsize` for predictive models](https://CRAN.R-project.org/package=pmsampsize)
    * [`ggsurvfit`](https://CRAN.R-project.org/package=ggsurvfit) for KM plots
  * [CodeMap - MAC application for examining dependencies in R or Stata analyses](https://github.com/haghish/CodeMap)
  * [Scottish health/social care - Various stuff including funnel plots](https://github.com/Health-SocialCare-Scotland/R-Resources)
  * [R package template (based on secuTrialR).](https://github.com/CTU-Basel/pkgTemplateR) Includes e.g. continuous integration testing with appveyor and TravisCI. Click the "use this template" button to copy it to a new repo (under a new name) then edit it as required.
  * "Books" etc
    * [Free online resources for learning R](https://cmdlinetips.com/2018/01/free-online-resources-books-to-learn-r-and-data-science/)
    * [Big Book of R](https://www.bigbookofr.com/index.html) - listing of a lot of online R books
    * [Flexible Imputation of Missing Data](https://stefvanbuuren.name/fimd/) book from the author of the `mice` package.
    * [Forecasting: Principles and Practice](https://otexts.com/fpp2/) Uses R for time series analysis and forecasting
    * [Data visualization](https://socviz.co/) lots on ggplot and R
    * [Bayesian inference with INLA](https://becarioprecario.bitbucket.io/inla-gitbook/index.html) covers a LOT of INLA stuff.
    * [Advanced Spatial Modeling with Stochastic Partial Differential Equations Using R and INLA](https://becarioprecario.bitbucket.io/spde-gitbook/)
    * [Michael Clarks documents](https://m-clark.github.io/documents.html) loads of tips and how-to for R
    * [Beyond Multiple Linear Regression: Applied Generalized Linear Models and Multilevel Models in R](https://bookdown.org/roback/bookdown-BeyondMLR/)
    * [An Introduction for Statistical Learning](https://www.statlearning.com/) includes a link to the PDF of the 1st edition
    * [Statistical rethinking with brms, ggplot2, and the tidyverse](https://bookdown.org/content/4857/) is based on "Statistical rethinking" and fits models with the rbms package
    * [Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/) includes a link to the 2nd edition
    * [Outstanding User Interfaces with Shiny](https://unleash-shiny.rinterface.com/welcome.html)
    * [The Art of Data Science](https://bookdown.org/rdpeng/artofdatascience/) by Roger Peng and Elizabeth Matsui
    * [RStudio::conf materials](https://github.com/rstudio/rstudio-conf) contains (some) talks and workshops from the different conferences
      * [ggplot2 with Cedric Scherer](https://github.com/rstudio-conf-2022/ggplot2-graphic-design)
      * [Quarto with Tom Mock (Getting started with Quarto)](https://github.com/rstudio-conf-2022/get-started-quarto) or [Andrew Bray (From Rmd to qmd)](https://github.com/rstudio-conf-2022/rmd-to-quarto)
      * [Causal inference with Lucy D'Agostino McGowan + Malcolm Barrett](https://github.com/rstudio-conf-2022/causal-inference-rstats)
      * and much more...
  * tidymodel resources (mostly from [here](https://twitter.com/PipingHotData/status/1400278485327876096))
    * [A Gentle Introduction to tidymodels](https://rviews.rstudio.com/2019/06/19/a-gentle-intro-to-tidymodels/)
    * [Introduction to Machine Learning with the Tidyverse](https://education.rstudio.com/blog/2020/02/conf20-intro-ml/)
    * [Choose your own tidymodels adventure](https://www.tidyverse.org/blog/2021/05/choose-tidymodels-adventure/)
    * [Tidy Modeling with R](https://www.tmwr.org/) (a tidymodels pagedown)
    * [Get started with tidymodels and #TidyTuesday Palmer penguins](https://juliasilge.com/blog/palmer-penguins/)
      * and [generally other stuff](https://juliasilge.com/) from [Julia Silge](https://twitter.com/juliasilge)
    * [tidmodels labs](https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/index.html)
    * the [tidymodels site](https://www.tidymodels.org/), of course
    * [notes on a book club](https://r4ds.github.io/bookclub-tmwr/) from the R4DS people
    * [tidymodels labes based on An Intro to Statistical Learning](https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/index.html)
    * [RStudio::conf 2022 workshop on tidymodels](https://github.com/rstudio-conf-2022/tidymodels-ml) by Julia Silge + Max Kuhn + David Robinson
    * not tidymodels, but ML... [code for ML by ML in neuroscience lab in zurich](https://micnlab.com/files/)
      * and [their paper on ML for clinicians](https://arxiv.org/abs/2006.15069) which refers to the code
    * also not strictly tidymodels, but ML [a comic book on ML in R](https://betaandbit.github.io/RML/)
  * [marginal means from models with interactions](https://grantmcdermott.com/interaction-effects/)
  * [mapping with R - gallery of maps from the #30DayMapChallenge with links to code](https://david.frigge.nz/3RDayMapChallenge/)
  * Discussions on .Rproj and here - [Jenny Bryan is for them: Project-oriented workflow](https://www.tidyverse.org/blog/2017/12/workflow-vs-script/), while [Tarak Shah seems to be against them: .Rproj considered harmful](https://hrdag.org/tech-notes/harmful.html#the-manual-unit-test)


#### Validation
Validating R itself is a big task. The R Foundation Board has a [statement on the issue](https://www.r-project.org/doc/R-FDA.pdf) which covers a few points that need not be covered by a validation of R itself (as they should be covered by the host system, e.g. Windows, MacOS, ...), but puts the onus for other issues in the hands of the organisation using the software. 

The [R validation hub](https://www.pharmar.org/overview/) has various info on the topic, including a [white paper](https://www.pharmar.org/white-paper/). They have also created an R Package, [`riskmetric`](https://pharmar.github.io/riskmetric/index.html) for estimating the risk posed by a given package based on it's documentation, bugs/issues, downloads etc. 

The [`valtools` package](https://github.com/phuse-org/valtools) may be useful for documenting validation of R packages (see a presentation on the package [here](https://www.youtube.com/watch?v=HVd5iGTNLGE)) and a [white paper on the topic](https://phuse.s3.eu-central-1.amazonaws.com/Deliverables/Data+Visualisation+%26+Open+Source+Technology/WP059.pdf) from the PHUSE group.

Information from RStudio on [environment validation](https://solutions.rstudio.com/environments/validation/)
  
Stata's internal approach to testing https://journals.sagepub.com/doi/10.1177/1536867X0100100102

[Verifizierung und Validierung: Unterschied & Definitionen](https://www.johner-institut.de/blog/iec-62304-medizinische-software/verifizierung-und-validierung-von-medizinprodukten/)

## Misc
  * [StatTag - a method to make dynamic WORD documents, supports Stata, R, and others](https://github.com/stattag)
  * [Use Notepad++ as a Stata editor](https://huebler.blogspot.com/2008/04/stata.html)
  * [Use Notepad++ as an R code editor](https://jekyll.math.byuh.edu/other/howto/notepadpp/using.shtml) (see also [sourceforge for the exe](https://sourceforge.net/projects/npptor/))
  * [Datamethods reference collection on "common myths"](https://discourse.datamethods.org/t/reference-collection-to-push-back-against-common-statistical-myths/1787)
    * e.g. has sections on post-hoc power (see also [this paper from Feb. 2022](https://www.sciencedirect.com/science/article/pii/S0889540621006971?via%3Dihub)), p-values in baseline tables and much more. A very useful resource.
  * [BBR - Biostats for biomedical research](http://hbiostat.org/bbr/)
    * Frank Harrell and co's course
    * [PDF to course material](http://hbiostat.org/doc/bbr.pdf)
    * [ebook website](http://hbiostat.org/bbr/)
    * [Youtube videos of sessions/"lectures"](https://www.youtube.com/channel/UC-o_ZZ0tuFUYn8e8rf-QURA/videos)
  * [Ben Bolkers mixed models 'FAQ'](https://bbolker.github.io/mixedmodels-misc/glmmFAQ.html)
    * got a question about mixed models (particularly in R, but also in general), there's a chance it's covered there
  * [Intro to statistical learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) book website (includes PDF)
  * [Common statistical tests are linear models](https://lindeloev.github.io/tests-as-linear/) (even non-parametric ones)
  * [Statistical Problems to Document and to Avoid. Checklist for Authors](https://discourse.datamethods.org/t/author-checklist/3407)
  * [git/github notes](./github)
  * [C++ by example](https://cppbyexample.com/)

## Sample size
  * [presize](https://shiny.ctu.unibe.ch/presize)
  * Stepped wedge
    * [shiny app for stepped wedge](https://clusterrcts.shinyapps.io/rshinyapp/)
    * [various resources for stepped wedge](https://steppedwedgehog.blog/resources/#sample)
  * Sample size for prediction models 
    * [A note on estimating the Cox-Snell R2 from a reported C statistic (AUROC) to inform sample size calculations for developing a prediction model with a binary outcome](https://onlinelibrary.wiley.com/doi/epdf/10.1002/sim.8806)
    * [Sample size for binary logistic prediction models: Beyond events per variable criteria](https://doi.org/10.1177/0962280218784726)
    * [Calculating the sample size required for developing a clinical prediction model](https://doi.org/10.1136/bmj.m441)
    * [No rationale for 1 variable per 10 events criterion for binary logistic regression analysis](https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-016-0267-3)
    * [Minimum sample size for developing a multivariable prediction model: Part I – Continuous outcomes](https://doi.org/10.1002/sim.7993)
    * [Minimum sample size for external validation of a clinical prediction model with a continuous outcome](https://doi.org/10.1002/sim.8766)
    * [Minimum sample size for developing a multivariable prediction model: PART II - binary and time-to-event outcomes](https://onlinelibrary.wiley.com/doi/full/10.1002/sim.7992) (pmsampsize for stata and R)
    * [Minimum sample size for external validation of a clinical prediction model with a binary outcome](https://onlinelibrary.wiley.com/doi/10.1002/sim.9025?af=R) 
    * [Sample size considerations and predictive performance of multinomial logistic prediction models](https://doi.org/10.1002/sim.8063)
    * [Adaptive sample size determination for the development of clinical prediction models](https://diagnprognres.biomedcentral.com/articles/10.1186/s41512-021-00096-5)
    * [Some suggestions for measuring predictive performance](https://link.springer.com/article/10.1007/BF01060893)
  * [WebPower](https://cran.r-project.org/web/packages/WebPower) - pretty powerful looking [website](https://webpower.psychstat.org/wiki/)/R package with a wide range of methods/tests.

 
## Useful literature
  * [A simple, step-by-step guide to interpreting decision curve analysis](https://doi.org/10.1186/s41512-019-0064-7)
  * [Table 2 Fallacy](https://academic.oup.com/aje/article/177/4/292/147738) on interpretation of model parameters in the presence of confounding/effect modifiers
  * [Standardized classification and framework for reporting, interpreting, and analysing medication non-adherence in cardiovascular clinical trials: a consensus report from the Non-adherence Academic Research Consortium (NARC)](https://pubmed.ncbi.nlm.nih.gov/29992264/) - a method for handling levels of adherence
  * [Introduction to computational causal inference using reproducible Stata, R, and Python code: A tutorial](https://onlinelibrary.wiley.com/doi/full/10.1002/sim.9234?campaign=wolearlyview) - We illustrate the implementation of different methods [G formula/methods, IPTW, MSM, double-robust, targeted maximum likelihood estimation (TMLE)] using an empirical example from the Connors study based on intensive care medicine, and most importantly, we provide reproducible and commented code in Stata, R, and Python for researchers to adapt in their own observational study. 
    * [R, Stata and SAS code is available here](https://github.com/migariane/TutorialComputationalCausalInferenceEstimators)
    * [Covariate Adjustment in Randomized Trials](https://covariateadjustment.github.io)  - Covariate Adjustment in Randomized Trials
  * RMST
    *  Other possible CIs - [Some new confidence intervals for Kaplan-Meier based estimators from one and two sample survival data](https://onlinelibrary.wiley.com/doi/10.1002/sim.9105)
    *  [Are restricted mean survival time methods especially useful for noninferiority trials?](https://journals.sagepub.com/doi/full/10.1177/1740774520976576)
    *  [Why restricted mean survival time methods are especially useful for non-inferiority trials](https://journals.sagepub.com/doi/pdf/10.1177/17407745211045124)
    *  [Adding a new analytical procedure with clinical interpretation in the tool box of survival analysis](https://www.sciencedirect.com/science/article/pii/S0923753419345612)
    *  [Utility of Restricted Mean Survival Time Analysis for Heart Failure Clinical Trial Evaluation and Interpretation](https://www.sciencedirect.com/science/article/pii/S2213177920304558)
    *  [A comparison of different population-level summary measures for randomised trials with time-to-event outcomes, with a focus on non-inferiority trials](https://journals.sagepub.com/doi/10.1177/17407745231181907)
  *  [When and how should multiple imputation be used for handling missing data in randomised clinical trials – a practical guide with flowcharts](https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-017-0442-1) - useful as a reference for the choice of 5% missing to start using MI and >40% missing as a reason to stop
  *  [Win odds: An adaptation of the win ratio to include ties](https://onlinelibrary.wiley.com/doi/full/10.1002/sim.8967)
  *  [Lessons learnt when accounting for competing events in the external validation of time-to-event prognostic models](https://academic.oup.com/ije/article/51/2/615/6468864) - long story short... its important...
  * [FDA guidance on multiple testing in clinical trials](https://www.fda.gov/media/162416/download)
  * [A roadmap to using randomization in clinical trials](https://bmcmedresmethodol.biomedcentral.com/articles/10.1186/s12874-021-01303-z) - a comparison of different randomization methods
  * [Statistical code for clinical research papers in a high-impact specialist medical journal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6705117/)
  * [Ten simple rules for initial data analysis](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009819)

## Reporting guidelines
  * TRIPOD - guidelines for reporting of predictive/prognostic models (validation or derivation)
    * [Moons et al 2011](https://heart.bmj.com/content/98/9/683.short)
    * [Moons et al 2015](http://dx.doi.org/10.7326/M14-0698) 
    * [Moons et al 2012](http://heart.bmj.com/content/98/9/691)
    * [TRIPOD checklists](https://www.equator-network.org/reporting-guidelines/tripod-statement/)
    * [Alternate site for derivation/validation checklist](https://med.stanford.edu/content/dam/sm/s-spire/documents/ManuscriptQualityChecklists/Tripod-Checklist-Prediction-Model-Development-and-Validation.pdf)
  * Latent trajectory studies (GRoLTS)
    * [The GRoLTS-Checklist: Guidelines for Reporting on Latent Trajectory Studies](https://www.tandfonline.com/doi/full/10.1080/10705511.2016.1247646)
  * STROBE - guidelines for reporting of observational studies
    * [STROBE website](https://www.strobe-statement.org/index.php?id=strobe-home)
    * [STROBE checklists](https://www.strobe-statement.org/index.php?id=available-checklists)
    * The STROBE statement itself has been published in many journals ([see here](https://www.strobe-statement.org/index.php?id=strobe-publications))
  * CONSORT - guidelines for publishing RCTs
    * [Checklist](http://www.consort-statement.org/consort-statement/checklist)
    * [Statement](http://www.consort-statement.org/consort-2010)
    * [Flow diagram](http://www.consort-statement.org/consort-statement/flow-diagram)
    * DISCOURAGES USE OF P-VALUES/CONFIDENCE INTERVALS/STANDARD ERRORS IN DESCRIPTIVE TABLES (e.g. Table 1) - POSSIBLY USEFUL TO REFUTE REVIEWER REQUESTS FOR THEM (see also the [Datamethods reference collection on "common myths"](https://discourse.datamethods.org/t/reference-collection-to-push-back-against-common-statistical-myths/1787))
    * [Extension for adaptive designs](https://trialsjournal.biomedcentral.com/articles/10.1186/s13063-020-04334-x)
      * (checklist in the supplementary materials)
    * [CONSORT-AI](https://www.clinical-trials.ai/consort) site, including checklist, and the [publication](https://www.nature.com/articles/s41591-020-1034-x)
  * PRISMA - guidelines for transparent reporting of systematic reviews
    * [Homepage](http://www.prisma-statement.org/)
    * [Checklist](http://www.prisma-statement.org/PRISMAStatement/Checklist)
    * [Extensions to the original statement](http://www.prisma-statement.org/Extensions/)
    * [Link registration details page](http://www.prisma-statement.org/Protocols/Registration) where registrations are actually made on [PROSPERO](https://www.crd.york.ac.uk/PROSPERO/)
    * Note that systematic reviews/metaanalyses are sometimes/often rejected by journals for not having been registered

The [EQUATOR Network](https://www.equator-network.org/) also has links to many other guidelines (SPIRIT, CARE, AGREE, ...)

Not a reporting guideline per se, but a method of assessing risk of bias and applicability of prediction model studies - [PROBAST](www.probast.org)
  * [PROBAST paper](https://www.acpjournals.org/doi/10.7326/M18-1376)
  * [further explanations and elaboration of PROBAST](https://www.acpjournals.org/doi/10.7326/M18-1377)
  * useful along side TRIPOD perhaps?
  * use of PROBAST to [assess ML models in ocology](https://diagnprognres.biomedcentral.com/articles/10.1186/s41512-022-00126-w). Long story short, most models are high risk 
    > 123 (81%, 95% CI: 73.8 to 86.4) developed models and 19 (51%, 95% CI: 35.1 to 67.3) validated models were at high risk of bias due to their analysis, mostly due to shortcomings in the analysis including insufficient sample size and split-sample internal validation

[The COMET Initiative](https://www.comet-initiative.org/) has a searchable list of standardised outcome sets for diseases, conditions etc.

[SPIRIT](https://www.spirit-statement.org/) (Standard Protocol Items: Recommendations for Interventional Trials)
  * [SPIRIT-AI](https://www.clinical-trials.ai/spirit) website and [publication](https://www.nature.com/articles/s41591-020-1037-7)

[ICEMAN](https://www.iceman.help/overview) provides an approach for assessing the credibility of subgroup analyses.
  * [publication](https://www.cmaj.ca/content/192/32/E901)
  * [worksheets](https://www.iceman.help/download)

Feel free to add to this list.
