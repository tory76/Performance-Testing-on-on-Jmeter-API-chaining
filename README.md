# HTML Report:

<img width="1600" height="729" alt="image" src="https://github.com/user-attachments/assets/8f61f802-4b4b-4600-bb2b-92bc244cc021" />
<img width="1600" height="743" alt="image" src="https://github.com/user-attachments/assets/b321b27b-3f59-4d60-9ffc-544f377dad43" />

# Dmoney JMeter API chaining Project
## Project Overview

This project contains API automation test cases for the Dmoney system using Apache JMeter.
The purpose of this project is to validate core financial transaction APIs such as:

Deposit

Send Money

Payment

All test data is parameterized using CSV files.

## Tools & Technologies
Tool          | Version       
------------- | ------------- 
Apache JMeter | 5.6.3          
Java          | JDK 17        
OS            | Windows 

## Test Scenarios
Module     | Description                            
---------- | -------------------------------------- 
Deposit    | User can deposit money to another user 
Send Money | User can send money to another user    
Payment    | User can make merchant payment         

## Test Data (CSV)

File Name     | Purpose                       
------------- | ----------------------------- 
deposit.csv   | Input data for Deposit API    
sendMoney.csv | Input data for Send Money API 
Payment.csv   | Input data for Payment API    

## How to Run

1.Open Apache JMeter

2.Load dmoney.jmx

3.Click Run 

4.After execution generate HTML report from JMeter


