Title: computional_biology_project <br />
Background: This project is undergrad research for Mark Grimes.	<br />
Start date: September 2016 <br />
Objective: Create an interactive web application that uses Mark's existing work on the interaction	of gene/protein networks. <br />	

The packages folder includes additional packages needed for RCy3 to run and some for RCyjs to run. R will notify you if more dependencies are needed. Install these if R instructs. <br />

Versions: <br />
R 		3.3.1 64 bit <br />
RCyjs 		1.7.0 NOTE: Do not install RCyjs with biocLite("RCyjs"). It will revert you to an old version. <br />
RCy3		1.2.0 NOTE: Do not install with biocLite("RCy3"). It reverts to an old version that will not work with R 3.3.1. <br />
BrowserViz 	1.7.0 <br />
BiocInstaller 	1.24.0 <br />
Bioconductor	3.4 <br />
Java		1.8.0_111-b14 <br />
Cytoscape 	3.4.0 <br />
cyREST app	3.3.7 <br />

To get setup and check that RCy3 works, do the following... <br />
Install R version 3.3.1 64 bit. <br />
Install the packages in the packages folder. <br />
Run in R (check that bioconductor is version 3.4): <br />
source("https://bioconductor.org/biocLite.R") <br />
Add any additional packages that R instructs. <br />
Load libraries in R: <br />
library(RCy3) <br />
Install Cytoscape version 3.4.0. <br />
Turn on Cytoscape. <br />
Run the following in R to make the connection: <br />
cy <- CytoscapeConnection() <br />
For additional instructions read the RCy3_documentation pdf. <br />
Note that some instructions in the pdf may or may not be outdated. <br />
