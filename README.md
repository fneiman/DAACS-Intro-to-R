# DAACS-Intro-to-R
This repository contains the materials for the DAACS Summer School 2021 lessons on Introduction to R and R Studio. It is meant to be followed through as the lesson and then reviewed later as reference materials.

## Goals
Everyone will:
1. leave the lesson with a functional R environment using RStudio.
2. be comfortable or at least on their way to being comfortable with R and Rstudio.
3. be equipped to find solutions to the problems they encounter using R.

### Quick Poll
1. Everyone raise your hand
2. Lower your hand if you started programming within the last 5 years
3. Lower your hand if you started programming in the last 10 years
.....

Everyone look at the last person with their hand up

# Part I: Getting up and Running
In this part we will spend our time getting our R and Rstudio environments up and running.
## Installation
1. Go [here to download R and RStudio](https://www.rstudio.com/products/rstudio/download/#download) - **NB** They are separate downloads and installs
2. Alternatively [make an account on RStudio Cloud](https://rstudio.cloud/)
## Orientation
1. Pete will lead a guided tour of RStudio - (core takeaway: type code into console and see what happens)
2. Everyone else will interrupt Pete with questions
## Environment Test
1. write our first program - 'hello world'
2. working directories and paths and files ..... oh my.

# Part II: The building blocks
In this part we will get to know the main R building blocks: Functions, Packages, Variables, and Data Structures. More importantly we will learn some R helpers, double most importantly '?'.

## Functions
In R a function is your main tool. Every function is designed to do one specific thing and hopefully has a name that makes it clear what the function does.

**For example** there is a function called 'c'. **facepalm emoji** I would argue that it is impossible to guess what that function does from its name. Let's introduce our first R helper. '?'

### Exercise
1. Enter `?c`
2. Read the Description from the documentation
3. Answer the question to yourself, "Did that description make me more or less confused?"
    * if you are less confused ask yourself "What does this function do?"
    * if you are more confused make a note of your new questions

### Exercise
Let's take a swing at a different function: sum(...)
1. Enter `sum(1,2,3,4)`
2. What does R return?
3. Is this what you expected?
4. Investigate sum, enter `?sum`

### Exercise: Recognizing functions in the wild
In this exercise we will attempt to do one thing. Find functions in code. Fortunately there is a feature that makes functions stick out. When you use a function it is a name followed immediately by a '('.

For Example:
* c(1,2,3)
* sum(1,2,3)
* EstimateMCD(dataForMCD$unitData, dataForMCD$typeData)

Everytime a function is used there is a name followed by a '('

Now let's go hunting

1. Click on this link ---> [link](https://github.com/TJF-Monticello/Chronology/blob/master/MCD-CA%20Code/CA_MCD_URCode.R)
2. Read the code but don't try to understand anything, just identify functions. For everyone you see write down the line number and the function
    * eg: line 10, library
    * eg: line 11, library
    * eg: line 33, dbGetQuery

3. Ask yourself, what percent of lines in this code have a function?


That's the thing about R programming. Everything you do is a function. (for the nerds: we call R programming 'functional')


## Packages (aka bundles of functions)
1. WWWWWH
2. Installing
3. Using
4. Leading activity 2
### Jargon Corner
Base R vs TidyR
## Variables
1. WWWWWH
2. Leading activity 3
## Data Structures
1. WWWWWH
2. Leading activity 4

# Part III: Write a script to do a scientific task
For this part everyone breaks up into pairs and tackles different scientific tasks.

## Definitions
1. R - A programming language designed for statistical computing ([top 15 of all programming languages](https://www.tiobe.com/tiobe-index/)) - debut 1993, "next generation S"
11. The R foundation - The organization that governs R development - [link](https://www.r-project.org/foundation/)
2. RStudio, software - The premire IDE for R: public beta (2011), version 1.0 (2016), current version 1.4.
10. RStudio, PBC - RStudio Public-benefit corporation - They govern development of RStudio - [link](https://www.rstudio.com/about/)
3. RStudio Desktop - What most people install on their computer (including laptops)
4. Rstudio Cloud - What most people use for a cloud based R environemnt
5. IDE - Integraded Development Environment - RStudio is an IDE - [link](https://en.wikipedia.org/wiki/Integrated_development_environment)
6. CRAN - Comprehensive R Archive Network - the central repository for R software - ie packages/libraries/etc.
7. Packages aka Libraries - code written by others that is easy for you to use - aka they reason why R is popular
8. Tidyverse - A collection of R packages - focuses on 'making data tidy' and 'using tidy data' (Pete has a mini rant on this if you are inclined to hear about it) 
9. RMarkdown - along with project jupyter one of the biggest bane's in Pete's teaching career
10. knitr - an R package to integrate with things like LaTeX, HTML, Markdown, etc.

## Resources
* [R wikipedia page](https://en.wikipedia.org/wiki/R_(programming_language))
* [RStudio wikipedia page](https://en.wikipedia.org/wiki/RStudio)
* [R and Rstudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* [Rstudio cloud](https://rstudio.cloud/)
* [Working directory wikipedia page](https://www.rstudio.com/products/rstudio/download/#download)
* [R for Data Science](https://r4ds.had.co.nz/) - The "best" book for learning R
* [Software Carpentry Introduction to R and Rstudio](https://swcarpentry.github.io/swc-releases/2016.06/r-novice-gapminder/01-rstudio-intro/)

# License
![](https://github.com/alonzi/DAACS-Intro-to-R/blob/main/2880px-Cc-by-nc-sa_icon.svg.png)
