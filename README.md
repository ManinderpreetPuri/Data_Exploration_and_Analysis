# Data_Exploration_and_Analysis

Project 1

Task 1 of 4: Data Wrangling:
1 Used “data1”. Performed following tasks:
a. Load the data into code.
b. The data has two columns. 
c. Used the “separate” method to convert the data into the following format:
d. Applied “unite” function to return the data into the original format. 
2 Used “iris.csv”. Performed following tasks:
a. Load the data into code.
b. Applied “gather” function on “iris” data to convert it into the following format:
c. Applied the “spread” function on “iris” data to convert it into the following format 
d. Applied the proper function on “iris” data to return it into the original format.

Task 2 of 4: Data Wrangling
1- Used "house_data". Performed following tasks:
2- The data has 12 columns. Columns 1 to 11 are independent variables (X1 to X11). Column 12 is the dependent variable (Y).
3- Removed inconsistency data from some ROWS. For example, “bathrooms” values should be integers only (for example, 1, 2, 4, 5, ...etc). Removed the row(s) that includes a real value(s). Wrote a code to perform the checking and removing process. 

Task 3 of 4: Univariate Graphs
The dataset for task 3: Mobile dataset
Mobile and technology are one of the world’s biggest industries. Organisation is aiming to 
enter this industry and plans to launch a portfolio of mobiles to compete with the currently 
established manufacturers. The company has collected the production data of mobiles from 
different companies. As a consultant and one of my tasks was to explore the data set and answer 
the following questions.

Dataset Description:
Id Unique ID
battery_power Total energy a battery can store in one time measured in mAh
blue Has bluetooth or not
clock_speed speed at which microprocessor executes instructions
dual_sim Has dual sim support or not
fc Front Camera mega pixels
four_g Has 4G or not
int_memory Internal Memory in Gigabytes
m_dep Mobile Depth in cm mobile_wt 
Weight of mobile phone n_cores 
Number of cores of processor pc 
Primary Camera mega pixels 
px_height Pixel Resolution Height 
px_width Pixel Resolution Width
ram Random Access Memory in Megabytes
sc_h Screen Height of mobile in cm
sc_w Screen Width of mobile in cm
talk_time longest time that a single battery charge will last when you are
three_g Has 3G or not
touch_screen Has touch screen or not
wifi Has wifi or not

For the dataset, completed the following tasks and answered the following questions:
1) Missing Values:
o Are there any anomalies (unusual data or missing values) in the given dataset? 
Are we going to remove the missing values? Support answer with the 
appropriate argument.
2) Do we need to normalise the data? Provide appropriate reasoning.
3) Tabular exploration:
o Created histograms for all variables to visualise.
• Is there any outlier?
• Which attribute does not follow a normal distribution? Explain your answer.
o Computed the descriptive statistics (including mean, median, mode, range, quartiles) and draw a boxplot (in just one graph) of the all variables.
• Presented a summary of your findings by contrasting different features of these distributions
o Categorised Battery attribute on “Low”, “Medium” and “High” and used a bar chart to illustrate the new categories.
o Represented the different of n_cores (in percentage) and draw your findings. Uses a pie chart with labels.

Task 4 of 4: Bivariate
The dataset for task 4: Household data
The household dataset contains sample data from approx. 2000 houses in Australia. It contains 
information regarding income, total taxes, expenses, age, gender, and level of education of the 
head household. It also includes information on the number of children and adults per home.

Dataset Description:
Attributes:
Income
Taxes
Groceries
Meals
Utilities
Cloth
Alcohol
Fuel
Phone
Children
Adults
Ownhouse
Education.level
HH.Age
HH.Gender
Other specifics:
Education P ‘Primary’ S ‘Secondary’ I ‘Intermediate’ B ‘Bachelors’ M ‘Master’
Gender M ‘Male’ F ‘Female’

For the dataset, completed the following tasks and answered the following questions:

1) Data cleaning:
o Are there any anomalies (unusual data or missing values) in the given dataset? 
Are we going to remove the missing values? Support answer with the 
appropriate argument.
2) Do we need to normalise the data? Provided appropriate reasoning.
3) Data visualisation:
o Analysed and illustrated the relationship between Income vs Taxes, and Income vs 
TOTAL Expenditure. Is there any relationship between Taxes and Total expenditure?
Explained the findings.
o Commented on the relationship between variables: Income vs Taxes and Income vs TOTAL 
Expenditure. 
o Visualised the relationship between Ownership and other variables as follows: 
• Draw and explain the relationship between Ownhouse and Income
• Explained the relationship between Ownhouse and Education. Level and Gender
• Draw and explained the frequency Ownhouse attribute.
o Used a proper visualisation method to filter age into: “Less than 25”, “between 25 to 50”, 
“Older than 50”. 
• Plotted total expenses by “Less than 25”, “between 25 to 50”, “Older than 50”. 
• Plotted income vs age 
• Contrasted the two plots and explain the findings
