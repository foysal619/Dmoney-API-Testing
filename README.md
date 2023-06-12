# DMoney API Testing

This is a practise API testing with the help of demo DMoney API. I have generated some test scenarios with the help of postman and report using newman.

## Test Case Scenarios Covered

1. Admin creates an agent and random 2 customers
2. Deposit some money from SYSTEM account to the agent. System account (range 10tk to 10000tk)
3. Agent deposit to any of 1 customer
4. Check agent balance
5. Then withdraw any amount by the customer from the agent (range 10 tk to 10000 tk)
6. Then the customer checks balance
7. Then send money to the other customer
8. Then from the another customer payment to this merchant: 01686606905
9. Then the second customer will check both balance and statement
10. Then the merchant will check his own balance

## How to run this project

- Clone This project
- Then run the follwing command 

```bash
  npm i
  npm run report.js
```
## Tools Used
- Postman
- Newman


## Dmoney API Testing Test Case:
[https://docs.google.com/spreadsheets/d/1TlqU_8-HCT_h76P69iPLE_aJhjsKX7g9/edit?usp=sharing&ouid=105413695096846736430&rtpof=true&sd=true](https://docs.google.com/spreadsheets/d/1q9hr01iATjcPX0042Miz26rsIJBjp7cpeA4t8jIBOdA/edit?usp=sharing)

## Bug And Improvement Report:
[https://docs.google.com/spreadsheets/d/1GpIxce69jw1vQdlDSwo0Bdi1SlfEMjH0/edit?usp=sharing&ouid=105413695096846736430&rtpof=true&sd=true](https://docs.google.com/spreadsheets/d/1D4X_dAbA9UAZNmg4mtJYsJpXk8IoKpQKZco0-iGef8o/edit?usp=sharing)

# Postman documentation:
[https://documenter.getpostman.com/view/23351657/2s8ZDbX1VA](https://documenter.getpostman.com/view/17855925/2s93mBvJ9S)

### Screenshot of Newman Report
![Newman Report](https://github.com/foysal619/Dmoney-API-Testing/assets/61048879/66b4235e-b3b2-47ab-9aeb-1d382f99b382)





