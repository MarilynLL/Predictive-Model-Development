# Predictive-Model-Development
>This code lines are useful to create a predictive model where the user can determine the probability of default in credit risk area. First, the user clean and apply the database. Then, the LightGBM classifier is built and trained for implement it to know which observations correspond to a defaulter.

## Activities Summary
### 1. Clean the Database 
- Treat missing observations.
- Select some information according to a technical note.

### 2. Develop LGBM model
- NOTE: This model was selected because of the technical note.
### 3. Adjust hyperparameters
- According to the type of model.
### 4. Implement the model to data
- Train the model applying data so the accuracy obtained is about 70
### 5. Get probability of default results
- Look at PI table.
- This probability is about 0 to 1.
### 6. Get defaulters results
- In the column "IMPAGADOR", 0 corresponds to a non-defaulter while 1 corresponds to a defaulter.
