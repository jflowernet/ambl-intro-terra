# Introduction to rasters with `terra`

This workshop will provide you with an introduction to manipulating raster spatial data using the R package `terra`. `terra` and its predecessor, `raster` are widely used for spatial data manipulation in R. No prior experience of spatial data is assumed, but this short workshop will not have time to delve into some important aspects of spatial data such as projections. 

`terra`'s predecessor `raster` had many of the same functions as `terra`, and I will mention how functions have changed or been renamed which might be helpful for people migrating from using `raster`. In the words of the creator of both packages: `terra` is simpler, faster and can do more, so definitely switch to `terra` if you are still using `raster`!

## Prerequisites 

You will need the `terra` package installed, which can be done by running `install.packages("terra")`. If you have problems, there are more details about installing it [here](https://rspatial.github.io/terra/index.html). I will also show how to make an interactive map with `terra`, which requires the `leaflet` package to be installed; `install.packages("leaflet")`. 

You will also need to have the data within this repository. You can do one of the following depending on how comfortable you are with Github:

- Fork this repository using the grey "Fork" button on this page. This will create your own copy of this repository which has all the data and code. More details on how to fork [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
- Download the data to somewhere on your computer that you will be able to access during the workshop. The data are in a zip file [here](https://github.com/emlab-ucsb/intro-terra/blob/main/data/data.zip); use the "Download raw file" icon (arrow pointing down) in the top right of that page. Once you have downloaded the data, unzip it, and make sure you know the path to the folder with all the data, e.g. "Documents/workshop_data/", so you can load the data during the workshop.

The workshop website is shown on the right hand side of this page
