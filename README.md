# Classify--GUI-for-ML-Classification
An interactive GUI for running 4 ML classifcation algorithms and obtain results and plots for analysis purpose.

Hello Friends!

It is my first GUI which solely aims to remove all code work required in ML Analysis. I will guide you through some steps to get started.

Step 1: Use select button to select a csv file.
Step 2: Press show button to see 50 records of your dataset. RESET button is  to start from scratch so press only when you want to change your file
Step 3: You can go through histplot and heat map to check correlation throught whole data
Step 4: Accordingly select X features and target y variable. y must not be in X selected features
Step 5: Check corr plot and pair plot and if you need to change features then click feature change button. These plots change when features selected are changed and its based upon your y variable.
Step 6: Give test size and random state. Click split
Step 7: CLick predict and give parameters as per your need. Only some important parameters are covered.
Step 8: Check the results left of predict button and in the bottom 'Output analysis section'
Step 9: Repeat for other algorithms

NOTE:
1. This gui doesnt support categorical variables
2. Some plots take time to display so dont think it froze. Tweaking some parameters in code can make execution faster if needed
3. In output analysis section. Ignore the warnings coming in output terminal since its version problem. If still wanna remove then import filterwarnings module or just change X_train to X_train.values in fit model.

Comments and issues are most welcome. Will be glad to make this GUI better. Feel free to edit the code in your way and most importantly, have fun coding!!


