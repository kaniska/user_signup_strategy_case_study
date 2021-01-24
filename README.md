# User signup strategy Case Study

## Goal: 

Develop ML Models for improving the chance of user signups for a product 

## Data: 

Bank Product Campaign data: 

-- The dataset provided is tied to the direct marketing campaigns of a banking institution. 
-- The campaigns were direct phone calls to the customer. 
-- The goal of the campaign was to get them to subscribe to a product. 
-- Often, more than one contact to the same customer was required before the goal was achieved. 

### Client info

-- age (numeric)
-- job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
"blue-collar","self-employed","retired","technician","services") 
-- marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
-- education (categorical: "unknown","secondary","primary","tertiary")
-- default: has credit in default? (binary: "yes","no")
-- balance: average yearly balance, in euros (numeric) 
-- housing: has a housing loan? (binary: "yes","no")
-- loan: has personal loan? (binary: "yes","no")

### Info on last contact of the current campaign

-- contact: contact communication type (categorical: "unknown","telephone","cellular") 
-- day: last contact day of the month (numeric)
-- month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
-- duration: last contact duration, in seconds (numeric)

### Other data

-- campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
-- pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
-- previous: number of contacts performed before this campaign and for this client (numeric)
-- poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

### Output

y - has the client subscribed to the product? (binary: "yes","no")

## Report

https://docs.google.com/document/d/1tjdfZnF4mhVAWDjxUAcBMmRLXKhaPxtwQVp1QUJ3SvQ/edit?usp=sharing
