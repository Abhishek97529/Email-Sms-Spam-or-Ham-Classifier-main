# Email-Sms-Spam-or-Ham-Classifier

![image](https://user-images.githubusercontent.com/37560890/159529916-3e94cbe8-bfd7-4d2e-83ef-6dec48b99c10.png)

### [ Step - I ] . Importing the required lib's and data cleaning

1. Import the data & lib's.

![image](https://user-images.githubusercontent.com/37560890/159530215-91598006-fd34-4966-a755-25af83580ecf.png)

2. Print the head.

![image](https://user-images.githubusercontent.com/37560890/159530486-f5b0d683-c464-475c-b055-5daf98f3f941.png)

3. Shape & description of data.

![image](https://user-images.githubusercontent.com/37560890/159530705-4cfc0005-cfdd-44d3-910f-03f02102d3e4.png)


4. Data information.

![image](https://user-images.githubusercontent.com/37560890/159531065-260f1a95-79d7-456c-b45d-7f3b2e59b166.png)

5. Renaming the columns.

![image](https://user-images.githubusercontent.com/37560890/159534082-016d5ecb-63e9-4c50-bbff-dcea05c6b963.png)

6. Apply the label encoder Spam -> 1 and Ham ->0

![image](https://user-images.githubusercontent.com/37560890/159531477-5ed06b73-308c-40bd-ad91-717f49a4febf.png)

7. Check for the null values, duplicate values , remove the duplicate values.

![image](https://user-images.githubusercontent.com/37560890/159531787-0a2cdc1b-5fd1-4f98-a735-a9a3d6bd57ab.png)

### [ Step - II ] . Exploratory Data Analysis

1. Value counts for the target variable , plot the pie chart.

![image](https://user-images.githubusercontent.com/37560890/159532131-9d079760-4470-4376-a0ab-93726c7d08b3.png)

2. Import the nltk pkg. 

![image](https://user-images.githubusercontent.com/37560890/159532475-a14c145d-a3da-4c60-8362-e34bf2628e15.png)

![image](https://user-images.githubusercontent.com/37560890/159533231-33331b7e-f695-41a5-833c-cccef878853e.png)

3. Count the number of sentences.

![image](https://user-images.githubusercontent.com/37560890/159533388-41984af9-589c-4847-98f1-05614c37dd4d.png)

4. Descibe our new features.

![image](https://user-images.githubusercontent.com/37560890/159534908-8a425345-a262-417d-9e6d-9963bf80fe99.png)

5. Plot the histogram.

![image](https://user-images.githubusercontent.com/37560890/159535115-4f7f3c23-18ca-4d40-b99e-ece18ec916ee.png)

![image](https://user-images.githubusercontent.com/37560890/159535225-8ddb55ea-115a-4af0-9c11-cafe95c3f686.png)


6. Computing the correlations.

![image](https://user-images.githubusercontent.com/37560890/159535422-c7e812d6-9ad8-4ec2-8f53-3dd03c354dd4.png)


### [ Step - III ] . Text Preprocessing

1. Text preprocessing.

![image](https://user-images.githubusercontent.com/37560890/159536111-847ae4c9-915f-4a22-b036-51b6734dacc4.png)

![image](https://user-images.githubusercontent.com/37560890/159536276-7e5b9de6-0cb5-48ab-b625-dfedc83fae31.png)

2. Apply on our dataset.

![image](https://user-images.githubusercontent.com/37560890/159536881-c5f13d43-cf60-4876-bf24-7f80665d1843.png)

3. Install the word cloud.

![image](https://user-images.githubusercontent.com/37560890/159537020-657b4792-961d-4ea8-aad6-3ef78c38592a.png)

4. Make the word cloud for spam msg's.

![image](https://user-images.githubusercontent.com/37560890/159537146-96c75c52-b65e-4962-b15e-317e4a880568.png)

![image](https://user-images.githubusercontent.com/37560890/159537244-5abd7ba1-c690-4f76-aec5-6c959fa43c28.png)

5. Make word cloud for ham msg's.

![image](https://user-images.githubusercontent.com/37560890/159537392-1c4747d4-395f-4aed-87f2-0565a2e69c5f.png)

![image](https://user-images.githubusercontent.com/37560890/159537473-91ed1a17-f022-4563-862b-71533353cf9c.png)

6. Top 30 word's in spam msg's.

![image](https://user-images.githubusercontent.com/37560890/159537586-df8f4950-9798-4783-a35b-2f24a01e474a.png)

![image](https://user-images.githubusercontent.com/37560890/159537712-3fccb5ac-4c6c-419e-9a8f-0d2e8c56cbd8.png)


7. Top 30 word's in ham msg's.

![image](https://user-images.githubusercontent.com/37560890/159537842-74e3ff28-4736-44a9-8e54-3a3524b1d712.png)

![image](https://user-images.githubusercontent.com/37560890/159538107-9973150c-a944-4579-a00f-75426e263f51.png)

### [ Step - IV ] . Model Building

1. Count vectorizer.

![image](https://user-images.githubusercontent.com/37560890/159539701-b1b3d8ec-6888-4eb4-808f-6cfa20e64ecf.png)

2. Train , Test, Split.

![image](https://user-images.githubusercontent.com/37560890/159539958-28436409-b8e7-4783-b504-d83dc8bc09d6.png)

