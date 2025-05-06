# Activity 4E: CAR Database (AI-Enhanced)

### Database Schema
Tables: `CUSTOMER`, `CAR_COMPONENT`, `CLAIM`, `COMPONENT_CLAIM` (see below).  

#### CUSTOMER
| CUSTID | CUSTNAME      | CAR_NUMBER | PHONE_NUMBER | REGISTER_DATE |
|--------|---------------|------------|--------------|---------------|
| C0001  | David Teo     | WUV2318    | 81691        | 2014-01-09    |
| C0002  | Sulaiman Ali  | JKJ9782    | 61291        | 2011-05-07    |
| C0003  | Kang Gary     | MAM123     | 41972        | 2010-06-13    |
| C0004  | Ji Hyo        | SA4888     | 11341        | 2012-09-26    |
| C0005  | Karigalan     | KUL511     | 21412        | 2003-07-18    |

#### CAR_COMPONENT
| COMPID | COMPNAME           | PRICE |
|--------|--------------------|-------|
| KK001  | ISWARA Rear Lamp   | 100   |
| KK002  | WIRA Front Bumper  | 450   |
| KK003  | ISWARA Front Mirror| 300   |
| KK004  | WAJA Break Lamp    | 250   |
| KK005  | WIRA Front Lamp    | 600   |

#### CLAIM
| CLAIMID | CLAIM_DATE  | CUSTID |
|---------|-------------|--------|
| CL001   | 2014-04-19  | C0005  |
| CL002   | 2014-01-28  | C0001  |
| CL003   | 2014-02-20  | C0003  |
| CL004   | 2014-09-30  | C0002  |
| CL005   | 2014-12-07  | C0004  |

#### COMPONENT_CLAIM
| CLAIMID | COMPID | QUANTITY |
|---------|--------|----------|
| CL001   | KK001  | 1        |
| CL003   | KK003  | 2        |
| CL002   | KK002  | 1        |
| CL005   | KK005  | 1        |
| CL004   | KK004  | 2        |

---

## STEP 1: Create Tables  
**Task**: Write SQL to create the `CUSTOMER` table with columns:  
- `CUSTID` (VARCHAR, Primary Key)  
- `CUSTNAME` (VARCHAR)  
- `CAR_NUMBER` (VARCHAR)  
- `PHONE_NUMBER` (INT)  
- `REGISTER_DATE` (DATE)  

```sql
-- Your code here
