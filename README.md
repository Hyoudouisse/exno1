# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output
            1) d=pd.read_csv("SAMPLEIDS.csv")

            2) d=pd.read_csv("SAMPLEIDS.csv")

            3) d

            4) d.head(4)

            5) d.tail(4)

            6) d.info()

            7) d.isnull().sum()

            8) d.[' '].fillna(value=d[' '].mean(),inplace=True)

            9) d.isnull().sum()


![image](https://github.com/Hyoudouisse/exno1/assets/142372168/8055139e-6283-47c9-8efa-7b16ef185bad)

![image](https://github.com/Hyoudouisse/exno1/assets/142372168/14bcabdc-3457-465e-a4ab-94476fa9c73c)

![image](https://github.com/Hyoudouisse/exno1/assets/142372168/46a7607f-6f3a-40cd-9e42-dd97bf71f523)
# Result
          we sucessfully read the given file and goen our output  


          









