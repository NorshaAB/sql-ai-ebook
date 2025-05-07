# Activity 4E: CAR Database (AI-Enhanced)

## Database Schema

**Tables**: `CUSTOMER`, `CAR_COMPONENT`, `CLAIM`, `COMPONENT_CLAIM`

### CUSTOMER

| CUSTID | CUSTNAME     | CAR_NUMBER | PHONE_NUMBER | REGISTER_DATE |
|--------|--------------|------------|--------------|----------------|
| C0001  | David Teo     | WUV2318    | 81691        | 2014-01-09     |
| C0002  | Sulaiman Ali  | JKJ9782    | 61291        | 2011-05-07     |
| C0003  | Kang Gary     | MAM123     | 41972        | 2010-06-13     |
| C0004  | Ji Hyo        | SA4888     | 11341        | 2012-09-26     |
| C0005  | Karigalan     | KUL511     | 21412        | 2003-07-18     |

### CAR_COMPONENT

| COMPID | COMPNAME            | PRICE |
|--------|---------------------|-------|
| KK001  | ISWARA Rear Lamp    | 100   |
| KK002  | WIRA Front Bumper   | 450   |
| KK003  | ISWARA Front Mirror | 300   |
| KK004  | WAJA Break Lamp     | 250   |
| KK005  | WIRA Front Lamp     | 600   |

### CLAIM

| CLAIMID | CLAIM_DATE | CUSTID |
|---------|------------|--------|
| CL001   | 2014-04-19 | C0005  |
| CL002   | 2014-01-28 | C0001  |
| CL003   | 2014-02-20 | C0003  |
| CL004   | 2014-09-30 | C0002  |
| CL005   | 2014-12-07 | C0004  |

### COMPONENT_CLAIM

| CLAIMID | COMPID | QUANTITY |
|---------|--------|----------|
| CL001   | KK001  | 1        |
| CL003   | KK003  | 2        |
| CL002   | KK002  | 1        |
| CL005   | KK005  | 1        |
| CL004   | KK004  | 2        |

---

## 💡 SQL Tasks

1. Create table `CUSTOMER`, `CAR_COMPONENT`, `CLAIM`, and `COMPONENT_CLAIM`.
2. Insert all data into each table.
3. Type SQL command to find customer name from `CUSTOMER` table.
4. Type SQL command to display component ID, component name and price **between 200 and 400**.
5. Type SQL command to display car number that **begins with 'J'**.
6. Type SQL command to display `CLAIMID` and `QUANTITY` where claim number is **CL001** or **CL004**.
7. Type SQL command to find the **minimum** value for `PRICE` in `CAR_COMPONENT` table.
8. Type SQL command to find the **maximum** value for `PRICE` in `CAR_COMPONENT` table.
9. Type SQL command to find the **average** value for `PRICE` in `CAR_COMPONENT` table.
10. Type SQL command to find the **sum** of `PRICE` in `CAR_COMPONENT` table.
11. Type SQL command to **count the number of customers**.

---

