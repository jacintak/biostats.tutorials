# Introduction

These are `learnr` tutorials about statistics and computation in R. They are a collection of materials based on activities delivered to undergraduates with the aim to supplement main concepts in biostatistics or explore a concept in more detail or revising fundamentals for postgraduates.

**This package is in active development**.  
Any suggestions or feedback are welcome.

***

# Developer notes

## v0.1.0

Initial tutorials:

  * Modelling assumptions
  * Simple linear regression
  * Model selection
  
## v0.2.0 - Added praise and encouragement

## v0.3.0 - Added Bootswatch HTML panels for emphasis
 
***

# Set up

Welcome! We need to set up our computer to start using tutorials in R. 

The tutorials require R version 4.0 or above & RStudio version 1.0.136 or above. Please update your software if required.

The tutorials need the following packages installed:

  * `learnr` - needed to run the tutorials
  * `remotes` - needed to install the tutorials

Use `install.packages("<name of packages>")` to install them if you have not already.

If everything worked then you should see a Tutorial tab in one of your RStudio windows (perhaps next to Environment and History). There should be some tutorials listed there already.

***

# Installing the `biostats.tutorials` package

The `biostats.tutorials` package are available on GitHub.  
Run the following code:

```
remotes::install_github("jacintak/biostats.tutorials")
```

***

# Running a tutorial

You can run a tutorial directly from the Tutorial tab.

Click "**Start Tutorial**" to open the tutorial. It make take time to load, you only need to press the button once. 

Once the tutorial had loaded, you can resize the window or you can click the "Show in new window" icon to open it in another window. Press the "Stop" icon to stop the tutorial. Press the "Home" icon to return to the Tutorials tab.  

If that doesn't work use this code and the tutorial will open in another window:

```
learnr::run_tutorial("<insert name of the tutorial to run>", package = "biostats.tutorials")
```

If neither works, check the `biostats.tutorials` package installed properly.  
***

# Troubleshooting

If the tutorial fails to open but has opened in the past, navigate to the package folder of the tutorial in question and delete the html file and the folder ending in "_files". *Do not delete the ".Rmd" file*. Restart RStudio and try opening the tutorial again.

Else, reinstall the tutorial using the code above.