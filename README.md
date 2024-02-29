<H3>ENTER YOUR NAME : NAVEEN S</H3>
<H3>ENTER YOUR REGISTER NO. 212222240070</H3>
<H3>EX. NO.1</H3>
<H3>DATE</H3>
<H1 ALIGN =CENTER> Introduction to Kaggle and Data preprocessing</H1>

## AIM:

To perform Data preprocessing in a data set downloaded from Kaggle

## EQUIPMENTS REQUIRED:
Hardware – PCs
Anaconda – Python 3.7 Installation / Google Colab /Jupiter Notebook

## RELATED THEORETICAL CONCEPT:

**Kaggle :**
Kaggle, a subsidiary of Google LLC, is an online community of data scientists and machine learning practitioners. Kaggle allows users to find and publish data sets, explore and build models in a web-based data-science environment, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges.

**Data Preprocessing:**

Pre-processing refers to the transformations applied to our data before feeding it to the algorithm. Data Preprocessing is a technique that is used to convert the raw data into a clean data set. In other words, whenever the data is gathered from different sources it is collected in raw format which is not feasible for the analysis.
Data Preprocessing is the process of making data suitable for use while training a machine learning model. The dataset initially provided for training might not be in a ready-to-use state, for e.g. it might not be formatted properly, or may contain missing or null values.Solving all these problems using various methods is called Data Preprocessing, using a properly processed dataset while training will not only make life easier for you but also increase the efficiency and accuracy of your model.

**Need of Data Preprocessing :**

For achieving better results from the applied model in Machine Learning projects the format of the data has to be in a proper manner. Some specified Machine Learning model needs information in a specified format, for example, Random Forest algorithm does not support null values, therefore to execute random forest algorithm null values have to be managed from the original raw data set.
Another aspect is that the data set should be formatted in such a way that more than one Machine Learning and Deep Learning algorithm are executed in one data set, and best out of them is chosen.


## ALGORITHM:
STEP 1:Importing the libraries<BR>
STEP 2:Importing the dataset<BR>
STEP 3:Taking care of missing data<BR>
STEP 4:Encoding categorical data<BR>
STEP 5:Normalizing the data<BR>
STEP 6:Splitting the data into test and train<BR>


##  PROGRAM:
```py
import pandas as pd
import io
from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import MinMaxScaler
from sklearn.model_selection import train_test_split

data = pd.read_csv("Churn_Modelling.csv")
data
data.head()

X=data.iloc[:,:-1].values
X

y=data.iloc[:,-1].values
y

data.isnull().sum()

data.duplicated()

data.describe()

data = data.drop(['Surname', 'Geography','Gender'], axis=1)
data.head()

scaler=MinMaxScaler()
df1=pd.DataFrame(scaler.fit_transform(data))
print(df1)

X_train ,X_test ,y_train,y_test=train_test_split(X,y,test_size=0.2)

X_train

X_test

print("Lenght of X_test ",len(X_test))


```
## OUTPUT:
### Dataset:
![data](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/3266a858-7026-457d-b074-8857923d7a07)
### X Values:
![x_values](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/aade21d7-c701-4b77-bc89-2c2b3525c10a)
### Y Values:
![y_values](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/d0814948-069a-4ef2-a673-f17b8d890bd3)
### Null Values:
![null_values](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/6d015d44-ee3a-45c1-ba58-9eef5c14b64b)
### Duplicated Values:
![duplicated_values](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/45952918-fb79-43a1-bb18-da592508ace2)
### Description:
![describe](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/49a40544-613f-42c9-8f30-21247564bfa1)
### Normalized Dataset:
![normalized](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/b52b7460-7491-462f-9e3e-153379875151)
### Training Data:
![training ](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/92024909-59f8-45b1-b69b-03e5eed238af)
### Testing Data:
![test](https://github.com/Naveensrinivasan07/Ex-1-NN/assets/119475891/17c1c314-f771-4787-8743-320698017e55)

## RESULT:
Thus, Implementation of Data Preprocessing is done in python  using a data set downloaded from Kaggle.



