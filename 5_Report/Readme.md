
# Requirements
## Introduction
   ##### DTH Billing System is an application that enables users to add and store DTH BILLING Records. DTH Billing System is developed to maintain the details of DTH Billing using smartcard numbers and names. The aim of the system is to develope “DTH BILLING SYSTEM” software, which should automate the process to create and store DTH Billing record details. The system is supposed to be used as a subsystem in a large office system, which could be manual system or a computerized one.

## Research
  #####  DTH Billing System is a small project, you may perform and handle billing processes in the same way as broadcasting businesses services do. You can add records with names, smartcard numbers, and payment amounts here. Existing records can be viewed, modified, searched, and deleted.

## Features and Timeline
##### • Major activities of the manual system is automated, which increases its throughput.
• The system is fast, user friendly and interactive
• The information entered is more accurate and clear
• Better data management facility in terms of maintaining files which are entered  in registers manually and stored.


## Defining our System
##### • Add Records.
#####     • Delete Records.
#####     • Search Records.
#####     • List Records.
#####     • Payment.
#####     • Modify Records.

## SWOT ANALYSIS
### Strengths:
##### • To reduce workload to staff.
##### • To reduce the delay in processing time.
#####  • To reduce the delay in bill generation.
##### • To provide greater flexibility. 
##### • Make maintenance changes easy.
    
### Weakness:
##### • Late payments when network problem arises.
    
### Opportunities:
#####     • TV Services
    
### Threats:
#####  • System Crash Errors and ommision

## 4W's and 1H 
#### Who: 
#####    DTH Billing Management. 
#### What: 
#####   DTH Billing Records. 
#### When: 
#####     There was problem of storing data manually but advancement in technologies helped in storing data and accessing it easily. 
#### Where: 
#####    This project can be used for DTH Billing. 
#### How:
#####  The inconvinience is caused in storing data manually and accessing it.Digitally storing data will be helpful in accessing data easily and modifying it.

## Details requirements
### High Level Requirements:
| ID | Description | Status |
|------| ------| ------|
| HLR1 | User shall be able to add new records (A) | Implemented
|HLR2  | User shall be able to List of records (L) | Implemented
|HLR3  | User shall be able to Modifying records (M) |	Implemented
|HLR4  | User shall be able to Payment (P) |	Implemented
|HLR5  | User shall be able For searching records(S) |	Implemented
|HLR6  | User shall be able to Deleting records(D) |	Implemented

#### Low Level Requirements:

| ID | Description | Status |
|-------|------|------|
| LLR1 | User shall be able to fetch perfect bill amount | Implemented 
| LLR2 |System must display data without error | Implemented



# Design


## Behavioural Diagram

![Behavioural](https://user-images.githubusercontent.com/50225786/142906440-1f580f3c-447a-450a-816b-baa0bbef22ef.jpg)

## Structural Diagram

![structural](https://user-images.githubusercontent.com/50225786/142906439-3c9ecc23-7375-474a-9e06-ed4e82877912.PNG)

## User Diagram

![User](https://user-images.githubusercontent.com/50225786/142906441-1ed158af-a9f4-4cdc-b40f-e3d3f1185efa.jpeg)



# Test Cases:

### High Level Test Cases:
| Test Id |	keys |	Description |	Expected output |	Actual output |	Pass/Fail(Result) |
|------|------|------|------|------|------|
| TID 1 | A | Adding Records | SUCCESS |	SUCCESS |	PASS 
| TID 2 |	L	| List of Records|	SUCCESS	| SUCCESS	 | PASS
| TID 3	| M	| Modifying | Records |	SUCCESS |	SUCCESS	|PASS
| TID 4 |	P	| Payment	| SUCCESS	| SUCCESS	| PASS
| TID 5	| S	| Searching Records | SUCCESS |	SUCCESS | PASS
| TID 6	| D |	Deleting Records | SUCCESS |	SUCCESS	| PASS


#### Low Level Test Cases:
| Test Id |	Description |	Expected output |	Actual output |	Pass/Fail(Result) |
|------|------|------|------|------|
| TID 1 | User shall be able to fetch perfect bill amount | SUCCESS | SUCCESS | PASS 
| TID 2 |System must display data without error | SUCCESS | SUCCESS |  PASS


# OUTPUT:

### welcome Page:

![2](https://user-images.githubusercontent.com/50225786/143028588-b2c4e470-9cc8-4dc8-8132-f6aa0b8217fc.PNG)

### Records:

![3](https://user-images.githubusercontent.com/50225786/143028608-b90fcd75-389c-4bd6-ac9a-55ce4a3359c5.PNG)

### System Generated Bill:

![4](https://user-images.githubusercontent.com/50225786/143028668-c3ae9691-633b-43c5-961a-39a88498f3da.PNG)







