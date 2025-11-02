# SQL-Assignment
## 1.Here is the Dataset for the below questions. 

##### Gold members Data Set--Column names : (userid integer, signup_date) 
###### ('John','09-22-2017'), ('Mary','04-21-2017') 
 
#### Users Data Set--Column names : (userid integer, signup_date) 
###### ('John','09-02-2014'), ('Michel','01-15-2015'), ('Mary','04-11-2014') 

#### Sales Data Set-- Column names : (userid,created_date,product_id) 
###### ('John','04-19-2017',2), ('Mary','12-18-2019',1), ('Michel','07-20-2020',3), ('John','10-23-2019',2), ('John','03-19-2018',3), ('Mary','12-20-2016',2), ('John','11-09-2016',1), ('John','05-20-2016',3), ('Michel','09-24-2017',1), ('John','03-11-2017',2), ('John','03-11-2016',1), ('Mary','11-10-2016',1), ('Mary','12-07-2017',2) 

#### Product Data Set--Column names : (product_id,product_name,price) 
###### (1,'Mobile',980), (2,'Ipad',870), (3,'Laptop',330) 

## Questions on above Dataset : 
#### 1.Create Database as ecommerce 
<img width="1691" height="103" alt="image" src="https://github.com/user-attachments/assets/e8355d7b-9db4-45a6-b21e-ae3f238ffb42" />

#### 2.Create 4 tables (gold_member_users, users, sales, product) under the above database(ecommerce) 
<img width="1672" height="425" alt="image" src="https://github.com/user-attachments/assets/0e687690-d40f-4127-a3e2-b9efaba06ace" />

#### 3.Insert the values provided above with respective datatypes 
<img width="1662" height="548" alt="image" src="https://github.com/user-attachments/assets/41151b33-e61e-4d49-8618-f63957260774" />

#### 4.Show all the tables in the same database(ecommerce) 
<img width="1686" height="186" alt="image" src="https://github.com/user-attachments/assets/4d54db91-47f9-497d-9345-071564e54c67" />

#### 5.Count all the records of all four tables using single query 
<img width="1687" height="311" alt="image" src="https://github.com/user-attachments/assets/631100d6-1fe1-4d7f-bb2f-0351a9afae72" />

#### 6.What is the total amount each customer spent on ecommerce company 
<img width="1658" height="233" alt="image" src="https://github.com/user-attachments/assets/c2f22796-8111-4318-a381-7ae7e71bb5ab" />

#### 7.Find the distinct dates of each customer visited the website:     output should have 2 columns date and customer name 
<img width="1687" height="443" alt="image" src="https://github.com/user-attachments/assets/9a733ca8-40fb-4693-a765-5f3a3cc74710" />

#### 8.Find the first product purchased by each customer using 3 tables(users, sales, product) 
<img width="1687" height="387" alt="image" src="https://github.com/user-attachments/assets/323a5c2c-dd2a-41c4-bfeb-869f7b2d3ade" />

#### 9.What is the most purchased item of each customer and how many times the customer has purchased it: output should have 2 columns count of the items as item_count and customer name 
<img width="1687" height="395" alt="image" src="https://github.com/user-attachments/assets/3757d1c7-d156-43aa-a03f-7ed448f2a01d" />

#### 10.Find out the customer who is not the gold_member_user 
<img width="1683" height="165" alt="image" src="https://github.com/user-attachments/assets/a9540827-cd52-4992-8d2c-56818931ce1a" />

#### 11.What is the amount spent by each customer when he was the gold_member order by  user 
<img width="1665" height="303" alt="image" src="https://github.com/user-attachments/assets/f971baaa-ef51-4f51-b835-713023afdbaa" />

#### 12.Find the Customers names whose name starts with M 
<img width="1686" height="211" alt="image" src="https://github.com/user-attachments/assets/7099413e-fbc7-421e-b896-ccffe8a5428c" />

#### 13.Find the Distinct customer Id of each customer 
<img width="1690" height="212" alt="image" src="https://github.com/user-attachments/assets/29a78aac-0e70-48ca-b27f-45d2e3c3303a" />

#### 14.Change the Column name from product table as price_value from price 
<img width="1687" height="142" alt="image" src="https://github.com/user-attachments/assets/90d0c7f1-b97d-416b-ba8a-ac6bc108421f" />
<img width="1670" height="147" alt="image" src="https://github.com/user-attachments/assets/617782bb-57fa-44e6-90eb-9e45768e584a" />

#### 15.Change the Column value product_name – Ipad to Iphone from product table 
<img width="1687" height="217" alt="image" src="https://github.com/user-attachments/assets/41d8858e-a62a-4005-8a5a-ccce3563afd2" />

#### 16.Change the table name of gold_member_users to gold_membership_users 
<img width="1690" height="163" alt="image" src="https://github.com/user-attachments/assets/210aa14f-418d-4d9c-b8c5-3a126d3de639" />
<img width="1681" height="178" alt="image" src="https://github.com/user-attachments/assets/c57c5556-8cbe-4073-8b33-bc8d3df7199c" />

#### 17.Create a new column  as Status in the table crate above gold_membership_users  the Status values should be 2 Yes and No if the user is gold member, then status should be Yes else No. 
##### Step 1
<img width="1686" height="162" alt="image" src="https://github.com/user-attachments/assets/3f3b203e-084c-4165-a324-6d0782689a99" />

##### Step 2
<img width="1687" height="297" alt="image" src="https://github.com/user-attachments/assets/dbc9a860-4c0e-48fc-a8a6-b97a155a9637" />

#### 18.Delete the users_ids 1,2 from users table and roll the back changes once both the rows are deleted one by one mention the result when performed roll back 
##### Step 1: Transaction begins
<img width="1687" height="260" alt="image" src="https://github.com/user-attachments/assets/6ec76673-0979-4936-b838-742af6ba7af0" />
<img width="1690" height="207" alt="image" src="https://github.com/user-attachments/assets/5534bf0b-a99e-4026-953a-02ec6cedc163" />

##### Step 2 RollBack the Transaction:
<img width="1687" height="221" alt="image" src="https://github.com/user-attachments/assets/a9a1f6d6-9f15-47b6-86fd-6795a095b5fa" />

#### 19.Insert one more record as same (3,'Laptop',330) as product table 
<img width="1687" height="236" alt="image" src="https://github.com/user-attachments/assets/ccd6d3e8-ff69-4a6f-bbcf-d9ebfbf14b6b" />

#### 20.Write a query to find the duplicates in product table 
<img width="1687" height="211" alt="image" src="https://github.com/user-attachments/assets/c8004efc-702a-44a8-ba21-660b2e28b9e2" />

## 2. Write a query to find for each date the number of different products sold and their names.  
#### Column names: (sell_date, product) 
##### Data: ('2020-05-30', 'Headphones'), 
###### ('2020-06-01','Pencil'), ('2020-06-02','Mask'), ('2020-05-30','Basketball'), ('2020-06-01','Book'), ('2020-06-02', ' Mask '), ('2020-05-30','T-Shirt') 
###### //Create table product_details with above data and find the above result 

### Step 1: Create the Table
<img width="1688" height="197" alt="image" src="https://github.com/user-attachments/assets/997df6cd-7d2e-4bd2-9a43-c88f0e135c14" />

### Step 2: Insert the Data
<img width="1687" height="307" alt="image" src="https://github.com/user-attachments/assets/9e2f8a73-8391-4c98-9cc4-fcf57ea7c018" />

### Step 3: Query to Find Number of Different Products and Their Names
#### We’ll:
* Trim extra spaces from product names (because ' Mask ' and 'Mask' should be treated the same).
* Use GROUP BY on sell_date.
* Use SQL Server’s STRING_AGG() function to combine product names.

<img width="1683" height="341" alt="image" src="https://github.com/user-attachments/assets/62434f8f-bd64-4563-82c5-041253f2fee0" />

## Find the total salary of each department 
#### Column names:(id_deptname, emp_name, salary) 
#### Data:  
###### ('1111-MATH', 'RAHUL', 10000), ('1111-MATH', 'RAKESH', 20000), ('2222-SCIENCE', 'AKASH', 10000), ('222-SCIENCE', 'ANDREW', 10000), ('22-CHEM', 'ANKIT', 25000), ('3333-CHEM', 'SONIKA', 12000), ('4444-BIO', 'HITESH', 2300), ('44-BIO', 'AKSHAY', 10000) 

### Step 1: Create the Table
<img width="1690" height="222" alt="image" src="https://github.com/user-attachments/assets/314152c5-0f14-45b6-a711-7a608e99e12a" />

### Step 2: Insert the Data
<img width="1685" height="292" alt="image" src="https://github.com/user-attachments/assets/66ea2db0-3abd-4df0-9087-d7450144f5af" />

### Step 3: Extract Department Name and Find Total Salary
* Here, department name appears after the hyphen (-).
* We can use CHARINDEX() and SUBSTRING() to extract it.

<img width="1691" height="240" alt="image" src="https://github.com/user-attachments/assets/fd07d111-36ac-4d4e-83bc-f176f3a42a76" />

4.Write a query to find gmail accounts with latest and first signup date and difference between both the dates and also write the query to replace null value with ‘1970-01-01’ 

Column names: (id, email_id, signup_date) 

Data: 

(1, 'Rajesh@Gmail.com', '2022-02-01'), 
 (2, 'Rakesh_gmail@rediffmail.com', '2023-01-22'), 
 (3, 'Hitest@Gmail.com', '2020-09-08'), 
 (4, 'Salil@Gmmail.com', '2019-07-05'), 
 (5, 'Himanshu@Yahoo.com', '2023-05-09'), 
 (6, 'Hitesh@Twitter.com', '2015-01-01'), 
 (7, 'Rakesh@facebook.com', null); 

Create table email_signup with above data 


  



















