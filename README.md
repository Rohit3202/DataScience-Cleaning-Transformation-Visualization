# DataScience-Cleaning-Transformation-Visualization
Data science task covering data cleaning, transformation, and visualizatio
# load the iris dataset
pd = pd.read_csv("iris.csv")
# 1. Inspect the dataset
print("First five rows of the dataset.") print(df.head() print("\nSummary of missing values.") print(df.isnull().sum())
# 2. Handle missing values (if any)
# For demonstration, we'll fill missing values with the median, although iris dataset is usually clean
# 3. Remove duplicates  (if any)
df = df.drop_duplicates()
# Display cleaned data
print("\nData after cleaning:") print(df.info())
