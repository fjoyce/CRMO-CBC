# ACG-Cacao CBC Shiny app

[Shiny app](https://fhjoyce.shinyapps.io/CRCA-CBC/) for Cacao Christmas Bird Count in Area Conservación Guanacaste. 

Adapted from [Sharleen W's Shiny app for Hamilton, Ontario](https://sharleenw.shinyapps.io/hamilton_cbc_shiny/), as described on [this blog]( https://sharleenw.rbind.io/2019/03/24/hamilton-cbc-part-3/)

# data

"HistoricalResultsByCount [CRCA-2011-2020].csv" is the raw csv download (taxonomic sort) from https://netapp.audubon.org/cbcobservation/historical/resultsbycount.aspx# for count code CRCA.

Start year: 111 (2010) and End year: 120 (2019), even though the filename says 2011-2020

I did do a bit of manual cleanup as described in the Rmd.

ACG-CBC-cleaning.Rmd takes CRCA-2010-2019_pre-cleaned.csv and outputs CRCA-CBC-2019-cleaned.csv

# root
CRCA-CBC-2019-cleaned.csv is the data file used by the app.

app.R is the code for the Shiny app.
