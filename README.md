# 🧠 Analysis of Demographic and Socioeconomic Impacts on Life Satisfaction

This project investigates the relationship between socioeconomic factors and life satisfaction, focusing specifically on subpopulations within the United States. It uses survey data to explore how race, gender, and demographic variables affect reported happiness and builds insights through exploratory and statistical analysis in R.

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Data_Cleaning.Rmd` | Loads and preprocesses the original dataset, including filtering and renaming |
| `USA_EDA.Rmd` | Conducts exploratory data analysis (EDA) for the full U.S. dataset |
| `USA_White_F.Rmd` | Analyzes life satisfaction trends and factors for White females in the U.S. |
| `USA_White_M.Rmd` | Analyzes life satisfaction trends and factors for White males in the U.S. |

---

## 🔍 Key Themes

- Differences in life satisfaction across race and gender
- Socioeconomic predictors such as income, education, and employment
- Comparative analysis of White females vs. White males in the U.S.
- Visualizations of distributions and group comparisons

---

## 📦 Tools & R Packages Used

- `tidyverse`
- `ggplot2`
- `dplyr`
- `readr`
- `psych`
- `summarytools`

---

## 📈 How to Run

1. Open each `.Rmd` file in **RStudio**
2. Run them in order:
   - `Data_Cleaning.Rmd`
   - `USA_EDA.Rmd`
   - `USA_White_F.Rmd`
   - `USA_White_M.Rmd`

To render as HTML/PDF:

```r
rmarkdown::render("USA_White_F.Rmd")
