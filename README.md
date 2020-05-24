# Exploring The Simpsons Show

This repository dives deep into the world of [The Simpsons](https://en.wikipedia.org/wiki/The_Simpsons). We use the data sets available at the data science platform [Kaggle](https://www.kaggle.com/prashant111/the-simpsons-dataset) and the \#tidytuesday [Github repository](https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-08-27), which contain a variety of information on the show, including script lines, IMDb ratings, TV views, guest star appearances, and much more.

<img src="Images/simpsons_image.png" width = "150">

## Description

The repository contains a notebook illustrating exploratory and text analyses of the resources above. In particular,

* **Exploratory data analysis**: this allows us to discover, among other things, the most popular characters, the locations where they usually interact, how the ratings and views have evolved across almost 30 seasons, and whether the appearance of guest stars has had any impact on the show ratings.

* **Text analysis**: the availability of the script lines allows up to plunge into The Simpsons' world, and investigate the most recurrent and peculiar (as measured by tf-idf) words and bigrams, and the underlying sentiments. Through a Latent Dirichlet Allocation (LDA) analysis, we can uncover the main topics of the show, such as family, school, social life, and work relationships.

## Usage

The analysis code is contained in the R Markdown report `exploring-simpsons.Rmd`. 

If you just what to have a look at the rendered notebook, please refer to `exploring-simpsons.html`.

The HTML outlook of the report can be changed by editing the `custom.css` file, which is itself a modified version of the [`readthedown` format](https://github.com/juba/rmdformats).

All the data sets employed for the analyses are collected for convenience in the `Data` folder.

## Other

Suggestions and feedback are welcome!