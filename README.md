
# rmedicine

This is a test package built during the workshop  *R package development with GitHub Pages and pkgdown* 
by [Melissa Van Bussel](https://github.com/melissavanbussel) at the
[R/Medicine conference](https://rconsortium.github.io/RMedicine_website/) 2025.

**Course material** can be found here:

* Slides: https://melissavanbussel.github.io/rmedicine/slides.html#/title-slide
* GitHub: https://github.com/melissavanbussel/rmedicine/tree/main


## Most important functions to remember

`library(devtools)`
`library(usethis)`
`library(testthat)`

- `use_readme_md()`: will open and README.md, which will be the homepage of the pkgdown site
- `use_r("my_function_name")`: will open up a file in the R folder with the name of the function
- `use_test("my_function_name")`: will create test file for the function
- `check()`: ...
- `use_git()`: initializes git repo
- `use_github()`: creates a github repo automatically and pushes everything
- `use_pkgdown_github_pages()`: makes pkgdown page and pushes it to github site
- `build_site()`: build pkgdown site locally --> important for development



# rmedicine <a href="https://serigra.github.io/rmedicine/"><img src="man/figures/logo.png" align="right" height="120" alt="rmedicine website" /></a>
<!-- badges: start -->
<!-- badges: end -->


## Installation

You can install the development version of rmedicine like so:

``` r
# FILL THIS IN! HOW CAN PEOPLE INSTALL YOUR DEV PACKAGE?
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(rmedicine)
## basic example code
```

