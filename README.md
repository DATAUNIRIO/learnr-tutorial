# Create and serve `learnr` tutorials using Binder
https://syoh.org/learnr-tutorial/

## Interactive Tutorials for R with `learnr`

[**learnr**](https://rstudio.github.io/learnr/) packages are for creating R tutorials with shiny apps running under the hood. Normally, running them require you to run a server or purchase [shiny apps](https://www.shinyapps.io) hosting service.

However, Binder service can provide an alternative. Following are two examples of `learnr` tutorials running on Binder.

## “Hosting” Interactive Tutorial with Binder
Binder is a flexible platform to reproduce a computational environment. You can read more about Binder on The Turing Way (an online book for research computing that I find super useful).
For example, Binder can start a Rstudio session with cloned contents of a GitHub repository, and start a Shiny app for you.

shiny/test1: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/syoh/learnr-tutorial/master?urlpath=shiny/test1/)

shiny/test2: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/syoh/learnr-tutorial/master?urlpath=shiny/test2/)

## Developing/Troubleshooting Tutorials

The Binder image has Jupyter notebook with R and RStudio installed. Rstudio can be invoked to develop and troubleshoot tutorials. Following Binder links will show you how to get to these endpoints

R + Jupyter notebook: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/syoh/learnr-tutorial/master?filepath=index.ipynb)

RStudio: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/syoh/learnr-tutorial/master?urlpath=rstudio)
