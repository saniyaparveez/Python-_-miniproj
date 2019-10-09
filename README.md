"# TestRepo" 
FINANCING A CAR

The following project includes :
1. Car loans : monthly payments calculated and equated in monthly installments
2. Interest Paid : (APR) how it affects the monthly payments
3. How the length of the loan affects total interest paid 

Car loans :
In Emi we pay interest and principal each month  
The formula for calculating this is 
 
P * r(1 + r)^n / (1 + r)^n - 1
where 
  P : Principal 
  r : rate
  n : term
Calculations :

r = Interest paid / 12  (1 year)

num = ( r * ((1 + r)**(n)))

deno = ((1 + r)**(n))-1

emi = P *(num/deno)
emi
