import pandas as pd
# read a csv file
df = pd.read_csv('/content/sample_data/california_housing_test.csv')
df.head(7)
df.describe()
df.hist
