# EDA-on-Titanic-Dataset
This project explores the Titanic dataset to understand the factors that influenced passenger survival using Python and visualization libraries.

## 🧮 Feature Engineering
To enhance the analysis, several new features were created:
FamilySize = SibSp + Parch + 1

-FamilyType:
Alone (1 member)
Small (2–4 members)
Big (5+ members)
- AgeGroup:
Child (≤12)
Teen (13–20)
Adult (21–64)
Old (≥65)

### 📊 Key Insights
- Univariate Analysis
🔹Majority of passengers were adults aged 20–40 years.
🔹Fare distribution is right-skewed, with most paying under $100.
🔹Most passengers traveled in 3rd class (~55%).
🔹Majority embarked from Southampton (S).

- Bivariate Analysis
🔹Gender: Females had a survival rate of ~74%, while males had only ~19%.
🔹Class: 1st-class passengers had the highest survival (~62%), 3rd-class the lowest (~25%).
🔹Family Type: Passengers with small families had better survival rates than those traveling alone or in big families.
🔹Embarkation Point: Passengers from Cherbourg (C) had the best survival rates.
🔹Age Group: Children were more likely to survive than adults.
  - Multivariate Analysis
🔹Sex, Class, and Survival:
   Female 1st-class passengers had the highest survival rate.
Male 3rd-class passengers had the lowest survival rate.

🔹Fare and Class:
Higher fares were associated with better survival chances.

### 🧰 Tools & Technologies
Python 🐍 | Pandas |Seaborn| Matplotlib| Jupyter Notebook

👨‍💻 Author

Rohit Raj
Data Analyst Enthusiast | SQL | Python | Pandas | Visualization
📫 Connect with me on LinkedIn
🔗 Explore more projects on GitHub
