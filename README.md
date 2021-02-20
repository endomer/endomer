
<!-- README.md is generated from README.Rmd. Please edit that file -->

# endomer

<!-- badges: start -->

[![R build
status](https://github.com/endomer/endomer/workflows/R-CMD-check/badge.svg)](https://github.com/endomer/endomer/actions)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/endomer)](https://CRAN.R-project.org/package=endomer)
[![Codecov test
coverage](https://codecov.io/gh/endomer/endomer/branch/main/graph/badge.svg)](https://codecov.io/gh/endomer/endomer?branch=main)
<!-- badges: end -->

El objetivo de este paquete es el de proveer funciones comunes a todos
los paquetes del econsistema endomer.

## Instalación

endomer se instala cuando instalas otro de los paquetes del ecosistema.

<!-- You can install the released version of endomer from [CRAN](https://CRAN.R-project.org) with: -->
<!-- ``` r -->
<!-- install.packages("endomer") -->
<!-- ``` -->

endomer no está dispobible en CRAN. Pero puedes instalar la versión de
desarrollo desde [GitHub](https://github.com/) con:

``` r
tryCatch(
  library(remotes),
  error = function(e){
    install.packages('remotes')
  }
)
remotes::install_github("endomer/endomer")
```

## Contribuye

Tienes comentarios o quieres contribuir?

Por favor, revisa las [gias de contribución (en
inglés)](https://endomer.github.io/endomer/CONTRIBUTING.html) antes de
iniciar un issue o pull request.

Por favor, observa que el proyecto endomer está sujeto a un [Código del
contribuyente](https://contributor-covenant.org/es/version/2/0/CODE_OF_CONDUCT.html).
Contribuyendo con el proyecto aceptas las términos y condiciones.