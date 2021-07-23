This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

It is about the role of religious institutions in providing informal insurance and is based on the paper "God Insures Those Who Pay? Formal Insurance and Religious Offerings in Ghana" by Emmanuelle Auriol, Julie Lassébie, Amma Panin, Eva Raiber, Paul Seabright.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("aditi-malani/RTutorGodInsuresThoseWhoPay")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorGodInsuresThoseWhoPay)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorGodInsuresThoseWhoPay")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorGodInsuresThoseWhoPay",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
