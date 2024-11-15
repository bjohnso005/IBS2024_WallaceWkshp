<div align="center">
	<img src="logo.png" width="200">
</div>

# Species Distribution Modeling for Conservation with *Wallace EcoMod*

# Organizers

-   **Bethany A. Johnson** (wallaceecomod@gmail.com; bjohnso005@citymail.cuny.edu)  
    Center for Biodiversity & Conservation, American Museum of Natural History  
-   **Andrea Paz** (andrea.paz.velez@umontreal.ca)  
    Université de Montréal

# Logistics
Date: 22 November 2024  
Time: 2:00 – 5:00 p.m. GMT  
Location: Virtual - Zoom Link to be provided  

# Abstract
Species distribution modeling (SDM) enables conservation scientists to make range
estimates for species of concern, as well as predictions of potential range in unsampled areas
and for different time periods. Since the field’s inception, modeling and methodological best
practices continue to advance at a rapid pace, and cutting-edge techniques are increasingly
accessible only to those with advanced programming knowledge. We developed the application
Wallace EcoMod to lower the barriers for modern species distribution modeling by offering
access to the latest programmatic tools through an interactive graphical interface. Wallace
implements a range of analysis functions from existing packages in the R programming
language without necessitating any user programming knowledge. Additionally, Wallace offers
extensive guidance text that explains methodological details and theory with literature
references using simple language that benefits both new and experienced users. Each session
can be exported as a readable, documented script that can be run to reproduce the analysis in
R. The Wallace application is available in the R package `wallace`, with a single function that
opens the interface. It comes equipped with both MaxEnt and BIOCLIM algorithms for modeling
environmental suitability to estimate species’ ranges.  

In this workshop, we will review the basics of SDM using Wallace, demonstrate key application
functions, highlight some new features, and show applications to conservation science through
a brief case study. Participants will also have a chance to work with their own datasets with
instructor support. Participants should have a minimal understanding of species distribution
modeling and using R. They will use their own laptops to run Wallace for a hands-on learning
experience, and will emerge more confident SDM users.  

# Agenda
Our 3hr workshop will be divided as follows:
-   Team & Group Introductions: Who we are & why we are here (40 mins)
-   Lecture: Introduction to species distribution modeling; Introduction to R & Wallace (40 mins)
-   Demo: Live demo using Wallace v2.1.3 (20 mins)
-   Short break (10 mins) *During this break we can troubleshoot any installation issues*
-   Using Wallace v2 with your own data (35 mins)
-   Preview of new v3 features for conservation (15 mins)
-   Conclusion & Questions (20 mins)

# Pre- & Post- Workshop Surveys

Please take the pre- and post-workshop surveys. They really help us!

-   Before the workshop: <a href="https://forms.gle/MSMMiShENFYePt6N8" target="_blank">Pre-workshop survey</a>

-   After the workshop: <a href="https://forms.gle/mpxaP5Ypskjjqq7A8" target="_blank">Post-workshop survey</a>

# Installation Instructions
Coming soon...

# Data
Wallace comes equipped with access to several databases to upload occurrence and environmental data, as well as an option for the user to upload their own datasets.  

<a href="https://drive.google.com/drive/folders/1oqBpCfFLlUUAMtg_63JUX5jpfGgdnw20?usp=sharing" target="_blank">Canned Data</a>  
Includes:  
- Occurrence data for two species (*B. neblina* & *B. alleni*)  
- Environmmental data at 2.5arcmin resolution  
- a binary SDM  
- a shapefile of Colombia

Note: If you would like to use your own datasets, please make sure your occurrence data is in a csv format with the first three fields named, "scientific_name", "longitude", & "latitude". See the canned data as an example. Environmental variables should be in raster format, and the same extent and resolution.


# External Links

REGISTER HERE: https://biogeography.wildapricot.org/event-5862050/Registration

<a href="https://wallaceecomod.github.io/" target="_blank">Wallace website</a>  

<a href="https://github.com/wallaceEcoMod" target="_blank">Wallace GitHub</a>  

<a href="https://wallaceecomod.github.io/wallace/articles/tutorial-v2.html" target="_blank">Wallace User Tutorial</a>  

Publications  
Cite these when using Wallace in your research.  
1.  Kass et al. (2023). wallace 2: a shiny app for modeling species niches and distributions redesigned to facilitate expansion via module contributions. Ecography, Volume 2023(3), e06547. <a href="https://doi.org/10.1111/ecog.06547" target="_blank">https://doi.org/10.1111/ecog.06547</a> 
2. Kass et al. (2018). Wallace: A flexible platform for reproducible modeling of species niches and distributions built for community expansion. Methods in Ecology and Evolution, 9, 1151–1156. <a href="https://doi.org/10.1111/2041-210X.12945" target="_blank">https://doi.org/10.1111/2041-210X.12945</a>  

# Contact Us
Wallace EcoMod has an active Google Group you can join to stay in touch with updates and user support.  <a href="https://groups.google.com/g/wallaceecomod" target="_blank">Wallace EcoMod Google Group</a>  
We also have a team email for support and inquiries: wallaceEcoMod@gmail.com  
Feel free to use our hashtag to share posts about publications or news using Wallace! **#wallaceEcoMod**

