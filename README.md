# FrothFlotationModel
Predicting the effectiveness of a Froth floating process

# Project Description:

We will use this dataset to analyse and predict the Froth floating process having the two aims:

What is the best predictor for the iron concentration of the product?

Can the data set be used to predict the impurity of the product (by silicate concentration)?
# Data Description:

This project deals with the analysis of a reverse cationic flotation process of a real production environment. 

# The Froth flotation process
The froth floatation is used to seperate the iron contents in the ore from other contaminations. The whole process usually contains for steps:

Contioning of the ore feed pulp (mixture of ore and water) and other reagents
Separation of hydrophobic and hydrophilic materials: binding particles attach to the bubbles
The bubbles transport the particles upwards until they float on the surface (froth)
Collection of the froth by mechanical separation (e.g. by an impeller)

# The dataset can be found here :
https://drive.google.com/open?id=1SBDxQAULXDTMvFpc-zHY4kxcFuWZPMVU

About this Dataset
Context
It is not always easy to find databases from real world manufacturing plants, specially mining plants. So, I would like to share this database with the community, which comes from one of the most important parts of a mining process: a flotation plant!

The main goal is to use this data to predict how much impurity is in the ore concentrate. As this impurity is measured every hour, if we can predict how much silica (impurity) is in the ore concentrate, we can help the engineers, giving them early information to take actions (empowering!). Hence, they will be able to take corrective actions in advance (reduce impurity, if it is the case) and also help the environment (reducing the amount of ore that goes to tailings as you reduce silica in the ore concentrate).

Content
The first column shows time and date range (from march of 2017 until september of 2017). Some columns were sampled every 20 second. Others were sampled on a hourly base.

The second and third columns are quality measures of the iron ore pulp right before it is fed into the flotation plant. Column 4 until column 8 are the most important variables that impact in the ore quality in the end of the process. From column 9 until column 22, we can see process data (level and air flow inside the flotation columns, which also impact in ore quality. The last two columns are the final iron ore pulp quality measurement from the lab. Target is to predict the last column, which is the % of silica in the iron ore concentrate.

Inspiration
I have been working in this dataset for at least six months and would like to see if the community can help to answer the following questions:

Is it possible to predict % Silica Concentrate every minute?

How many steps (hours) ahead can we predict % Silica in Concentrate? This would help engineers to act in predictive and optimized way, mitigatin the % of iron that could have gone to tailings.

Is it possible to predict % Silica in Concentrate whitout using % Iron Concentrate column (as they are highly correlated)?
