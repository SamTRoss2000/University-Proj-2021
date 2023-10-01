This folder contains the pipeline and provided 
data to convert three datasets of input data 
into a output of an interactive shiny map constructed 
via the leaflet package.

-----------------------------------------------------
		     PACKAGES:
-----------------------------------------------------
Copy and paste this code into Rstudio and run to install 
the packages necessary for the pipeline:

# Used for examining and cleaning data 
install.packages("janitor")

# tidyverse is a collection of packages for data tidying and includes the pipe
install.packages("tidyverse")

# Allows melting and recasting of data which allows conversion from wide to long formats and vice versa
install.packages("reshape2")

# Used for the combining of dataframes
install.packages("plyr")

# Used for building interactive web apps in R
install.packages("shiny")

# Allows creating and customizing interactive maps 
install.packages("leaflet")

# Used for building complex HTML tables
install.packages("kableExtra")

# DT used as most of the dataframes are too large to be suitable for kableExtra
install.packages("DT")

-----------------------------------------------------
		     WARNING:
-----------------------------------------------------
If any of the packages are already installed then check for
updates before attempting to run the "map_pipeline.Rmd" Rmarkdown
file. If the file is ran without being updated then clear cache 
of the markdown file and attempt again.
-----------------------------------------------------
		    DATA PROCESSING:
-----------------------------------------------------
The raw data is processed by opening and running the 
Rmarkdown file. If alternate data is to be added
or updated to the map then ensure the file name is
the same type and has the same name.
