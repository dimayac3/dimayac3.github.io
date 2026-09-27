# dimayac3.github.io

## About

This repository contains my website with blog posts, as well as relevant files to run both python and R scripts.

## Installation

To access the documents within this repository, the following must be installed:

Quarto: quarto version 1.10.18
UV: uv 0.12.5
R: R version 4.6.1

## Instructions
1. Clone the repository: open your computer terminal and run the following:

```{bash}
git clone https://github.com/dimayac3/dimayac3.github.io.git
```

2. Enter repository: run in terminal:

```{bash}
cd dimayac3.github.io
```

3. Sync Python environment: run in terminal:

```{bash}
uv sync
```

4. Sync R environment: run the lines in terminal to open R, restore the correct environments, then quit R in terminal:

```{bash}
R
```

```{bash}
renv::restore()
```

```{bash}
q()
```

5. Render website through Quarto: run in terminal:

```{bash}
uv run quarto render
```

6. Preview website through Quarto: run in terminal:

```{bash}
uv run quarto preview
```

## Data Citations

The data being manipulated in the posts are from the Palmer Penguins dataset, loaded in from base R 

(Horst AM, Hill AP, Gorman KB (2020). palmerpenguins: Palmer
Archipelago (Antarctica) penguin data. R package version 0.1.0.
https://allisonhorst.github.io/palmerpenguins/. doi:10.5281/zenodo.3960218.)