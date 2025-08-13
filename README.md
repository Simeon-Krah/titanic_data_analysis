Exploratory Data Analysis on the Titanic Dataset

📝 Introduction

This repository contains a Jupyter Notebook with an Exploratory Data Analysis (EDA) of the famous Titanic passenger dataset. The primary goal of this project is to uncover patterns and relationships in the data to understand the factors that influenced a passenger's survival.



🚢 Dataset

The dataset used in this analysis is the well-known Titanic dataset, which includes information on passenger demographics, ticket fares, class, and survival status.



Key columns analyzed include:



Age: Passenger's age



Fare: The ticket price paid by the passenger



Sex: Gender of the passenger



Survived: Survival status (0 = Died, 1 = Survived)



Pclass: Passenger class (1st, 2nd, or 3rd)



🔍 Key Findings

Through visualizations and statistical analysis, several significant insights were discovered:



Age and Survival: The survival rate was heavily influenced by age. A disproportionately high number of children under 10 survived, while the majority of casualties were young adults in their 20s and 30s.



Fare and Survival: There is a strong correlation between the fare paid and survival. Passengers who paid higher fares had a much greater chance of survival, while most of the casualties were among those who paid the lowest fares.



Categorical Encoding: Categorical features like Sex and Embarked were successfully one-hot encoded to prepare the data for potential machine learning models.



🛠️ Tools and Libraries

This project was built using the following Python libraries:



Pandas: For data manipulation and analysis.



NumPy: For numerical operations.



Seaborn: For creating stunning statistical visualizations.



Matplotlib: For plotting and data visualization.



Scikit-learn: For data preprocessing and machine learning utilities.



**NB:** Ideally, matplotlib.inline was supposed to working, making figures show without plt.show(), but that was not the case for me. 

