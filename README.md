# Food Claims Process Analysis 

## Company Background¶
Vivendo is a fast food chain in Brazil with over 200 outlets. As with many fast food establishments, customers make claims against the company. For example, they blame Vivendo for suspected food poisoning.

The legal team, who processes these claims, is currently split across four locations. The new head of the legal department wants to see if there are differences in the time it takes to close claims across the locations.
![tingey-injury-law-firm-L4YGuSg0fxs-unsplash](https://user-images.githubusercontent.com/108904370/204107374-ca7d25aa-89db-4e23-b2cc-4574034476df.jpg)


### Customer Question
The legal team has given you a data set where each row is a claim made against the company. They would like you to answer the following questions:

How does the number of claims differ across locations?
What is the distribution of time to close claims?
How does the average time to close claims differ by location?

### Dataset
The dataset contains one row for each claim. The dataset can be downloaded from here.

The dataset needs to be validated based on the description below:

Column Name	Criteria
Claim ID	Character, the unique identifier of the claim.
Time to Close	Numeric, number of days it took for the claim to be closed.
Claim Amount	Numeric, initial claim value in the currency of Brazil. For example, “R$50,000.00” should be converted into 50000.
Amount Paid	Numeric, total amount paid after the claim closed in the currency of Brazil.
Location	Character, location of the claim, one of “RECIFE”, “SAO LUIS”, "FORTALEZA", or "NATAL".
Individuals on Claim	Numeric, number of individuals on this claim.
Linked Cases	Binary, whether this claim is believed to be linked with other cases, either TRUE or FALSE.
Cause	Character, the cause of the food poisoning injuries, one of 'vegetable', 'meat', or 'unknown'. Replace any empty rows with 'unknown'

To view my code, the processes in which I took to validate the data, model the data and then step by step analysis and insights 
https://github.com/FaithOIgwe/Food-Claims-Process-Analysis-in-Python/blob/main/Food%20Claims%20Analysis.ipynb
