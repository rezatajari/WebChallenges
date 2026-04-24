# Loan Qualification Checker

## Overview

In this challenge, you will build a **Loan Qualification Checker App** using JavaScript conditionals.
The program determines whether an applicant qualifies for a **duplex**, **condo**, or **car loan** based on their **annual income** and **credit score**.

A **credit score** represents how reliable someone is when it comes to managing borrowed money — higher scores indicate better creditworthiness.

This project helps you practice:

* Using conditional statements (`if`, `else if`, `else`)
* Comparing numeric values with relational operators (`>=`, `<`)
* Working with functions that return specific results
* Declaring and testing multiple variables

---

## Objective

Create a program that checks an applicant’s loan eligibility based on minimum income and credit score requirements for different loan types.
Return the correct qualification message for each scenario.

---

## User Stories

1. Create variables that store the minimum income and credit score requirements for each loan type:

   * `minIncomeForDuplex` = 60000
   * `minCreditScoreForDuplex` = 700
   * `minIncomeForCondo` = 45000
   * `minCreditScoreForCondo` = 680
   * `minIncomeForCar` = 30000
   * `minCreditScoreForCar` = 650

2. Define a function named `getLoanMessage` that takes two arguments:

   * `annualIncome`
   * `creditScore`

3. Inside the function:

   * If both values meet or exceed the duplex requirements, return
     `"You qualify for a duplex, condo, and car loan."`
   * Else if both values meet or exceed the condo requirements, return
     `"You qualify for a condo and car loan."`
   * Else if both values meet or exceed the car requirements, return
     `"You qualify for a car loan."`
   * Otherwise, return
     `"You don't qualify for any loans."`

4. Outside the function:

   * Create four variables that call the function with different inputs:

     * `duplexLoanMsg = getLoanMessage(85000, 850)`
     * `condoLoanMsg = getLoanMessage(65000, 690)`
     * `carLoanMsg = getLoanMessage(45000, 660)`
     * `noLoanMsg = getLoanMessage(25000, 550)`

5. Log each variable to the console to display the result.

---

## How It Works

1. The program uses conditional logic to compare the applicant’s income and credit score against predefined thresholds.
2. Depending on which thresholds are met, the function returns the appropriate qualification message.
3. The results are then printed to the console to show which loan(s) the applicant qualifies for.

---

## Technologies Used

* JavaScript (ES6)
* Node.js or browser console environment

---

## Goal

When you run the program, it should correctly determine and display which type of loan(s) each applicant qualifies for — or inform them that they don’t qualify for any.
