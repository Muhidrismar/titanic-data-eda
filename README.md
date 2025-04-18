# Exploratory Data Analysis: Titanic Dataset

EDA (Exploratory and Explanatory Data Analysis) was performed on the Titanic dataset containing basic passenger information such as name, gender, age, and survival status. The Titanic is one of the most iconic ships in history, and this dataset is widely used as an introduction to data analysis.

The purpose of this analysis is to understand the basic structure of the data and uncover initial insights such as the age distribution of passengers, gender composition, survival rate, and the overall quality of the dataset including duplicates and missing values.

---

## Insights

1. The dataset contains 4 columns and 500 rows.
2. The `Survived` column contains binary values (0 and 1), indicating survival status.
3. The `Age` column contains missing values.
4. `Name` has 499 unique values, indicating one duplicate name.
5. The `Sex` column contains two unique values: male and female.
6. There are more male passengers (288) than female.
7. More than half of the passengers survived.
8. Passenger ages range widely, from infants to the elderly.

---

## Advices

1. Female passengers appear to have higher survival rates — further analysis could explore why.
2. Grouping age ranges (e.g., child, adult, senior) could help in understanding survival patterns.
3. Filling missing `Age` values using median is simple, but using grouped medians (e.g., based on `Sex` or `Survived`) could improve accuracy.
4. Ensure identifiers like `Name` are unique or supported with stronger ID columns in future datasets.

If you have any suggestions or feedback, feel free to reach out to me via LinkedIn:

- [LinkedIn](https://www.linkedin.com/in/muh-idris-mar)
