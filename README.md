# EXNO2DS
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
        ![image](https://github.com/user-attachments/assets/4a15bf22-4fee-449d-8a4e-7c95cd2b5b72)
df.info()
![image](https://github.com/user-attachments/assets/efaad6dd-c72c-42a7-8bfc-e2f5e531ab28)
df.shape
![image](https://github.com/user-attachments/assets/2b4d5e09-a314-40f1-bb57-9fc4c53bbf77)
df.head(4)
![image](https://github.com/user-attachments/assets/37e8a61a-da0a-47cc-9b44-bb766169f487)
df.describe()
df.set_index("PassengerId",inplace=True) df.describe()
![image](https://github.com/user-attachments/assets/af661591-a928-49ea-88f4-837ffbd85864)

# RESULT
        Thus ,the Exploratory Data Analysis on the given data set was performed successfully.
