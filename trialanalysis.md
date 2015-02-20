1 Trial Analysis Presentation
========================================================
author: James Forde
date: 16 Feb 2015

2 Trial Analysis Description
========================================================

This is an example project for the Data Products course from
the Coursera website, it provides an example of a SHINY project
which when run (via runApp()) allows you to see the results of
a fictitious analysis of sales of various brands/products sold
over weekly periods.

The project assignment is to demonstrate basic knowledge for 
programming the shiny web interface and subsequently the 
deployment of same on an RStudio shiny server.

3 Trial Analysis Data
========================================================


The data for this app can be found in the github repository.

The following data files were used:-

TrialMaster.csv
TrialDetails.csv
TrialBrands.csv

TrialMaster contains transaction level information, of main in
are the quantities sold.

TrialDetails contains the brands per transaction and links to 
TrialMaster.

TrialBrands contains branding information to enable top sellers 
and category based sales to be determined.

The dataset is stored in a comma-separated-value (CSV) files.

4 Trial Analysis Graph
========================================================

![plot of chunk unnamed-chunk-2](trialanalysis-figure/unnamed-chunk-2.png) 

5 Trial Analysis Links
========================================================

See the shiny app in action here
- https://dataprods.shinyapps.io/dataprods/

Get the shiny app source code here
- https://github.com/j4de/DataProductsCoursera

