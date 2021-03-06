# stock-analysis
## Overview of Project
The objective of this project is to **refactor** the existing VBA code created in *module 2* in order to run faster and more efficient. Once completed, the script will help #Steve# analyze the performance of *12* stocks for *2017* and *2018*. 

The results of his analysis will assist him to advise his parents with a good stock to invest in.

## Results
### Stock Performance Comparison
Looking at both tables below, we can conclude that ***ENPH*** and ***RUN*** are both good stocks to invest in since their return was positive in both years.

![Time Analysis for 2017](./Resources/VBA_Challenge_2017_Returns.png)

![Time Analysis for 2018](./Resources/VBA_Challenge_2018_Returns.png)

### Code Performance Comparison
As for the code performance, I noticed a huge improvement between the time it takes to run the original script vs. the refactored one. Refactored code runs at approximately 12%-15% of the time it takes to run the original code. The bar chart below helps visualize the improvement.

![Time Analysis for 2017](./Resources/Org_vs_Refac_Time_Analysis.png)

#### Original Code
![Time Analysis for 2017](./Resources/VBA_Challenge_2017_ORG.png)

![Time Analysis for 2018](./Resources/VBA_Challenge_2018_ORG.png)

#### Refactored Code
![Time Analysis for 2017](./Resources/VBA_Challenge_2017.png)

![Time Analysis for 2018](./Resources/VBA_Challenge_2018.png)

## Summary
### What are the advantages or disadvantages of refactoring code?

Some of the advantages of refactoring code are:
- Makes code easier to read and understand
- Helps find bugs
- Introduction of more efficient patterns
- Review by peers
- Makes codes more flexible (more extensible)

Disadvantages can be:
- Time consuming
- Can be costly
- Chances for errors

References:

1. [AnAr](https://anarsolutions.com/code-refactoring-concept-analysis/)
2. [Stack Overflow](https://stackoverflow.com/questions/43983284/what-are-the-advantages-and-disadvantages-of-refactoring-code-smell-in-software)
3. [C# Corner](https://www.c-sharpcorner.com/article/pros-and-cons-of-code-refactoring/)


### How do these pros and cons apply to refactoring the original VBA script?

#### PROS
The code runs much faster now as illustrated above. This performance improvement is a result of using one ***FOR*** loop to read and store data from the sheet vs. the nested loop used in the original script. 
Another advantage is: The code now is well structured and commented, which makes it easier for others to read and understand.

#### CONS
It was time consuming to write the refactored code. In real life, time is **MONEY**.

---

![Saeed Al-Yacoubi](./Resources/qr-code.png)