GROUP 9 Final Project Issued Construction Permits

Group Members:
Neal Friesenhahn

Link to dataset used:
https://data.austintexas.gov/Building-and-Development/Issued-Construction-Permits/3syk-w9eu

*Note size is about 1.12 GB so it isn't included in this repo.
-Might include reduced dataset after cleaning is done. 


FILES TO ADD IN ZIP:

README.txt // Text file describing contents of project and files contained within

Group 9 Data Mining.ipynb // Jupyter Notebook of the project with data cleaned just enough to run on Darwin, uses Boosted trees
                          // partitions data by first 10th and last half,  1:5 test to train records ratio.

Random Sampling Random Forest.ipynb // Random sampling approach to dataset instead of partitioning blocks from dataset

ReducedImportFeatures.ipynb  // Takes the most important features from Group 9 Data Mining.ipynb and trains a model on just those
                             // features. 

Issued_Construction_Permits.csv // Complete Dataset used in this project, 1.12 GB in size

login.txt // Used to store creditials when running the program

FILES THAT ARE GENERATED:

train.csv   // File generated to train the model on Darwin

test.csv    // File generated to test the model on Darwin

cleaned.csv // (Optional) File downloaded from Darwin after clean is ran on train.csv

prediction.csv // (Optional) File downloaded from darwin with predictions made
