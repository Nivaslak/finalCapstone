# Investment and Bond Calculator
This Python script calculates the amount of interest on an investment or the monthly repayment amount for a home loan (bond). It provides options for calculating both simple and compound interest for investments.
## Usage
1. Clone the repository to your local machine.
2. Open the script in a Python environment.
3. The program will display a menu with two options:
   - `investment`: Calculate the amount of interest you'll earn on your investment.
   - `bond`: Calculate the amount you'll have to pay on a home loan.
4. Enter your preferred choice (`investment` or `bond`).
5. Follow the prompts and enter the required information:
   - For `investment`:
     - Enter the deposit amount (`P`).
     - Enter the rate of interest (`r`) as a decimal or percentage.
     - Enter the number of years you plan to invest (`t`).
     - Choose between `simple` or `compound` interest.
   - For `bond`:
     - Enter the value of your house (`P`).
     - Enter the number of months to repay the bond (`n`).
     - Enter the rate of interest (`r`) as a decimal or percentage.
6. The program will calculate and display the results:
   - For `investment`:
     - If simple interest is chosen, it will display the total amount (`A`) you will get back after `t` years.
     - If compound interest is chosen, it will display the total amount (`A`) you will get back after `t` years.
   - For `bond`, it will display the monthly repayment amount (`A`).
## Investment Formula:
 The total amount when simple interest is applied is calculated as follows: 𝐴 = 𝑃(1 + 𝑟 × 𝑡) 
The Python equivalent is very similar: A = P*(1 + r*t)
 The total amount when compound interest is applied is calculated as follows: 𝐴 = 𝑃(1 + 𝑟) ^𝑡
 The Python equivalent is slightly different: A = P * math.pow((1+r),t) 
In the formulae above: 
● ‘r’ is the interest entered above divided by 100, e.g. if 8% is entered, then r is 0.08.
 ● ‘P’ is the amount that the user deposits. 
● ‘t’ is the number of years that the money is being invested.
 ● ‘A’ is the total amount once the interest has been applied.

## Bond Repayment Formula:
 The amount that a person will have to be repaid on a home loan each month is calculated as follows: 𝑟𝑒𝑝𝑎𝑦𝑚𝑒𝑛𝑡 = 𝑖 × 𝑃/ 1− (1+𝑖) −𝑛
 The Python equivalent is slightly different:
 repayment = (i * P)/(1 - (1 + i)**(-n))
 In the formula above:
 ● ‘P’ is the present value of the house.
 ● ‘i’ is the monthly interest rate, calculated by dividing the annual interest rate by 12.
 Remember to divide the interest entered by the user by 100 e.g. (8 / 100) before dividing by 12. 
● ‘n’ is the number of months over which the bond will be repaid.
