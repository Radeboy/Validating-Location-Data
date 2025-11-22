This project is for a specific dataset, so check it and edit appropriately before using.
Note that it may take a while to run if you have a large dataset. (about 1s per row).
The code is useful when you have secondary or tertiary dataset and you want to validate the location provided and ensure consistency.

For this dataset, there were address and postal code columns.
The aim of the project was to 
- compare the address to the standardized postal code.
- check if the provided postal code in the dataset is valid based on the provided address.
- indicate which rows have a wrong postal code.
- replace the postal code with the new and correct postal code.

The author recognized that many persons during data collection are more likely to input their address correctly and less likely to input their correcsponding postal code correctly.
So this method was devised to validate the postal code, assuming the address is correct.
