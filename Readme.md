## Adverse Events

This repository contains a sample Shiny application and parameterized R Markdown report based off of adverse event data available from the FDA. The content also uses the rxNorm data set available on BigQuery.

To run these examples you'll need to setup a Google Cloud account and follow the instructions in the `bigrquery` package. 

Alternatively, you can visit the sample application and report on our demo servers:

- App: http://colorado.rstudio.com/rsc/content/1556/
- Report: http://colorado.rstudio.com/rsc/content/1559/

The parameterized report creates a custom email and also generates and attaches a powerpoint document. The report itself is a pdf generated using the `tufte` package.
