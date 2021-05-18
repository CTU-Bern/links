# links
As it is not possible for an organization to star/follow repositories/organizations, here is a list of potentially interesting github repositories/organizations/users. This list also contains links to various other things that might be of interest (e.g. guidelines).

## [SCTO Organisation](https://github.com/SwissClinicalTrialOrganisation)
  * [SecuTrial R package](https://github.com/SwissClinicalTrialOrganisation/secuTrialR)
  * [SecuTrial Recipes (Enhanced version)](https://swissclinicaltrialorganisation.github.io/secuTrial_recipes/)
  * [SecuTrial Recipes (GitHub version)](https://github.com/SwissClinicalTrialOrganisation/secuTrial_recipes)
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
  * [CodeMap - MAC application for examining dependencies in R or Stata analyses](https://github.com/haghish/CodeMap)
  * Power calculation
    * [Simon's two stage design](https://ideas.repec.org/c/boc/bocode/s457081.html)
## R
  * Packages
    * [Gmisc - package that includes a nice approach to creating flowcharts](https://github.com/gforge/Gmisc)
      * [Link to vignette](https://cran.r-project.org/web/packages/Gmisc/vignettes/Grid-based_flowcharts.html)
    * [flowchart - Alan's flowchart package - create flowcharts without needing to play around with the layout (much)](https://github.com/CTU-Bern/flowchart)
    * Predictions from mixed models, with SEs are available in the [AICcmodavg](https://cran.r-project.org/web/packages/AICcmodavg/index.html) package
    * [atable](https://cran.r-project.org/web/packages/atable/index.html) package for baseline tables. Very flexible.
    * [gtsummary](http://www.danieldsjoberg.com/gtsummary/index.html) also for baseline tables. Also flexible.
    * [metamisc](https://cran.r-project.org/web/packages/metamisc/index.html) 'Facilitate meta-analysis of diagnosis and prognosis research studies. It includes functions to summarize multiple estimates of prediction model discrimination and calibration performance, as described by Debray et al. (2019) <doi:10.1177/0962280218785504>. It also includes functions to evaluate funnel plot asymmetry, as described by Debray et al. (2018) <doi:10.1002/jrsm.1266>. Finally, the package provides functions for developing multivariable prediction models from datasets with clustering. '
    * [ipcwswitch](https://www.sciencedirect.com/science/article/abs/pii/S0010482519302082?via%3Dihub) 'Inverse Probability of Censoring Weights to Deal with Treatment Switch in Randomized Clinical Trials'
    * Power calculation:
      * [presize - precision based sample size calculation](https://github.com/CTU-Bern/presize)
        * [shiny app](https://shiny.ctu.unibe.ch/presize)
      * [Simon's two stage design and various Bayesian approaches for single arm studies](https://cran.r-project.org/web/packages/EurosarcBayes/index.html)
      * [pmsampsize for predictive models](https://CRAN.R-project.org/package=pmsampsize)
  * [CodeMap - MAC application for examining dependencies in R or Stata analyses](https://github.com/haghish/CodeMap)
  * [Scottish health/social care - Various stuff including funnel plots](https://github.com/Health-SocialCare-Scotland/R-Resources)
  * [R package template (based on secuTrialR).](https://github.com/CTU-Basel/pkgTemplateR) Includes e.g. continuous integration testing with appveyor and TravisCI. Click the "use this template" button to copy it to a new repo (under a new name) then edit it as required.
  * "Books"
    * [Free online resources for learning R](https://cmdlinetips.com/2018/01/free-online-resources-books-to-learn-r-and-data-science/)
    * [Big Book of R](https://www.bigbookofr.com/index.html) - listing of a lot of online R books
    * [Flexible Imputation of Missing Data](https://stefvanbuuren.name/fimd/) book from the author of the `mice` package.
    * [Forecasting: Principles and Practice](https://otexts.com/fpp2/) Uses R for time series analysis and forecasting
    * [Data visualization](https://socviz.co/) lots on ggplot and R
    * [Bayesian inference with INLA](https://becarioprecario.bitbucket.io/inla-gitbook/index.html) covers a LOT of INLA stuff.
    * [Advanced Spatial Modeling with Stochastic Partial Differential Equations Using R and INLA](https://becarioprecario.bitbucket.io/spde-gitbook/)
    * [Michael Clarks documents](https://m-clark.github.io/documents.html) loads of tips and how-to for R
  
## Misc
  * [StatTag - a method to make dynamic WORD documents, supports Stata, R, and others](https://github.com/stattag)
  * [Use Notepad++ as a Stata editor](https://huebler.blogspot.com/2008/04/stata.html)
  * [Use Notepad++ as an R code editor](https://jekyll.math.byuh.edu/other/howto/notepadpp/using.shtml) (see also [sourceforge for the exe](https://sourceforge.net/projects/npptor/))
  * [Datamethods reference collection on "common myths"](https://discourse.datamethods.org/t/reference-collection-to-push-back-against-common-statistical-myths/1787)
    * e.g. has sections on post-hoc power, p-values in baseline tables and much more. A very useful resource.
  * [BBR - Biostats for biomedical research](http://hbiostat.org/bbr/)
    * Frank Harrell and co's course
    * [PDF to course material](http://hbiostat.org/doc/bbr.pdf)
    * [Youtube videos of sessions/"lectures"](https://www.youtube.com/channel/UC-o_ZZ0tuFUYn8e8rf-QURA/videos)
  * [Ben Bolkers mixed models 'FAQ'](https://bbolker.github.io/mixedmodels-misc/glmmFAQ.html)
    * got a question about mixed models (particularly in R, but also in general), there's a chance it's covered there
  * [Intro to statistical learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) book website (includes PDF)
  * [Common statistical tests are linear models](https://lindeloev.github.io/tests-as-linear/) (even non-parametric ones)
  * [Statistical Problems to Document and to Avoid. Checklist for Authors](https://discourse.datamethods.org/t/author-checklist/3407)
  * [git/github notes](./github)

## Sample size
  * [presize](https://shiny.ctu.unibe.ch/presize)
  * Stepped wedge
    * [shiny app for stepped wedge](https://clusterrcts.shinyapps.io/rshinyapp/)
    * [various resources for stepped wedge](https://steppedwedgehog.blog/resources/#sample)
  * [Sample size for prediction models (pmsampsize for stata and R)]()

 
## Useful literature
  * [A simple, step-by-step guide to interpreting decision curve analysis](https://doi.org/10.1186/s41512-019-0064-7)
  * [Table 2 Fallacy](https://academic.oup.com/aje/article/177/4/292/147738) on interpretation of model parameters in the presence of confounding/effect modifiers
  * [Standardized classification and framework for reporting, interpreting, and analysing medication non-adherence in cardiovascular clinical trials: a consensus report from the Non-adherence Academic Research Consortium (NARC)](https://pubmed.ncbi.nlm.nih.gov/29992264/) - a method for handling levels of adherence

## Reporting guidelines
  * TRIPOD - guidelines for reporting of predictive/prognostic models (validation or derivation)
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
    * DISCOURAGES USE OF P-VALUES/CONFIDENCE INTERVALS/STANDARD ERRORS IN DESCRIPTIVE TABLES (e.g. Table 1) - POSSIBLY USEFUL TO REFUTE REVIEWER REQUESTS FOR THEM
    * [Extension for adaptive designs](https://trialsjournal.biomedcentral.com/articles/10.1186/s13063-020-04334-x)
      * (checklist in the supplementary materials)
  * PRISMA - guidelines for transparent reporting of systematic reviews
    * [Homepage](http://www.prisma-statement.org/)
    * [Checklist](http://www.prisma-statement.org/PRISMAStatement/Checklist)
    * [Extensions to the original statement](http://www.prisma-statement.org/Extensions/)
    * [Link registration details page](http://www.prisma-statement.org/Protocols/Registration) where registrations are actually made on [PROSPERO](https://www.crd.york.ac.uk/PROSPERO/)
    * Note that systematic reviews/metaanalyses are sometimes/often rejected by journals for not having been registered

Feel free to add to this list.
