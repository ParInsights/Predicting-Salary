# Predicting Salary 

Goal: Determine the best salary for the next Syracuse head football coach. This does not include bonuses, just total compensation.

### Steps:
1. Load coaches dataset 
2. Review and clean dataset.
3. load graduation rates dataset
4.Develop vector for each school using last years record.
5. Develop data frame of analysis
6. Crate and Fit a regression model
    -with salary as the response and relevent predictor (need more than one predictor)

  ~Extra~
7. Create a geographic visual that best depicts the conference median salary
8. Fit a hiearchical model based on conference. 
9. Use additional material from link to recreate the code for the basic regression model with a training and test 
   set. Do not use conference as a predictor. 

### Questions Answered:
1. What is the recommended salary for a Syracuse football coach?
2. What would his salary be if Syracuse was still in the Big East? 
    -Compare this to if they were in the Big Ten? 
3. What schools were dropeed from the data. 
    -Why? 
4. What effect does graduation rates have on projected salary? 
5. How good is the model?
6. What is the single biggest impact on salary size?
Notes/Thoughts along the way:
1. To complete number 4 above - need coaches win and loss records. 
    -Solved this by creating own Coaches win and loss records dataset by importing data from website and creating master datatable. See below. 
