### Probem statement
A company that advertises its products on different platforms would like to know which marketing strategy is more effective, and how to capitalize on this strategy.By predicting future sales, they can better leverage these predictions from the analysis,and  optimize their advertising strategies and maximize sales potential.

----

### Sales prediction using python
Project entails using machine learning model for sales prediction  model.
Sales foreacasting usually takes into account various factors such as advertising expenditure, target audience segmentation, and advertising platform selection. 

---
In this case, I'll be using advertising platform selections such as tv and radio.
### :scroll: Data Description
The dcanataset consists of four columns:
- `TV`:  TV advertisements
- `Radio`:  Radio advertisements
- `Newspaper`:  Newspaper advertisements
- `Sales`: The number of units sold
---
### :hammer_and_wrench: Tools used
| Tool | Purpose |
|----------|----------|
| Python    | Data cleaning, analysis , prediction |
| Pandas    | Data manipulaton, data preparation |
| Numpy     | Data loading |           
|Matplotlib | Data visualization |
|Seaborn    |  Data Visualization|
|Scikit-learn| Machine Learning |
 ---
### :Yellow Right-Pointing Triangle: Methodology
#### Step 1: Data Loading and Cleaning 
- Loaded the .csv file into Microsoft Excel.
Standardized values across categories to prevent inconsistencies (e.g., consistent naming of states and call reasons).
Removed duplicates and ensured numeric fields were properly formatted.
Created helper columns where necessary for categorization and aggregation.
### Exploratory Data Analysis (EDA)
EDA was performed using  correlation heatmaps to understand the relationships between variables, and descriptive statistics to provvide an overview of the dataset.
### Data cleaning & Validation
 Data cleaning was done by handling missing values, outliers and finaly checking for the accuracy of the data.
 #### Model Selection
Different models were used to predict sales based on the independent variables.
Random forest and Liner Regression were applied in order to predict sales.
#### Performance Metrics and accuracy evaluation 
The linear model had an  Mean Squared Error (MSE) of 3   and an R-Squared Scorered Error (R^2) of 0.89.
The random forest had an  Mean Squared Error (MSE) of 1   and an R-Squared Scorered Error (R^2) of 0.95.
#### Interpretation 
Random forest was a better model, with   an accuracy score 95% , indicating a better fit to the data. 


