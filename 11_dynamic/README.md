# Dynamic documents

## Compile from the command line

| Directory      | Shell command                                    |
| -------------- | ------------------------------------------------ |
| `01_sweave`    | `R CMD Sweave --clean --pdf analysis.Rnw`        |
| `02_knitr`     | `Rscript -e "knitr::knit2pdf('analysis.Rnw')"`   |
| `03_rmarkdown` | `Rscript -e "rmarkdown::render('analysis.Rmd')"` |
| `04_quarto`    | `quarto render analysis.qmd`                     |
