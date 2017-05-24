# ASReml-R
Some examples of ASReml-R use for mixed models in R.  

Please note that ASReml-R is a commercial package that requires a license.

Exp35_2015_data_analysis.Rmd and Exp35_2015_data_analysis.pdf are R markdown and knitted PDF versions of an analysis of a field experiment with two replications of an alpha incomplete block design of different corn variaties evaluated for Fusarium ear rot and fumonisin content in the grain. Each plot of ~ 25 plants was split in half, with different inoculation treatments applied to each half. Ears were scored for percent kernel rot at maturity, then grain was bulked and assayed for fumonisin content by two different students at two different universities (LM and TM). The objective of the analysis was to explore data, transform as necessary to stabilize residuals, and compare inoculation methods and assays in terms of correlations and heritabilites. 

Some useful aspects of this code are running ASReml analyses within functions, which requires some trickery. The Cullis heritability estimator was used. Some munging was required to split and combine data in different ways for different inoculation procedures, and dply methods (mostly) were used for that.
