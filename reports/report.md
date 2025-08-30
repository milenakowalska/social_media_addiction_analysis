# About the dataset
- 705 individuals at the age of 18-24.

## Data dictionary

|Column|Description|Type|Units/Scale |Possible Values |
|-----|-----|-----|-----|-----|
|Student_ID|Unique student's identifier|Integer|-|1, 2, 3, ...|
|Age|Student’s age|Integer|Years|18-24|
|Gender|Student’s gender|Categorical|-|Male, Female|
|Academic_Level|Student's education level|Categorical|-|High School, Undergraduate, Graduate|
|Country|Student's country|Categorical|-|e.g., USA, India, Germany|
|Avg_Daily_Usage_Hours|Avg hours per day spent on social media|Float|Hours|0–24|
|Most_Used_Platform|Most used social media platform|Categorical|-|e.g., Instagram, Facebook, TikTok|
|Affects_Academic_Performance|Whether social media affects academic performance|Boolean|-|Yes, No|
|Sleep_Hours_Per_Night|Average sleep duration per night|Float|Hours|0–24|
|Mental_Health_Score|Self-rated mental health|Integer|1–10|1 = poor, 10 = excellent|
|Relationship_Status|The student's relationship status|Categorical|-|Single, In Relationship, Complicated|
|Conflicts_Over_Social_Media|The number of relationship conflicts due to social media|Integer|Count|0, 1, 2, …|
|Addicted_Score|Social media addiction score|Integer|1–10|1 = low, 10 = high|


# Research overview

The aim of this study is to investigate the relationship between social media addiction and factors such as demographic characteristics and the effects of social media usage on daily life. The study is divided into two parts: descriptive / exploratory analysis and predictive models using Machine Learning.  

## Descriptive / Exploratory Analysis
1. Which features (Age, Gender, Academic_Level, Country, Average daily usage hours) are associated with social media addiction?
2. Which social media platform has the highest average addiction score among its users?
3. How are average daily social media usage (in hours) and addiction score related to outcomes such as:

    a. Affects academic performance, 

    b. Sleep hours per night,

    c. Mental health score, 

    d. Relationship status?

4. Does the effect of daily usage differ across gender or academic level?

## Predictive / Machine Learning
5. How accurately can social media addiction score be predicted based on Age, Gender, Academic Level, and Country?

The 5th research question is formulated as a regression problem. The target variable is Addicted_Score.
Evaluation metrics will be: RMSE (Root Mean Squared Error) and R² (Coefficient of Determination)


# References
Shamim, A. (n.d.). Students' Social Media Addiction vs Relationships. Kaggle. Retrieved August 28, 2025, from https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships