# Food_Choice_Analysis
**Food Choice Analysis: Exploring the Impact of Nutrition Awareness and Early Food Preferences on College Students' Dietary Selections**

![image](https://github.com/aashok30/Food_Choice_Analysis/assets/101622691/729f0c2e-d8e4-4883-bb12-104fef58bba1)

Image Source: https://www.karmicecology.com/wp-content/uploads/2011/09/food-choices.jpg

This study delves into the fascinating realm of food choice among college students, aiming to uncover the intricate interplay between their nutritional knowledge, childhood food preferences, and cooking practices in the family. It delves into whether these factors influence the dietary selections of young adults and whether their taste in food varies based on these factors. The analysis also examines responses to open-ended questions, including students' favorite comfort foods and preferred cuisines. By delving into these aspects, the research seeks to provide valuable insights into the food choices of today's college generation.

## Tools and Libraries Utilized:

For this in-depth analysis, Python served as the primary programming language, operating within the versatile Jupyter Notebook environment. This combination enabled an extensive range of data tasks, encompassing analysis, preprocessing, and model development.

## Data Understanding:
The preliminary phase involved a thorough understanding of the dataset's characteristics. This encompassed examining data shapes and types, with an emphasis on data types including int64, float64, and object (string) categories.

## Data Preprocessing:
In preparation for analysis, a comprehensive data preprocessing pipeline was executed. Key steps included:

Segregation of data into categorical and numerical components, categorizing them as cat_cols and num_cols.
A meticulous missing value treatment procedure was applied. This encompassed identifying missing values, quantifying their presence through percentage analysis, visualizing their distribution using a heatmap, and executing appropriate imputations. Specifically, numerical columns were imputed with the mean, while categorical columns were imputed with the mode.

## Exploratory Data Analysis (EDA):
A fundamental aspect of the study was the exploratory analysis, focusing on gaining valuable insights into the dietary habits and nutritional choices of college students. Key areas of investigation included:

**Breakfast Preferences:** Understanding the breakfast choices among students, such as 'Cereal' and 'Donut.'

**Importance of Daily Caloric Intake:** Analyzing students' perceptions regarding daily caloric intake, categorized as 'Very Important,' 'Moderately Important,' 'Not Important,' or 'Not Known.'

**Cooking Frequency:** Examining the frequency of cooking among students, with options including 'Daily,' '2-3 times/week,' 'Not often,' 'Holidays,' and 'Never.'

**Coffee Preferences:** Investigating students' coffee preferences, distinguishing between 'Creamy Frappuccino' and 'Espresso Shown.'

**Comfort Food Selection:** Understanding the emotional factors influencing food choices, such as 'Stress,' 'Boredom,' 'Depression/Sadness,' 'Hunger,' 'Laziness,' 'Cold Weather,' 'Happiness,' 'Watching TV,' or 'None.'

**Changes in Eating Habits:** Analyzing the changes in students' eating habits, categorized as 'worse,' 'better,' 'the same,' or 'unclear.'

**Favorite Cuisine:** Investigating students' preferred cuisines, which included options like 'Italian/French/Greek,' 'Spanish/Mexican,' 'Arabic/Turkish,' 'Asian/Chineses/Thai/Nepal,' 'American,' 'African,' 'Jamaican,' and 'Indian.'

## Data Encoding:
The data encoding process was pivotal for facilitating subsequent analyses. It involved the utilization of label encoding techniques to convert object data types. The newly created object variable, obList, played a significant role in this endeavor.

## Feature Selection:
An essential component of the analysis involved the selection of pertinent features. This process was instrumental in optimizing the performance of the subsequent analytical models.

## Data Scaling:
In specific cases, data scaling techniques were applied to ensure that variables were within suitable ranges for modeling purposes.

## Model Selection:
The choice of the K-Means clustering algorithm for this analysis was driven by its relevance to the research objectives. The selection of the optimal number of clusters (K) was performed through the Elbow method, with experimentation involving K values of 2, 3, and 4. Ultimately, K = 4 was determined to be the most suitable choice to underpin the subsequent analytical steps.

This thorough analysis was conducted to provide comprehensive insights into the dietary choices and preferences of college students, contributing valuable information for research and decision-making processes.
