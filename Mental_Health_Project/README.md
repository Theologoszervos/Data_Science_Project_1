# First-project
Dataset source:https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset/data

Team_Name : Mental Health Buddies
Team_Members : Avaritsioti Olympia, Zachos Panos, Zervos Theologos

Scope: 1st Project of Bootcamp Data Science at Big Blue Data Academy.

Data: This dataset is based on a mental health questionnaire and demographic information, work-related factors, and self-reported mental health indicators.

Data cleaning process :
1.Timestamp column convert from object to datetime.
2.creation of separate columns of year and month for possible future outcoms and data analysis.
3.The dataset contained missing values exclusively in the self_employed feature. To preserve the original distribution, missing values were imputed based on the proportion observed in the non-null entries (approximately 90% and 10%, respectively).

Exploratory Data Analysis :
Insights made under three separate groups:
->No students females (Males analysis)
->No students males	(Females analysis)
->Students

Insights:
1.For females time spend indoors correlates with the change in habits & the occupation

2.For females there is not important correlation for family history and mental health history

3.Regarding our data, since the dataset did not include direct metrics or an index metric of any kind, we estimated mental illness by assigning equal weights to the available categories and identified in descending order which countries where most affected by this index metric.
(Note that through creating our own index metric(Total_Score), some of our dataset columns such as Coping_Struggles and Work_Interest where added in reversed manner meaning.
 They where negatively impactful to our index metric(Total_Score) and not positively in comparison to the rest data provided.)

4.We found that the number of students with a mental health score above the average is not associated with family history, as there were more cases among those without a family mental health background.

5.Additionally, for students with a score above the average, mental health outcomes do not appear to depend on the frequency of staying indoors

6.Higher Score means greater impact in overall Mental Health per Male person.

7.Lower Score means lesser impact in overall Mental Health.

8.Moldova seems to be leading in Mental Health issues and on the other hand Croatia,Greece,Mexico etc. countries seem to have the best work-to-life balance and general mental Illness state in correlation to our aforementioned factors.         