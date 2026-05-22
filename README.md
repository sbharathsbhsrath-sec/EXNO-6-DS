# EXNO-6-DS-DATA VISUALIZATION USING SEABORN LIBRARY

# Aim:
  To Perform Data Visualization using seaborn python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
 ```
import seaborn as sns
import pandas as pd

Read the CSV File:

df=pd.read_csv("iris.csv")
df.head()

Join Plot:


sns.jointplot(x="petal_length", y="petal_width", data=df, kind="hex")

Pair PLot:


sns.pairplot(data=df, vars=["sepal_length","sepal_width"], hue="species")

Dist Plot:


sns.displot(df["petal_length"], kde=True)

Count Plot:


sns.countplot(y="species", data=df)

Box Plot:

sns.boxplot(x="species", y="petal_length", data=df)

Bar Plot:


sns.barplot(x="species", y="petal_length", data=df)

Violin Plot


sns.violinplot(x="species", y="petal_length", data=df)

```
<img width="688" height="723" alt="image" src="https://github.com/user-attachments/assets/6ec0625c-1cee-4f0b-804c-05c98e12eb8f" />

<img width="703" height="557" alt="image" src="https://github.com/user-attachments/assets/4e8d278d-e4fb-4c61-b25f-dd0dfd097653" />

<img width="604" height="617" alt="image" src="https://github.com/user-attachments/assets/0b58c962-d8ba-42e9-a5b3-20ff16580f2c" />

<img width="761" height="517" alt="image" src="https://github.com/user-attachments/assets/3b5a7978-37c0-4451-9862-af0c24d6c66d" />

<img width="725" height="550" alt="image" src="https://github.com/user-attachments/assets/6185263b-30a9-42fc-bdd8-f15f8cdef1e1" />

<img width="739" height="542" alt="image" src="https://github.com/user-attachments/assets/e8678e69-668b-4d65-a959-ec60b0ed1bbb" />

<img width="678" height="541" alt="image" src="https://github.com/user-attachments/assets/e43003f0-9d88-4f55-8d6d-f7dba9a05268" />


# Result:
successfully get Perform Data Visualization using seaborn python library for the given datas
