# Welcome
This is the bioinformatics part of the Cancer Immunotherapy Research course. We will analyze data using [R](https://www.r-project.org/) and perform some simple statistical tests to look predicitive and prognostic markers to immunotherapy. 

# Installation
To install R download it from [https://www.r-project.org/](https://www.r-project.org/)
To Rstudio download it from [https://www.rstudio.com/](https://www.rstudio.com/)

# Installing packages
R comes with some default packages for statistical and plotting but we will use fancier libraries for our analysis
inside we will use the install.packages function
```{r, message = TRUE, warning = FALSE, echo = TRUE}
install.packages(c("tidyverse"))
```