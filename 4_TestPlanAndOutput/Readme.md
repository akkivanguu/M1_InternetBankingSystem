# TEST PLAN:

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       |Check if Account is created or not                        | ((1). Account number (2). Name (3). Age (4). Address (5). Citizenship (6). Phone number  (7). Account type (8). Initial Balance (9) Date of birth | Pointer to structure | PASS | Requirement based|
|  H_02   |Check Addition of new information | (1). Struct (2). Account number (3). Name (4). Age (5). Address (6). Citizenship (7). Phone number  (8). Account type (9). Initial Balance (10) Date of birth | SUCCESS |SUCCESS|Requirement based |
| H_02_01 | Check  account number exists | (1). Account number (2). Struct pointer | SUCCESS | SUCCESS | Requirement based |
| H_02_02 | Check  account number doesn't exists | (1). Account number (2). Struct pointer | NO Account EXISTS | NO_ACC_EXISTS | Technical |
| H_03 | Check Updation of information | (1). Account number (2). Search function| SUCCESS | SUCCESS | Requirement based |
| H_03_01 | Check  account number exists | (1). Account number (2). Search function (3). Field to be updated | SUCCESS | SUCCESS | Requirement based |
| H_03_02 | Check  account number doesn't exists | (1). Account number (2). Search function | NO Account EXISTS | NO_ACC_EXISTS | Requirement based |
| H_04 | search account if account exists | (1). Account number (2). Display Flag | SUCCESS | SUCCESS | Requirement based |
| H_04_01 | Check if account number doesn't exists | (1). Struct Pointer (2). Account number | NO Account EXISTS | NO_ACC_EXISTS | Technical |
| H_05 | Deposit money | (1). Struct pointer (2). Account number (3). Amount deposited | SUCCESS| SUCCESS | Requirement based |
| H_05_0 | Check if account number doesn't exists | (1). Struct pointer (2). Account number | NO Account EXISTS | NO_ACC_EXISTS | Technical |
| H_06 | Withdraw money | (1). Struct pointers (2). Account number  | SUCCESS | SUCCESS | Technical |
| H_06_01 | Check if account number doesn't exists | (1). Struct pointers (2). Account number (3).Return | NO_ACC_EXISTS | NO Account EXISTS | Requirement based |
| H_07 | Display available accounts information | (1). Struct Pointer (2) Account number | SUCCESS | SUCCESS | Technical | 


## Unity Test Passed Output:

![Screenshot (31)](https://user-images.githubusercontent.com/101030179/161424204-f7dbb577-70a8-46b3-a22b-895e2afad67e.png)




