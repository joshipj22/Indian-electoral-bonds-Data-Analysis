# Indian-electoral-bonds-Data-Analysis
Electoral Bonds were a mode of funding for political parties in India from their introduction in 2017 to curb black money in Indian politics until they were struck down as unconstitutional by the Supreme Court on February 15, 2024 for lack of transparency. 

In its judgment dated 15 February, the Supreme Court had ordered that by 6 March, SBI must submit the details of the electoral bonds purchased between 12 April 2019 and 15 February 2024, to the Election Commission.

The court said that the details, which must include the date of purchase of each electoral bond, the donor's name, which party they donated to, and the denomination of the electoral bond purchased, must be made public by the EC by 13 March.

In its application to the apex court on 4 March, two days before the deadline set by the court, the SBI said that 22,217 electoral bonds were issued to various parties between 12 April 2019 to 15 February 2024.

**The SBI said that since the redeemed bonds were sent to the main SBI branch in Mumbai by the authorised branches, it has to decode and compile 44,434 (22,217x2) information sets and needed atleast 3 months before it could establish a money trail between the benefactors and beneficiaries.** 


# How was this obtained?
It was extracted from the PDFs released by the Election Commission of India https://www.eci.gov.in/disclosure-of-electoral-bonds
Electoral bonds are a financial instrument introduced in India to facilitate transparent political funding.
The inormation is fragmented into 2 tables 
**Puracase details :** https://www.eci.gov.in/eci-backend/public/api/download?url=LMAhAK6sOPBp%2FNFF0iRfXbEB1EVSLT41NNLRjYNJJP1KivrUxbfqkDatmHy12e%2FzBiU51zPFZI5qMtjV1qgjFmSC%2FSz9GPIId9Zlf4WX9G%2FfwrEDQFGDuen%2FyU1C5gVqkKaRPDqHSBCdx74poKJJ7Q%3D%3D

**Redemption Details:**  https://www.eci.gov.in/eci-backend/public/api/download?url=LMAhAK6sOPBp%2FNFF0iRfXbEB1EVSLT41NNLRjYNJJP1KivrUxbfqkDatmHy12e%2FzBiU51zPFZI5qMtjV1qgjFmSC%2FSz9GPIId9Zlf4WX9G%2FfwrEDQFGDuen%2FyU1C5gVqkKaRPDqHSBCdx74poKJJ7Q%3D%3D
Let’s break down the columns related to electoral bonds:

**Serial Number (Sr No.):**
This column provides a unique reference number for each electoral bond. It helps in indexing and tracking the bonds.

**Date of Encashment:**
This column indicates the date on which the electoral bond was redeemed or encashed by the political party.
When a political party receives an electoral bond, it can later redeem it for funds.
 
**Name of the Political Party:**
In this column, you’ll find the name of the political party that redeemed the electoral bond.
The party’s name is associated with the specific bond, allowing transparency in political funding

**Account Number Prefix:** 
The first few digits of the account number associated with the political party.

**Bond Number:** 
A unique alphanumeric identifier printed on the electoral bond.

**Denominations:**
The value of the bond (e.g., 1000, 10000, 100000, 1000000, and 10000000.).

**Pay Branch Code:**
The code of the bank branch where bond was encashed.

**Pay Teller:**
The teller or bank official who handled the transaction

**Status:**
Indicates whether the bond was successfully redeemed
The State Bank of India (SBI) submitted

**Date of\rPurchase:**
Date on which the electoral bonds were purchased by a private entity for the consumption of the political party

**Name of the Purchaser:**
Any private entity or corporate house that purchases the electoral bond i.e. donating money 
**
