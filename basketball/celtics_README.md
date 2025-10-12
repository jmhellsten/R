# Boston Celtics 2021-22 Season Analysis

Analysis of Boston Celtics player performance during the 2021-22 NBA season.

## Dataset

**Source:** [Sports Analytics with R](https://github.com/bkrai/Sports-Analytics-With-R)
- **Repository:** bkrai/Sports-Analytics-With-R
- **File:** 2022BOS.csv
- **Observations:** 884 player-game records
- **Season:** 2021-22 NBA Regular Season
- **Team:** Boston Celtics
- **Description:** Individual player statistics for every game played by Boston Celtics players during the 2021-22 season

  **Data URL:https://raw.githubusercontent.com/bkrai/Sports-Analytics-With-R/main/2022BOS.csv**

## Key Analyses

### Player Performance
- Jayson Tatum averaged **26.9 points per game** (team leader)
- Tatum scored **28.5 PPG in wins** vs **24.1 PPG in losses**
- Robert Williams III had the highest Effective Field Goal % (**73.6%**)

### Team Statistics
- **569 wins** vs **315 losses** across all player-games
- Positive correlation between minutes played and points scored
- Plus/minus differential analysis by game outcome

## Visualizations

### 1. Opponent Distribution
Pie chart and bar plot showing games played against each NBA team.

### 2. Points Distribution
Histogram of points scored per player per game.

### 3. Minutes vs Points
Scatter plot with regression line showing strong positive correlation.

### 4. Player Efficiency
Bar chart comparing Effective Field Goal percentage across players.

### 5. Box Plots
Point distributions by player and game outcome (Win/Loss).

### 6. Correlation Matrix
Heatmap showing relationships between shooting statistics.

## Key Findings

- Strong positive correlation (**r = 0.68**) between minutes played and points scored
- Players scored more points in wins vs losses
- Field goal attempts highly correlated with minutes played (**r = 0.73**)
- 3-point shooting percentage shows moderate correlation with overall points

## Technologies

- R 4.5.1
- dplyr (data manipulation)
- ggplot2 (visualization)
- corrplot (correlation matrices)
- psych (statistical analysis)
- ggExtra (marginal plots)

## Code

See [analysis.R](analysis.R) for complete analysis code.

## How to Run
```r
# Load required packages
library(dplyr)
library(ggplot2)
library(corrplot)
library(psych)
library(ggExtra)

# Load data
bos <- read.csv('https://raw.githubusercontent.com/bkrai/Sports-Analytics-With-R/main/2022BOS.csv')

# Run analysis
source("analysis.R")
