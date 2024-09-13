# tok.fr

<!-- badges: start -->

<!-- badges: end -->

Le paquet d'internationalisation de **{tok}** en français (fr)

## Installation

Vous pouvez installer la version de development de **{tok.fr}** depuis [GitHub](https://github.com/) via:

``` r
# install.packages("devtools")
devtools::install_github("eliocamp/rhelpi18n")
devtools::install_github("cregouby/tok.fr")
```

## Exemple

Voici comment utiliser {tok} avec l'aide en français :

``` r
# configure la session en langue française
Sys.setenv(LANGUAGE = "fr")

# charge la librairie tok en traduction française et {tok}
library(tok.fr)
library(tok)

# consulte l'aide normalement
?transform_affine
```

![exemple de page de documentation en français dans l'onglet Help de RStudio](images/clipboard-3327763328.png)
