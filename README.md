Title: computional_biology_project
Background: This project is undergrad research
for Mark Grimes. 
Start date: September 2016
Objective: Create an interactive web application
that uses Mark's existing work on the interaction
of gene/protein networks. 

The packages folder includes additional packages 
needed for RCy3 to run and some for RCyjs to run. 
R will notify you if more dependencies are needed. 
Install these if R instructs. 

Versions:
R 		3.3.1 64 bit	
RCyjs 		1.7.0	
		NOTE: Do not install RCyjs with 
		biocLite("RCyjs"). It will revert 
		you to an old version.	
RCy3		1.2.0	
		NOTE: Do not install with 
		biocLite("RCy3"). It reverts to 
		an old version that will not work 
		with R 3.3.1.	 
BrowserViz 	1.7.0	
BiocInstaller 	1.24.0	
Bioconductor	3.4	
Java		1.8.0_111-b14	
Cytoscape 	3.4.0	
cyREST app	3.3.7	

To get setup and check that RCy3 works, do the following...	
Install R version 3.3.1 64 bit.	
Install the packages in the packages folder.	
Run in R (check that bioconductor is version 3.4):	 
source("https://bioconductor.org/biocLite.R")	
Add any additional packages that R instructs.	 
Load libraries in R:	
library(RCy3)	
Install Cytoscape version 3.4.0.	
Turn on Cytoscape.	
Run the following in R to make the connection:	
cy <- CytoscapeConnection()	
For additional instructions read the RCy3_documentation pdf.	
Note that some instructions in the pdf may or may not be outdated.	
