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
|---------|----------|
| Python    | Data cleaning, analysis , prediction |
| Pandas    | Data manipulaton, data preparation |
| Numpy     | Data loading |           
|Matplotlib | Data visualization |
|Seaborn    |  Data Visualization|
|Scikit-learn| Machine Learning |
 ---
### ▶️ Methodology
#### Step 1: Data Loading and Cleaning 
- Loaded the .csv file into Jupyter notebooks.
-Removed duplicates, handled missing data and ensured numeric fields were properly formatted.
#### Step 2: Data Analysis
##### Exploratory Data Analysis (EDA)
EDA was performed using  correlation heatmaps to understand the relationships between variables, and descriptive statistics to provvide an overview of the dataset.
#### Step 3: Data Visualization
-Created boxplots for `radio`, `TV` and `newspaper` to visualize the distribution of data points.
-Correlation charts to see the relationships of variables in the data.

---
 #### Model Selection
Different models were used to predict sales based on the independent variables.
Random forest and Liner Regression were applied in order to predict sales.
#### Performance Metrics and accuracy evaluation 
|Tool | Accuracy Evaluation | Scores |
|--------|------|-------|
|model   | Mse  |    R^2|
|Linear Model | 3| 0.89|
|Random Forest|1 |0.95|
---
####  :brain: Insights
The Random forest was a better model, with   an accuracy score 95% , indicating a better fit to the data. 


