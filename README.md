# Life Expectancy Dashboard

Interactive dashboard exploring life expectancy trends from 1770 to 2023 across four entities: Chile, the Americas, Europe, and the World.

## Features

- Line chart with hover tooltips showing life expectancy by year and region
- Checkbox filter to select one or more regions
- Year range slider to focus on specific periods
- Synchronized data table that updates with the filters

## Data

Source: Our World in Data. The dataset covers:

- **World**: global average from 1770 to 2023
- **Europe**: regional average from 1770 to 2023
- **Americas**: regional average from 1770 to 2023
- **Chile**: country-level data from 1900 to 2023, with sparse observations before 1950

## Requirements

R packages: `flexdashboard`, `crosstalk`, `plotly`, `DT`

Install with:
```r
install.packages(c("flexdashboard", "crosstalk", "plotly", "DT"))
```

## Usage

Open `ESPERANZA.Rmd` in RStudio and click Knit. This generates `index.html`, which can be opened in any browser or hosted on GitHub Pages.

## Live Dashboard

https://m-apablaza.github.io/life_expectancy/
