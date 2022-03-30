import pandas as pd

df = pd.read_csv('https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data')
df.head()

df.head()

df.shape

df.describe()

import seaborn as sns
outlier=df.drop([59,14,31,32])
sns.boxplot(x=outlier['sepal_width'])

#sns.set_theme(style="")
ax=sns.boxplot(x=df['petal_length'])
