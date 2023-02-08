# :mortar_board: Git for R User <img src="img/presentation-logo.png" height="120" align="right"/>



[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://choosealicense.com/licenses/mit/)



Code used to create the online presentation **Git for R User** available at:
[**frbcesab.github.io/git-for-r-user**](https://frbcesab.github.io/git-for-r-user)


<br>


### How to contribute

First install required R packages listed in the 
[`DESCRIPTION`](https://github.com/frbcesab/git-for-r-user/blob/main/DESCRIPTION)
file.

```r
## Install 'remotes' package (if necessary) ----
install.packages("remotes")

## Install required packages ----
remotes::install_deps()
```

<br>

Then, edit the 
[`index.qmd`](https://github.com/frbcesab/git-for-r-user/blob/main/index.Rmd) 
file. To update the `html` presentation, run: 

```r
## Render HTML presentation ----
quarto::quarto_render("index.qmd")
```


<br>


## Citation

Please cite this presentation as:

> Casajus N (2023) git-for-r-user: A gentle introduction to git for R user. 
URL: <https://frbcesab.github.io/git-for-r-user>.


<br>


## Code of Conduct

Please note that the `git-for-r-user` project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
