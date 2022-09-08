
# R Class

This is an empty repo to initialize an R project for [Introduction to
Programming in R](https://courses.business.columbia.edu/B8144) at
[Columbia Business School](https://courses.business.columbia.edu/B8144).

Please **follow all instructions** to set up your environment for the
training. Skimming the instructions often leads to errors, so be sure to
read everything.

# Install R and RStudio

This is just like installing any other program.

-   [R](https://cloud.r-project.org/)
-   [RStudio](https://www.rstudio.com/products/rstudio/download/#download)

It is important to have the most recent version of R, which as of this
repo creation was version 4.2.1.

# RStudio Project

I highly recommend using an [RStudio
project](https://support.rstudio.com/hc/en-us/articles/200526207-Using-RStudio-Projects)
(essentially just a folder on your computer to hold the files from
class) to keep yourself organized.

You can either start your own project by clicking `File > New Project`
or follow these instructions to copy the project for this class. You may
need to create a [GitHub
PAT](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
for this to work. Setting up your computer can be difficult, so if this
does not work out for you contact the TA or me to get help. It’s a one
time process so don’t get discouraged.

## Using the RStudio Gui to Copy this Project

This assumes you have `git`
[installed](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

Click `File > New Project`.

![](images/rstudio-project-menu.png)<!-- -->

Click `Version Control`.

![](images/rstudio-create-project.png)<!-- -->

Click `Git`.

![](images/rstudio-create-project-version-control.png)<!-- -->

Choose a folder in the `Create project as a subdirectory of` field.

Paste `https://github.com/jaredlander/cbs2022fall`[^1] in the
`Repository URL` field.

![](images/rstudio-create-project-git.png)<!-- -->

# Install Packages

Once you have a project setup, you can install the add-on packages we
will be using (and explaining) by running this code in the R console.

``` r
install.packages(
    c(
        'here', 'knitr', 'rmarkdown', 'tidyverse', 'usethis', 'tidymodels', 
        'leaflet', 'leafgl', 'glmnet', 'xgboost', 'DiagrammeR', 'coefplot', 
        'flexdashboard', 'xaringan'
    )
)
```

# If it Still Does Not Work

If you are still having trouble setting up the project and getting
everything installed you can sign up for an
[RStudio.cloud](https://rstudio.cloud/) account.

[^1]: Or `git@github.com:jaredlander/cbs2022fall.git` for ssh.
