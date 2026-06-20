🚢 Titanic Dataset Analysis & Advanced Data Visualization

A comprehensive Data Analysis project on the famous Titanic dataset involving Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA), and Advanced Data Visualization using Matplotlib and Seaborn. This project uncovers patterns influencing passenger survival through statistical analysis and visual storytelling. 


---

📌 Project Overview

The Titanic disaster remains one of the most studied datasets in Data Science. This project analyzes passenger demographics, ticket information, travel class, and survival outcomes to identify key factors that influenced survival.

The project includes:

Data Loading & Inspection

Data Cleaning

Missing Value Treatment

Feature Engineering

Exploratory Data Analysis

Advanced Data Visualization

Correlation Analysis

Key Insights Generation



---

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab



---

📂 Dataset Information

Dataset Size: 891 Passengers × 12 Features

Original Features

Feature	Description

PassengerId	Unique Passenger ID
Survived	Survival Status
Pclass	Passenger Class
Name	Passenger Name
Sex	Gender
Age	Passenger Age
SibSp	Siblings/Spouses Aboard
Parch	Parents/Children Aboard
Ticket	Ticket Number
Fare	Ticket Fare
Cabin	Cabin Number
Embarked	Port of Embarkation



---

🧹 Data Cleaning

Missing Values Identified

Column	Missing Values

Cabin	687
Age	177
Embarked	2


Cleaning Techniques Applied

✅ Removed Cabin column due to excessive missing values

✅ Filled missing Age values using Median

✅ Filled missing Embarked values using Mode

✅ Checked and removed duplicate records

Result:

No missing values remaining
No duplicate records found


---

⚙️ Feature Engineering

1. Age Group Classification

Passengers were categorized into:

Child (0–12)

Teenager (13–18)

Young Adult (19–35)

Adult (36–60)

Senior (60+)


2. Family Size

FamilySize = SibSp + Parch + 1

3. IsAlone Feature

IsAlone = 1 if FamilySize == 1 else 0


---

📊 Exploratory Data Analysis

Survival Distribution

Status	Count

Survived	342
Did Not Survive	549


Overall Survival Rate:

38.4%


---

Survival Rate by Gender

Gender	Survival Rate

Female	74.2%
Male	18.9%


Insight

Women had significantly higher survival rates than men.


---

Survival Rate by Passenger Class

Passenger Class	Survival Rate

First Class	63.0%
Second Class	47.3%
Third Class	24.2%


Insight

Higher-class passengers were more likely to survive.


---

Survival Rate by Age Group

Age Group	Survival Rate

Child	58.0%
Teenager	42.9%
Young Adult	35.3%
Adult	40.0%
Senior	22.7%


Insight

Children had the highest survival rate while seniors had the lowest.


---

📈 Advanced Data Visualizations

This project includes multiple visualizations created using Matplotlib and Seaborn. 

1️⃣ Survival Count Bar Chart

Visualizes:

Total survivors

Total non-survivors

Gender-wise survival comparison


Key Finding

> Approximately 74% of females survived compared to only 19% of males.




---

2️⃣ Age Distribution Histograms

Displays:

Overall age distribution

Age distribution by survival status

Mean and median age indicators


Key Finding

Most passengers were between 20–35 years old.


---

3️⃣ Box Plots

Analyzed:

Fare distribution by passenger class

Age distribution by class and survival


Key Finding

First-class passengers paid significantly higher fares and showed better survival rates.


---

4️⃣ Correlation Heatmap

Examined relationships among:

Survived

Pclass

Age

SibSp

Parch

Fare

FamilySize


Important Correlations

Variables	Correlation

Fare ↔ Pclass	-0.55
Survived ↔ Fare	+0.26
Survived ↔ Pclass	-0.34


Interpretation

Higher fares generally indicate higher passenger class.

Higher-class passengers had better survival chances.



---

5️⃣ Pie Chart – Port of Embarkation

Passenger distribution by embarkation port:

Southampton (S)

Cherbourg (C)

Queenstown (Q)


Key Finding

Most passengers boarded from Southampton.


---

6️⃣ Survival Count by Passenger Class

Grouped bar chart showing:

Survivors vs Non-survivors

Across all passenger classes


Key Finding

Third-class passengers experienced the highest mortality.


---

7️⃣ Violin Plot

Analyzed:

Age distribution

Passenger class

Survival status


Key Finding

Younger passengers in Third Class showed slightly better survival rates.


---

8️⃣ Facet Grid Analysis

Visualized:

Age distribution

Gender

Passenger class

Survival status


Key Finding

Women and children in First Class had the highest survival probability.


---

🔥 Key Findings Summary

Dataset Statistics

Total Passengers: 891

Survivors: 342

Deaths: 549


Major Insights

✅ Female passengers had the highest survival rates.

✅ First-class passengers had significantly better survival chances.

✅ Third-class males had the lowest survival rates.

✅ Children were prioritized during evacuation.

✅ Fare positively influenced survival probability.

✅ Most passengers boarded from Southampton.


---

▶️ How to Run

Clone Repository

git clone https://github.com/your-username/Titanic-EDA.git
cd Titanic-EDA

Install Dependencies

pip install pandas numpy matplotlib seaborn

Run Notebook

jupyter notebook Titanic_EDA.ipynb


---

🎯 Learning Outcomes

Through this project, I gained practical experience in:

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Statistical Analysis

Data Visualization

Correlation Analysis

Storytelling with Data

Real-world Dataset Handling



---

👩‍💻 Author

Akanksha
B.Tech – Computer Science & Engineering (AI & ML)

🌟 If you found this project helpful, consider giving it a star! ⭐
