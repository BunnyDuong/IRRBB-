## --Interest rate risk in the banking books (IRRBB) task

It's a big task worked by a team of 2 members. Below is the section I worked on.

The work as follow: 
1. Merging daily data 
2. Fixed deposit model:
We classified customers into different buckets that based on their prewithdrawal period. The formula as below:
![image](https://github.com/user-attachments/assets/186d6d13-4370-40d9-834c-6af479c20f98)

3. Percentile.
We also using percentile cutting method to identify the rate at which customer pre-withdraw the money the most and the least. 
![image](https://github.com/user-attachments/assets/55f84c3e-65b9-41c6-95da-e6b2f37fd4e4)

4. Regression
We run loop regression and chose models that use less independent variables and good score for evaluation parameters

