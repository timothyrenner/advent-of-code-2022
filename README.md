# [Advent of Code 2022](https://adventofcode.com/2022)

With DuckDB and SQL.

## Setup

You need: [conda](https://docs.conda.io/en/latest/miniconda.html) and [Quarto](https://quarto.org/docs/get-started/).

Once you have those set up, create the environment.

```
conda env create -f environment.yml
```

Installing [DuckDB](https://duckdb.org/) needs to be done within R, conda can't do this one for us.

```r
install.packages("duckdb")
```

It'll take a while to install most likely cause it has to compile.

From there cd into the directory you want to work and fire up Quarto to render the documents.