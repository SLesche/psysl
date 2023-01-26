# psysl
Sven Lesche's R package (includes data and custom functions/templates)

## Installation
This package is (obviously) not available on CRAN and needs to be installed manually on your machine using `devtools::install_github("SLesche/psysl"). After restarting your R-session, all templates, data and function will be available to you.

## Templates
### Rmarkdown
This package contains several templates for `.rmd` files. To generate a new `.rmd` script navigate to `File > New File > R Markdown...` and select `From Template` in the ensuing screen. Then choose the template you want to use.
The following templates are available from this package:
- `minimal`: This template aims to contain only the minimal setup I use for new `.rmd` files. Since I do most of my analysis in R-markdown, I often use `editor_options:chunk_output_type: console` to mimic the console-output used by basic `.r` scripts. This template also generates three beginning chunks `setup`, `function` and `data`.
- `rmd-script-sl`: This template contains commented basic author-information used when knitting this file directly. It also expands on `minimal` by defining a few chunk options such as `echo = TRUE` and setting a seed for all chunks to enable replicable random generation.
