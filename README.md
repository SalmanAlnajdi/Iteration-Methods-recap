# iterationMethodsTask_part1

1. Create a new repo in GitHub and name it `iterationMethods_recap1`
2. Clone the repo into your development folder 
3. Open the folder you just cloned in VScode 
4. Create `index.js` file, copy the below code into it, and start solving the task

```jsx
// You are given an array representing a series of financial records for a freelance worker.
// Each record is an array containing the record type ("income", "expense", "investment", or "refund") and the amount.
const financialRecords = [
    ["income", 1800],
    ["expense", 500],
    ["investment", 1000],
    ["income", 2400],
    ["refund", 200],
    ["expense", 800],
    ["income", 1500],
];

/*****************************************************************
Part 1: Record Categorization

Task 1) Create a new array containing only "income" and "refund" records.
       Output 1) [["income", 1800], ["income", 2400], ["refund", 200], ["income", 1500]]

Task 2) Create a new array containing only "expense" and "investment" records.
       Output 2) [["expense", 500], ["investment", 1000], ["expense", 800]]

******************************************************************/

/*****************************************************************
Part 2: Financial Calculations

Task 3) Calculate the total for "income" and "refund" records combined.
       Output 3) 5900

Task 4) Calculate the total for "expense" and "investment" records combined.
       Output 4) 2300

******************************************************************/

/*****************************************************************
Part 3: Detailed Analysis

Task 5) Determine the net financial impact (total for "income" and "refund" - total for "expense" and "investment").
       Output 5) 3600

Task 6) Identify and create a new array with records where the amount is greater than $800.
       Output 6) [["income", 1800], ["investment", 1000], ["income", 2400], ["income", 1500]]

******************************************************************/

// Use JavaScript array methods like filter and reduce to achieve the desired outputs for each task.
```

1. Save the file and push your code
