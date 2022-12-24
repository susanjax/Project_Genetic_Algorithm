# Project_Genetic_Algorithm
Here all the codes and instructions for building genetic algorithm with machine learning is provided.


steps of data preprocessing, model building and hyperparameter tuning are separated into different files with name starting as Part..

Validation using external dataset
Steps:
 1. Data were collected and combined creating a single file, combined_all_purified.csv
 2. Descriptors were added using descriptor_addition.ipynb file
 3. outliers were removed using Part_1...ipynb file and a preprocessed_data.csv file
 4. ordinal encoding is used to convert categorical information while standard scaler is used for scaling the numerical values and a scaled_original...csv and scaled_external...csv file are generated.
 5. using Part_2..ipynb file model comparision were done to find best model 
 6. using Part_3...ipynb file lgbm hyperparameter tuning and visulization 
 7. using Part_3_1...ipynb file 10 fold cross validation was performed. 
