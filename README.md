#Titanic Problem
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.
One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.
In this exercise, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.


#Data Description
    survival Survival(0 = No; 1 = Yes)
    pclass Passenger Class(1 = 1st; 2 = 2nd; 3 = 3rd)
    name Name
    sex Sex
    age Age
    sibsp Number of Siblings/Spouses Aboard
    parch Number of Parents/Children Aboard
    ticket Ticket Number
    fare Passenger Fare
    cabin Cabin
    embarked Port of Embarkation(C = Cherbourg; Q = Queenstown; S = Southampton)


#Problem Statement
Based on problem description, I decided to treat this as a classification problem by trying to predict the value of Survived variable for each instance.
In order to finish this task and create a model to predict who survived or died? I will use following libraries:

    NumPy
    IPython
    Pandas
    SciKit-Learn
    SciPy
    StatsModels
    Patsy
    Matplotlib
    

#How to run the code?
This is a jupyter notebook, so you need to install the jupyter environment and my suggestion is Anaconda from here https://www.continuum.io/downloads
