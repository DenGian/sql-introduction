# sql-introduction

---
## MaTS
![meme](./images/meme.jpeg)

---
## About

In this assignment I am trying to get familiar with databases.  
I am going to make a couple of those and try to extract and manipulate the data inside.  
When I am able to achieve this I'm going to try and use data between tables.  

---
## What's up?

### Step 1

Make the following tables and populate them with some dummy data (have at least two entries for every table)
1. groups: id, name, location, start_date, max_participants
2. learners: id, name, email, active
3. coaches: id, name

#### My examples: 
1.  
![1-groups](./images/1-group.png)
2.  
![1-learners](./images/1-learners.png)
3.  
![1-coaches](./images/1-coaches.png)

#### How did I create a table?

- Step 1  
![step 1](./images/step-1.png)  
  * You *right-click* on the tables and select *new* to make a new table
- Step 2  
![step-2](./images/step-2.png)  
  *  
- Step 3  
![step-3](./images/step-3.png)  
  * 
- Step 4   
![step-4](./images/step-4.png)  
  * 
- Step 5  
![step-5](./images/step-5.png)  
  * 
- Step 6  
![step-6](./images/step-6.png)  
  * 
- Step 7  
![step-7](./images/step-7.png)  
  * Congratulations, we have made our table!
---
### Step 2

Try the following selects:
1. get all data from groups
2. Get the name and email of the first learner, and alias the name to learner_name

#### The console?

- Step 1 
![console](./images/2-console.png)  
  * The console is located on the top right
- Step 2 
![solution1](./images/consoleSolution1.png)
  * The first one gets all the data from "groups"
  * The second one gets the name and email from the first learner and changes the "name" to "learner name"  
![consoleOutput](./images/consoleOutput1.png)  

---
### Step 3

💩 happens - a group needs to be postponed
1. Update the start date of the first_group (make it two months later)
2. Introduce a new field status which can contain a long text indicating the reason for postponing

#### To be continued 

### useful links
* https://mariadb.com/kb/en/mariadb-basics/
* https://sqlzoo.net/wiki/SQL_Tutorial