Group Name: Pitt-Trash-Can

# Group Members: 
Eva Frankovic: emf104@pitt.edu
Garrett DiCenzo: gad51@pitt.edu
John Segebart: jes354@pitt.edu

# Description
We are trying to find the best neighborhood based on general quality. We thought a great way to find that is to rate each neghborhood in 3 categories: Number of Trees, Cleanliness of Streets, and Amount of Police Incidents. Each neighborhood will be given a rating between 1 to 100 with 1 being the worst and 100 being the best. A computation will then be used to give each neighborhood a true rating based off of the ratings they received from each category.

# Links to Datasets Used
Number of Trees: https://data.wprdc.org/dataset/city-trees/resource/1515a93c-73e3-4425-9b35-1cd11b2196da

Cleanliness of Streets: https://data.wprdc.org/dataset/street-sweeping-routes/resource/a5f3ae45-0716-4652-a85c-a69424f2f4f7

Amount of Police Incidents: https://data.wprdc.org/datastore/dump/1797ead8-8262-41cc-9099-cbc8a161924b

# Abstract
Using the combined metric for all three datasets shows that the best neighborhood is Squirrel Hill. We arrived at this conclusion by using a universal metric across all three datasets where we took maximum value in each dataset and divided each value in the relevant column ("Quantity" for trees, "Travel Miles" for street sweeps, and "Incidents" for Police Incidents) by the max and converted each value to a percentage of that max. The rating score was set equal to each of those percentages. In the final metric, we concatenated all of the datasets together and sorted them by the mean of each neighborhood. 
