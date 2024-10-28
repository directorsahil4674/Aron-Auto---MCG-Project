🚗 Aron Auto - MCG Project -- Python
Author: Sahil Dhiman
Position: Sales Marketing Analyst
Company: Aron Auto
To Concern: VP of Fleet Management
Tools used: Python (Seaborn, Matplotlib)
📝 Description
Aron Auto is known for its fleet management services. As a client of Maven Consulting Group, they want assistance analyzing the Auto Procurement Market for a fleet of service vehicles. Their main concern aligns with having an optimal purchasing for Ford f150s through this analysis, ensuring the most affordable and efficient solution for clients who lease trucks to contractors and businesses.
📊 Project Objectives
This project focuses on 2 Major:
Section 1: Deep Visualization for Auto Procurement Process. Section 2: Finding Ford f150 - the main concern of the business.
My Approach:
1. Data Cleaning and EDA
2. Analysis of the Auto Procurement process. 
3. Finding the best Ford f150s out of the process. 
Section 1: Auto Procurement Process Analysis
Auto Procurement Process refers to the steps involved in purchasing or acquiring vehicles for a company's fleet. It discusses the car type, year, company and the best selling price.
We first used a pair plot to examine the relation between the selling price and MMR (The Recommended selling price):

![image](https://github.com/user-attachments/assets/69c3ee13-0460-434c-9376-272a984497b9)

The above image shows the possible relationship between each numeric variable.
The key point:
1. As the Year increases, the selling price also increases.     
Possible reasons could be condition and model technology enhancement. 
2. Same Analysis goes with MMR. As the selling price increases, so do the mmr. 
3. Somewhere or the other, we can predict that the selling price is almost equal to the recommended price. 
The Second analysis discusses the correlation analysis among these variables, and it clearly shows how year, odometer and condition are negatively correlated to each other.

![image](https://github.com/user-attachments/assets/21f8cc54-a814-45b3-a53e-a012059410da)

The key point:
1. It is not necessary that if the odometer's value is higher, so as the year will be. 
2. The same goes for the condition since it is also inversely proportional to the odometer value. 
3. Interestingly, MMR and selling price are closely related. 
We divided the condition of the models into their respective groups, known as conditional bins, and then it was analyzed using a bar plot compared to the selling price.

![image](https://github.com/user-attachments/assets/38584a77-e6c6-426c-b962-414e3a9d540f)

After this intensive analysis, we discovered the following:
1. Utha is the best place to buy the truck with the best selling price and is a nerdier buying option. 

![image](https://github.com/user-attachments/assets/25820276-c251-4176-ae60-683484fd76f8)

2. The table below shows our model years with the difference between the selling price and the recommended price, car counts and conditions.  

![image](https://github.com/user-attachments/assets/765ae335-94c1-4e53-8c2d-e699ec713558)

Note:
I've discussed a lot of insights in the jupyter notebook itself. Please go through it and provide your recommendations.
Sahil C Dhiman - Data Analyst
October 27, 2024
