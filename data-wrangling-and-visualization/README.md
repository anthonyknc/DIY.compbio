# My Go-To Software for Data Wrangling & Visualization

# **IDE**

-   [Positron](https://github.com/posit-dev/positron): A next-generation data science IDE with first-class support for both Python and R, developed by [Posit](https://posit.co/).
    -   Resources:
        -   [Download Positron Pre-releases](https://github.com/posit-dev/positron/releases) by Posit
        -   [Positron Wiki](https://github.com/posit-dev/positron/wiki) by Posit
        -   [Keyboard Shortcuts](https://github.com/posit-dev/positron/wiki/Keyboard-Shortcuts) by Posit

## Python

-   [Polars](https://pola.rs/): A [lightning-fast](https://duckdblabs.github.io/db-benchmark/) dataframe package for data wrangling.
    -   Resources:
        -   [Official Polars User Guide](https://docs.pola.rs/)
        -   [Modern Polars](https://kevinheavey.github.io/modern-polars/) by Kevin Heavey
        -   [Polars Cheatsheet](https://github.com/FranzDiebold/polars-cheat-sheet) by Franz Diebold
        -   [40+ Pandas Functions & their Polars Equivalence](https://www.kaggle.com/code/suraj520/40-pandas-functions-their-polars-equivalent/notebook) by suraj520
-   [Plotnine](https://plotnine.org/): A faithful port of R's elegant plotting library, [ggplot2](https://ggplot2.tidyverse.org/index.html), to Python based on the grammar of graphics.
    -   Resources:
        -   [Official Plotnine API Reference](https://plotnine.org/reference/)
        -   [Data Visualization with PlotNine](https://f0nzie.github.io/rmarkdown-python-plotnine/) by Jeroen Janssens
        -   [Plotnine Examples](https://github.com/has2k1/plotnine-examples) by has2k1
        -   [Plotnine: ggplot in python](https://python-graph-gallery.com/plotnine/) by Yan Holtz
-   [Plotly](https://plotly.com/python/): A interactive graphing library for Python.
    -   Resources:
        -   Official `plotly.express` [API Reference](https://plotly.com/python-api-reference/plotly.express.html)
        -   Official `plotly.graph_objects` [API Reference](https://plotly.com/python-api-reference/plotly.graph_objects.html)
        -   Official `plotly.subplots` [API Reference](https://plotly.com/python-api-reference/plotly.subplots.html)
        -   Official `plotly.io` [API Reference](https://plotly.com/python-api-reference/plotly.io.html)
        -   [Interactive charts with Plotly](https://python-graph-gallery.com/plotly/) by Yan Holtz
-   [Shiny](https://shiny.posit.co/py/): Effortless Python web applications with the power of reactive programming, available for both Python and R.
    -   Resources:
        -   Official `shiny.express` [API Reference](https://shiny.posit.co/py/api/express/)
        -   [Shiny for Python Cheatsheet](https://rstudio.github.io/cheatsheets/html/shiny-python.html) by Posit
        -   [Shiny for Python Community Forum](https://forum.posit.co/tags/c/shiny/8/python) by Posit
-   [Quarto](https://quarto.org/): A powerful open-source scientific and technical publishing system. Dynamic content can be created with Python, R, Julia, and Observable using Quarto.
    -   Resources:
        -   [Official Quarto Guide](https://quarto.org/docs/guide/)

## R

-   [Tidyverse](https://www.tidyverse.org/): A collection of R packages dedicated to data science. Tidyverse rules the world of R programming. Its philosophy inspired the conception of the machine learning framework, [tidymodels](https://www.tidymodels.org/), and the bioinformatic framework, [tidyomics](https://www.nature.com/articles/s41592-024-02299-2). Tidyverse consists of 8 core packages: [ggplot2](https://ggplot2.tidyverse.org/), [dplyr](https://dplyr.tidyverse.org/), [tidyr](https://tidyr.tidyverse.org/), [readr](https://readr.tidyverse.org/), [purrr](https://purrr.tidyverse.org/), [tibble](https://tibble.tidyverse.org/), [stringr](https://stringr.tidyverse.org/), and [forcats](https://forcats.tidyverse.org/), which share an underlying design philosophy, grammar, and data structures for data wrangling and visualization.
    -   Resources:
        -   [Posit Cheatsheets](https://posit.co/resources/cheatsheets/) by Posit
        -   [R for Data Science (2e)](https://r4ds.hadley.nz/) by Hadley Wickham, Mine Cetinkaya-Rundel, and Garrett Grolemund
        -   [Statistical Inference via Data Science: A ModernDive into R and the tidyverse](https://www.moderndive.com/) by Chester Ismay and Albert Y. Kim
        -   [ggplot2: Elegant Graphics for Data Analysis (3e)](https://ggplot2-book.org/) by Hadley Wickham, Danielle Navarro, and Thomas Lin Pedersen
-   [Duckplyr](https://duckdblabs.github.io/duckplyr/): A drop-in replacement for [dplyr](https://dplyr.tidyverse.org/) that uses [DuckDB](https://duckdb.org/) as a backend for fast operation.