# COVID-19-Symptoms-Optimizer
- A patient suffering from the COVID-19 disease can have multiple symptoms due to the virus
- This study aims to identify those combination of symtoms that when present together in a patient could have higher probability of leading to fatality
- This work is done in association with Prof. Chun-An Chou leveraging his paper to build the models 
- The data contains demographic information, travel information and a list of all the symptoms that each patient carries
- The first step is generating association rules between individual symptoms which are generated in R, using the Apriori algorithm to prepare high probability groups of potentially lethal symptoms 
- After this, matrices related to demographic information and symptoms are generated which are then fed into the optimization model that's built in Python and solved using the - - GurobiPy solver.
- The result got from this multiple integer optimization model is fewer and more optimal symptom groups that if present in a patient could lead to fatality  
