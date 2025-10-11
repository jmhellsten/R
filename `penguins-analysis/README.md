# Palmer Penguins Analysis

Detailed exploratory data analysis of penguin measurements from Palmer Station, Antarctica.

## Dataset
- **Source:** palmerpenguins R package
- **Observations:** 344 penguins
- **Species:** Adelie, Chinstrap, Gentoo

## Visualizations

### Bill Dimensions
![Bill Dimensions](penguin_bill_dimensions.png)

Scatter plot showing the relationship between bill length and depth across species.

### Body Mass Distribution
![Histogram](penguin_body_mass_histogram.png)

Histogram displaying body mass distribution for each penguin species.

### Body Mass Comparison
![Boxplot](penguin_body_mass_boxplot.png)

Box plot comparing body mass across the three species.

## Key Findings
- Gentoo penguins are the largest species
- Strong correlation between flipper length and body mass
- Distinct bill patterns per species

## Code
See [analysis.R](analysis.R) for complete analysis code.

## How to Run
```r
install.packages(c("palmerpenguins", "ggplot2"))
source("analysis.R")
