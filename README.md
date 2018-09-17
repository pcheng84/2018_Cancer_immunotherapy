# Introduction
Cancer immunotherapy research is quite diverse and large datasets of clinical parameters such as hematological values, response and survival are being collected by the hospital. We can explore the data using [R](https://www.r-project.org/) and perform some simple statistical tests to look predicitive and prognostic markers. 

# What is R
- Free statistical language
- Works on Mac, Windows and Linux
- Detailed and complete help available
- [Rstudio](https://www.rstudio.com/) is a nice IDE to work in R

# What can R do
- Tables
- Explore data
- Arrange / merge tables according to multiple criteria
- Statistics
    - T-test, Chi-squared, ANOVA, Regression, Multiple regression, General linear model         (logistic regression), Mixed effects models, Multivariate methods etc.
- Graphs
    - Creates graphical outputs of publication quality.
- Save as pdf, eps, jpeg, png, bitmap, tiff


# Installation
To install R download it from [https://www.r-project.org/](https://www.r-project.org/)
To Rstudio download it from [https://www.rstudio.com/](https://www.rstudio.com/)

# Installing packages
R comes with some default packages for statistical and plotting but we will use fancier libraries for our analysis
inside we will use the install.packages function
```{r, message = TRUE, warning = FALSE, echo = TRUE}
install.packages(c("tidyverse""))
```