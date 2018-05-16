# The Pleasing Ratio Project

<img width="12%" style="float: left;margin:5px 20px 5px 1px" src="https://upload.wikimedia.org/wikipedia/commons/a/ae/Gustav_Fechner.jpg">

This serious man on the left is Gustav Theodor Fechner, a German philosopher, physicist and experimental psychologist who lived between 1801 and 1887. To be honest, I don't know almost anything of his life or work exepct one thing: he did in the 1860s a *thought-provoking* experiment. It seems me interesting for two important reasons: he called into question something widely established and obtained experimental data by himself.

Fechners's experiment was simpler than this one: he presented just ten rectangles to 82 students. Then he asked each of them to choose the most pleasing one and obtained revealing discoveries I will not explain here since would cause bias in my experiment.

Even my experiment is absolutely inspired by his own one, there are some differences. I can explore a bigger set of ratios doing an A/B test and I introduce the option *I'm not sure*. It makes this one a bit more complex and richer.

The experiment has also interesting technical features: the use of `shinydashboard` package to arrange the App, the use of `shinyjs` package to add javaScript to refresh page when use choose to play again, to save votes in a text file and to read it to visualize results.

You can find more information about the original experiment [here](https://plus.maths.org/content/golden-ratio-and-aesthetics).

Will I obtain the same results as Fechner? 

## Links

The project is available [here](http://91.134.134.147:3838/pleasing-ratio-project)
There is also a post in [Fronkonstin](https://fronkonstin.com/2018/05/15/the-pleasing-ratio-project/) explaining it

## Dependencies

The project is developed in [R](http://www.cran.r-project.org/) with the following packages:

  * [Shiny](http://shiny.rstudio.com/) - To build the web App
  * [shinyjs](https://cran.r-project.org/web/packages/shinyjs/index.html) - To improve the Shiny apps with some JavaScript
  * [shinydashboard](https://cran.r-project.org/web/packages/shinyjs/index.html) - Used to give the App a dashboard appearance
  * [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html) - To create the rectangles

### General Purpose Dependencies

These are dependencies used for internal operations and presentation tasks:

  * [dplyr](https://cran.r-project.org/web/packages/dplyr/index.html)
  * [highcharter](https://cran.r-project.org/web/packages/highcharter/index.html)
  * [markdown](https://cran.r-project.org/web/packages/markdown/index.html)

## Running Instructions

Run the following commands in order to download the project:

```
$ git clone git@github.com:aschinchon/pleasing-ratio-project.git
$ R
```

Once inside R, run the following code (make sure all your dependencies are installed
prior to this):

```r
library(shiny)
runApp("pleasing-ratio-project")
```

If everything goes smoothly, a web browser should open showing the project's
main page.


## Authors

**Antonio Sánchez Chinchón:**

  + [Twitter](https://twitter.com/aschinchon)
  + [Fronkonstin](https://fronkonstin.com/)

The code is licensed under the MIT License and is available in [Github](https://github.com/aschinchon) 
