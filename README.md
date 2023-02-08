<h1 align="center">
  <br>
  <a href="https://frbcesab.github.io/git-for-r-user"><img src="img/git-logo.png" alt="Logo" width="200"></a>
  <br>
  Git for R Users
  <br>
</h1>

<h4 align="center">A gentle introduction to git for R users
<br>
<a href="https://frbcesab.github.io/git-for-r-user" target="_blank"><b>frbcesab.github.io/git-for-r-user</b></a></h4>

<p align="center">
  <a href="https://quarto.org/">
    <img src="https://img.shields.io/badge/Made%20with-Quarto-blue.svg" alt="Quarto">
  </a>
  <a href="https://choosealicense.com/licenses/mit/">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License MIT">
  </a>
</p>

<p align="center">
  <a href="#contribute">Contribute</a> •
  <a href="#citation">Citation</a> •
  <a href="#code-of-conduct">Code of Conduct</a>
</p>

![screenshot](img/markdownify.gif)


<br>


## Contribute

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
