# The Agency Fund R Workshops

Welcome! This is the Agency Fund repository for R workshops as a part of the larger research mindsets workshop series. Please follow the steps below to get set up.

## Recommended Learning Materials

[*R for Data Science*](https://r4ds.had.co.nz/) by Grolemund and Wickham.

# Workshop Recordings

...

# Setup

We recommend using GitHub Desktop to download course materials. This desktop app allows you to click a button to "pull" (i.e. download) information from our course repository on GitHub every time we update the materials. Whenever you "pull" the new information, your local folder will be automatically synced with the newest version on the GitHub website.

## 1 - Set up GitHub Desktop

1.  Create an account on https://github.com/ and Install [Github Desktop](https://desktop.github.com/).
2.  Once installed, go to our [R workshop repository on GitHub](https://github.com/agency-fund/r-workshop), and click on the green "Code" button
3.  Choose "Open with GitHub Desktop", which prompts you to the GitHub Desktop app.
4.  Choose whichever local folder path that you want to store and sync the code locally.

## 2 - Set up R and Rstudio

1.  Download and install [R](https://cran.r-project.org/) *and then*
    [RStudio](https://rstudio.com/). Note: R and RStudio are *not* the
    same thing. R is the language and execution environment, and RStudio
    is an integrated development environment (IDE) *for* R. In other
    words, you write R code using the RStudio interface, and it runs your code
    in the R programming language.
2.  Navigate to where you downloaded this repository, and open
    `R_Workshop.Rproj` with RStudio (by double-clicking the file).
3.  In the "Console" tab that should appear in the left pane, run these
    two commands in order:

``` r
install.packages("devtools")
devtools::install_deps(dependencies = TRUE)
```

All of the packages that all materials depend upon should now be
installed.
