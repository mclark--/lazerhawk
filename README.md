# lazerhawk


## Package description
This package has a few miscellaneous functions useful to me, and which might be useful to others. It will be added to over time, and likely will have functions from all over the place as far as utility is concerned.  Nothing extraordinarily unique is here at present, more or less tweaks/variations of available R functions that do almost what I want, but not quite.  Also, I wanted to learn more about building packages, and this is my first foray into that world.  Very little testing of the functions has been done at this point, but the package itself would pass on CRAN, and testing will continue to expand.  Feel free to note issues if you use it.

I was listening to [Lazerhawk](http://lazerhawk.bandcamp.com/album/redline) at one point while creating it, hence the name, and which I can suggest is decent to listen to for programming, but to each their own in that regard.

## Installation
The usual github installation. **devtools** package required.

```{r}
devtools::install_github('m-clark/lazerhawk')
```

## Functions
### corrheat
A copy of [d3heatmap](https://github.com/rstudio/d3heatmap) specifically for correlation matrices, with a measurement focus.  Currently requires d3heatmap.

### createCorr
A function to create a correlation matrix. Useful, for example, in setting up simulations.

### lowerTri, upperTri
Return a triangular matrix, with some options on what specifically is returned.

### describeAll
A summary function for mixed data types that provides the information I usually want.

### pairwise
Apply an arbitrary function to pairwise combinations of rows or columns.

### createAdjacency, createEdges
Create an adjacency matrix, or use one to create an edge list.

### ggClean, theme_trueMinimal
Clean up your ggvis or ggplot visualizations.

## Addins
### insertImgCenterAddin 
For Rmarkdown files, inserts `<img ...>` with centered options filled in.

### insertSpanAddin 
For Rmarkdown files, inserts `<span class=''>`.


## Release Notes
- 0.1.0 Initial release
- 0.1.1 Added createAdjaceny and createEdges, and start of addins
- 0.1.2 Added clean themes for ggvis and ggplot
- 0.1.3 Addins for span, slide
- 0.1.4 Updates to corrheat to use psych package
- 0.1.5 Added plotly theme, modified help

