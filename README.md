# Modeling Project

## Team Members: Sam Crowl and Jack Echols

The updated netlogo code, data from the experiment runs, and the code used to generate
plots and perform statistical tests can all be found in this repository.

### Updated Wound Healing Model

Within WoundInfectionModel_Update.nlogo, the following changes were made:

1. An additional agent was added, called bacteria2. In the model, this serves as the
prey bacteria. It follows the same logic as the bacteria from the original model. 

2. A switch which will turn bacteria1 into a predator bacteria that will eat bacteria2
if it comes into contact. 

3. An extra slider and chooser to allow for bacteria1 (predator) and bacteria2 (prey) to
have different initial amounts of cells and different proliferation rates.

4. A slider from 0 to 5, which sets the number of new bacteria1 generated when a bacteria1
turtle consumes bacteria2. In our report, the slider was set to 3.

5. A slider which indicates how likely a macrophage or neutrophil is to kill bacteria1
if it comes into contact. This setting was not used in our final report, as it did not
significantly change the conclusions made.

6. The plot was updated to include counts of total bacteria, bacteria1 and bacteria2

### Data Files

There are two different .csv files that hold the data used for our report. The 'one_cell_experiments_ver5.csv' file 
holds the data for 10 runs with only bacteria2 present. The 'two_cell_experiments_ver5.csv' file has the data for runs when 
both bacteria agents were present. This includes results for both when bacteria1 is 
and is not predatory.

### Code

All code used for this project beyond NetLogo can be found in the jupyter notebook,
'plotting.ipnyb'.