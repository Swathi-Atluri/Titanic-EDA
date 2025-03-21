# **Titanic Dataset Analysis – Exploratory Data Analysis (EDA)**  

## **Overview**  
This project explores survival patterns in the Titanic disaster using EDA. The analysis identifies key factors influencing survival, such as socio-economic status, gender, age, and fare.  

## **Key Findings**  

### 1. Survival Rate  
- Approximately **38-40%** of passengers survived, while **60-62%** perished.  

### 2. Passenger Class Impact  
- **First Class**: ~60-63% survival rate.  
- **Second Class**: ~47-50% survival rate.  
- **Third Class**: ~24-25% survival rate.  
- Higher-class passengers had better survival odds due to proximity to lifeboats and priority in evacuation.  

### 3. Gender Influence  
- **Females**: ~74-75% survival rate.  
- **Males**: ~18-19% survival rate.  
- Women were prioritized during evacuation, aligning with historical records.  

### 4. Age and Survival  
- **Children (<15 years)** had higher survival rates.  
- **Elderly (>60 years)** had lower chances of survival.  
- Majority of passengers were aged **20-40 years**.  

### 5. Fare and Socio-Economic Influence  
- Higher fares correlated with better survival rates.  
- First-class passengers paid more and had greater access to lifeboats.  

### 6. Embarkation Effects  
- **Cherbourg (C)**: Highest survival (~55%), likely due to more first-class passengers.  
- **Southampton (S)**: ~33-35% survival.  
- **Queenstown (Q)**: ~38-39% survival.  

### 7. Family Size and Survival  
- Small families (2-4 members) had the highest survival rates.  
- Large families (5+ members) struggled to evacuate, reducing survival chances.  
- Solo travelers had lower survival odds.  

## **Correlations & Insights**  
- **Pclass vs. Survival**: Lower-class passengers had lower survival rates (-0.34 correlation).  
- **Fare vs. Survival**: Higher fares correlated with survival (0.26 correlation).  
- **Gender & Age Priority**: Women and children were prioritized, while older passengers faced more risk.  

## **Conclusion**  
Survival on the Titanic was highly influenced by **socio-economic status, gender, and age**.  
- **First-class passengers, women, and children had the best survival odds.**  
- These insights serve as a foundation for predictive modeling, where **Pclass, Sex, Age, and Fare** are strong survival predictors.  

---
