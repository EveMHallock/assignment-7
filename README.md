## assignment-7

## **Package**
 {Rcapture}
 
 ## **Location**
 It is found on [CRAN](https://CRAN.R-project.org/package=Rcapture). 
 
 ## **Vignettes** 
 I found two related vignettes: Loglinear Models for Capture-Recapture in R, by Sophie Baillargeon and Louis-Paul Rivest in 2007, and Modeling variation in abundance using capture-recapture data, by Richard Chandler in 2019 (this one covers the unmarked package).

## **Applications**
There are no websites from this package. Hillman & Jones (2022) used and cited it in their study, A resurvey of a Wood Turtle (Glyptemys insculpta) population in northern New Hampshire, USA, after 13 years. They state: "We  estimated  the  size  of  the  population  in  2007  and  2020  using  closed-population  loglinear  models  (Otis et al. 1978; Rivest and Lévesque 2001) and con-ducted all analyses in the “Rcapture” package version 1.4-3 (Baillargeon and Rivest 2007) in the program-ming language R version 4.2.1 (R Core Team 2020)."

## **Review**
Baillargeon and Rivest state that "The package Rcapture covers the basic statistical models for capture-recapture experiments. It is the only package that focuses on the use of loglinear models for the analysis of closed and open population data." You can fit a variety of built in models to your own closed or open population data, or nine built in datasets. For example data(mvole) is an open population of meadow voles. You can use the function openp to see if a population is closed or open. The function closedp is how you fit loglinear models for abundance estimations.
The biggest limitation of the package is that it does not include deaths that could occur with trapping or other unknown reasons. I do think it is still very useful to summarize capture/recapture data. It is easy to visualize capture occasions, numbers of individuals during capture periods, individual animals' records, etc. You can fit parameters, compare models, make AIC tables, and calculate confidence intervals smoothly. I would recommend that someone check this package out, although mark and unmark may also be more useful depending on the distribution or format of the data. 


