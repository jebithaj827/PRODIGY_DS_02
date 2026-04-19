# Titanic Data Analysis Project - Task 2 

### **Data Cleaning Summary**
* **Merging:** I compared two separate files and added the "Survived" column into the main dataset to identify who lived and who died.
* **Dropping:** I deleted the Cabin Number column because it was missing most of its data and was useless for the analysis.
* **Imputing (Missing Values):** I used the Median value method to fill in the gaps. I added the median in every place the Age and Fare of a person was missing so every passenger had a complete record.
* **Verification:** I performed a final check to ensure all other data was entered correctly and verified that there were no duplicate rows.

---

### **Exploratory Data Analysis (EDA) Summary**
* **Univariate Analysis:** I created histograms for Age and Fare to see how data was spread. I found a major spike in the 20-30 age range (due to my median filling) and saw that most passengers paid a low Fare, with only a few high-paying outliers.
* **Categorical Analysis:** I used a Pie Chart for Passenger Class, which showed that the majority of the ship (over 50%) was made up of 3rd Class passengers.
* **Bivariate (Gender):** I compared Sex vs. Survived using a bar chart. This confirmed a clear pattern: 100% of females survived and 0% of males survived in this dataset.
* **Bivariate (Class):** I analyzed Pclass vs. Survived. My table shows that 3rd Class had the highest survival percentage compared to 1st and 2nd.
* **Bivariate (Age Groups):** I grouped ages into 10-year intervals to see survival trends. This helped identify which age brackets were most likely to survive.

---

### **Patterns and Trends Identified**
* **Gender:** Being female was the strongest predictor of survival.
* **Class:** Survival was closely linked to a passenger's socio-economic class.
* **Age:** Certain age groups were prioritized, which became clear after grouping the data.
