# demo-rmd-penguins

An parameterized RMarkdown report!

![](report/imgs/report-screenshot.png)

## Usage

To render the report run:

```r
knit_with_parameters("~/projects/demo-rmd-penguins/report.Rmd")
```

## Deployment

To deploy the report to RStudio Connect:

```r
rsconnect::writeManifest("report")
```

Then commit any changes to GitHub.
