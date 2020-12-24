# Monteverde, Costa Rica Christmas Bird Count Shiny app

[Shiny app](XXXXX) for Monteverde Christmas Bird Count. 

Adapted from [Sharleen W's Shiny app for Hamilton, Ontario](https://sharleenw.shinyapps.io/hamilton_cbc_shiny/), as described on [this blog]( https://sharleenw.rbind.io/2019/03/24/hamilton-cbc-part-3/)

# data

"HistoricalResultsByCount [CRCMO-2011-2020].csv" is the raw csv download (taxonomic sort) from https://netapp.audubon.org/cbcobservation/historical/resultsbycount.aspx# for count code CRMO.

Start year: XXXX (1994) and End year: 120 (2019), even though the filename says XXXX-2020

I did do a bit of manual cleanup as described in the Rmd.

cleaning.Rmd takes CRMO-XXXX-2019_pre-cleaned.csv and outputs CRMO-CBC-2019-cleaned.csv

# root
CRMO-CBC-2019-cleaned.csv is the data file used by the app.

app.R is the code for the Shiny app.
