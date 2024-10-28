# PMLAssignment

#### Lyn Yang
#### Oct 27, 2024

## Title:Practical Machine Learning Project
## Synopsis: This data analysis uses data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants to predict the manner in which they did the exercise

### Data Processing:
#### Loading the data & necessary files:
```{r, echo=TRUE, cache=TRUE}
library(lattice)
library(ggplot2)
library(caret)
library(kernlab)
library(rattle)
library(corrplot)
set.seed(1234)
```
