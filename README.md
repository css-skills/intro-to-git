## Overview

[Git](https://git-scm.com/) is a common tool in software development for version control, while [GitHub](https://github.com/) is a cloud-based service that works in conjunction with the Git software to facilitate version control and collaboration. These tools can be used to improve data science workflows and computationally-enhanced research projects. However the learning curve for Git is quite steep, and often individuals are left to learn Git on their own with little explicit instruction. In this workshop we will introduce Git/GitHub and practice common workflows.

## Objectives

- Identify the value of version control software for data science projects
- Create repositories
- Make commits and synchronize repositories
- Implement collaborative workflows using branches and forks
- Generate pull requests

## Audience

This workshop is designed for individuals with introductory-to-intermediate experience programming in a language such as Python or R.

## Location

Room 295 in [1155 E 60th St](https://goo.gl/maps/7n7wDsd9mjnfRBtR8).

## Prework

On the day of the workshop, please plan to work from a laptop that has the following installed:

- A recent version of R (>=4.1.0), which is available for free at https://cloud.r-project.org/
- The most recent version of the RStudio Desktop Integrated Development Environment (IDE version 2022.02.0+443), available for free ([RStudio Desktop Open Source License](https://www.rstudio.com/products/rstudio/download/#download)).
- The R packages we will use, which you can install by connecting to the internet, opening RStudio, and running at the command line:

    ```r
    install.packages(c("usethis", "gitcreds", "gh"))
    ```

- Restart your R session before using any newly installed packages

We will be using GitHub in this workshop for version control and publishing. Sign up for a free GitHub.com account at <https://github.com/join> if you don't already have one.

## Additional resources

- [Slides from the workshop](https://css-skills.github.io/intro-to-git/slides/)
- [*Happy Git and GitHub for the useR*](https://happygitwithr.com/) by Jenny Bryan, the STAT 545 TAs, and Jim Hester - a comprehensive guide to "git"-ing started with Git, GitHub, and R/RStudio. Covers more complicated scenarios and workflows than we have time to cover in this workshop.

