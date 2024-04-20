# VOYAGE OF FATE: UNRAVELING THE TITANIC TRAGEDY

# INTRODUCTION
The Titanic's tragic voyage continues to captivate people worldwide, spawning numerous literary works, movies, and cultural references that delve into the human stories and lessons gleaned from this historic maritime disaster. 
The RMS Titanic, a marvel of its time, was a British passenger liner operated by the White Star Line. Constructed in Belfast, Northern Ireland, it set out on its maiden voyage from Southampton, England, on April 10, 1912, destined for New York City. Tragically, just four days into its journey, the Titanic struck an iceberg in the North Atlantic, leading to its catastrophic sinking and the loss of lives. This disaster spurred significant advancements in maritime safety regulations and remains a poignant symbol of human courage and vulnerability at sea.

![1000_F_157107915_LcIHyd3EuJD6WSIJkQ5iGpI8ywMYBLhM jpg TITANIC STOCK PHOTO](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/5e4c59a5-0cc0-4c72-a212-acf272dad6a4)

Documentation of the Titanic's passengers stems from a blend of official records, survivor testimonies, historical research, and archival sources, all contributing to our understanding of this monumental event and the individuals involved.
Determining the exact number of passengers with comprehensive, complete records of their presence aboard the Titanic can be challenging. However, factors such as class status, survivorship, and archival challenges play a role in the completeness of passenger records.


**Documentation was carried out through various means**:

1. **Passenger Lists**: Official passenger lists, meticulously curated by the White Star Line, detailed the names, ages, genders, and cabin classes of the passengers.

2. **Ticket Records**: The White Star Line maintained detailed ticket records, including ticket numbers, fares, and cabin allocations.

3. **Boarding Records**: Records were maintained of passengers boarding at different ports, such as Southampton, Cherbourg, and Queenstown (Cobh).

4. **Survivor Accounts**: Survivors of the Titanic disaster provided invaluable firsthand accounts of their experiences, including interactions with fellow passengers and their actions during the evacuation.

5. **Official Inquiries**: Following the disaster, comprehensive official inquiries and investigations, conducted by entities like the British and American governments, gathered testimonies from survivors and documented crucial information about passengers and crew.

 Over time, historical archives, museums, and organizations have meticulously collected and preserved documents, photographs, and artifacts related to the Titanic and its passengers, enriching our understanding of this historic event.



### Objective of this project

This report delves into the factors influencing survival rates among passengers, particularly focusing on the impact of passenger class. The dataset used for this analysis is sourced from Kaggle and has been meticulously cleaned and prepared for exploration.

### Dataset Overview
The  sampling dataset comprises 714 complete passenger records, encompassing information about passenger class, gender, and survival status. Seven charts were segmented by ship class and gender to provide a visual representation of survivor, non-survivor, and total onboard numbers. Preprocessing steps included removing blanks, handling outliers, and dataset remodeling to ensure data accuracy.


### Challenges faced

Addressing these challenges involved a combination of data preprocessing techniques, statistical analysis methods, and a lot of research and strategies to ensure the accuracy, validity, and relevance of the analysis outcomes. Avoiding interpretation bias and ensuring objective analysis of the data can be challenging, particularly when exploring sensitive topics such as socio-economic factors influencing survival rates.

1. **Missing Data**: Dealing with missing values in the dataset could be challenging, as it requires strategies such as imputation or removal of incomplete records while ensuring data integrity.

2. **Data Cleaning**: Cleaning the dataset involves handling outliers, and inconsistencies, and ensuring data accuracy, which can be time-consuming and requires careful attention to detail.

3. **Dataset Size**: With a dataset size of **714** records, there may be limitations in conducting detailed subgroup analyses or statistical tests, especially when stratifying by multiple variables simultaneously.

4. **Complex Relationships**: Understanding the complex relationships between passenger class, gender, age, and survival rates requires sophisticated analysis techniques and may pose challenges in drawing conclusive insights.

5. **Contextual Understanding**: Gaining a nuanced understanding of historical context and factors influencing survival beyond the dataset, such as crew actions, evacuation procedures, and passenger behaviors, adds complexity to the analysis.


### ANALYSIS: BASED ON THE SAMPLING DATASET  OF INDIVIDUALS WITH COMPLETE RECORDS
1. **Gender Analysis**:
Male Passengers are **453 (63.4%)** of the passengers onboard based on the sampling dataset,  **28.8%** survived while **79.5%** did not survive. Female Passengers make up **261 (36.6%)** of the passengers out of which, **75.5%** survived, and **24.5%** did not survive. The survival rate among females is notably higher than among males, indicating a potential priority given to women during the evacuation.
2. **Class of Ship Cabin Analysis**:
There were **186 (26.1%)** of the total passengers in the _first-class cabins_, out of which **65.6%** survived, and **34.4%** did not.  Among the **173 (24.2%)** of the total passengers in _second class_, **47.9%**  survived, while **48.3%** did not. The _third-class cabins_ accommodated **355 (49.7%)** of the total passengers, with **23.9%** surviving and **76.0%** did not survive.
The overall survival rate among the passengers was approximately **40.6%**, and **59.4%** did not survive.


## VISUALIZATION:
-----------------

These findings highlight the relationship between passenger class, gender, and survival outcomes during the Titanic disaster, providing valuable insights into the factors that influenced passenger fate.

**Visualization 1: Total Number of Survivors and Non-Survivors to Classes**

![Desktop-screenshot png viz 1](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/f9e96ef3-e2a9-4d6e-b3a3-ea51de010e9e)


- Finding: There is a notable difference in survival rates across passenger classes, with First Class having the highest survival rate and Third Class the lowest.
This finding suggests that passengers in higher classes had better chances of survival, This could be due to factors such as socio-economic status,  proximity to lifeboats, and priority in evacuation procedures.

- Total survivors in First Class: **42%**
- Total survivors in Second Class: **28.1%**
- Total survivors in Third Class: **29.3%**
- Total non-survivors in First Class: **15.1%**
- Total non-survivors in Second Class: **21.2%**
- Total non-survivors in Third Class: **63.7%**

-----------------------------------------------------------------------------------------------------------------------------------------


**Visualization 2: Number of Non-Survivor Females to Classes**

![Desktop-screenshot png viz 2](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/01cc36a3-a8fa-44cd-8746-f547c0606668)

- Finding: The number of female non-survivors is highest in Third Class compared to other classes.
This finding may indicate challenges faced by female passengers in lower-class accommodations during the evacuation process.

- Number of female non-survivors in First Class:**4.7%**
- Number of female non-survivors in Second Class:**9.4%**
- Number of female non-survivors in Third Class: **85.9%**

-------------------------------------------------------------------------------------------------------------------------------------------


**Visualization 3: Female Survivor to Classes**

![Desktop-screenshot png viz 3](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/55c8c11e-31a8-47fe-86b7-9390b46acdf9)

- Finding: First Class has the highest number of female survivors, followed by Second Class and then Third Class. This finding aligns with the trend observed in Visualization 1, indicating that female passengers in higher classes had better chances of survival.

- Number of female survivors in First Class: **41.6%**
- Number of female survivors in Second Class: **34.5%**
- Number of female survivors in Third Class: **23.9%**

----------------------------------------------------------------------------------------------------------------------------------------


 **Visualization 4: Number of Females Onboard by Class**

![Desktop-screenshot png viz 4](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/6e6fab74-6f00-4478-bede-ea4783dfffb1)

- Finding 4: Class 3 had the highest number of females onboard.
This finding reflects the demographics of passengers on the Titanic, where the Third Class had a larger number of passengers compared to other classes.
- Numerical Calculation: Calculate the count of females onboard by class.

- Number of females onboard in First Class: **32.7%**
- Number of females onboard in Second Class: **28.4%**
- Number of females onboard in Third Class: **39.1%**

-------------------------------------------------------------------------------------------------------------------------------------
  

**Visualization 5: Number of Male Non-Survivors to Classes**

![Desktop-screenshot png viz 5](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/216e56f4-5d4e-4479-a83a-572ba3b877bb)

- Finding: Third Class had the highest number of male non-survivors, highlighting challenges faced by lower-class passengers during the disaster.
  Similar to the trend observed with female non-survivors, male passengers in lower classes faced challenges during the disaster. The reason might be Limited access to lifeboats and evacuation challenges may have contributed to this disparity.

- Number of male non-survivors in First Class: **16.9%**
- Number of male non-survivors in Second Class: **23.3%**
- Number of male non-survivors in Third Class: **59.7%**

-----------------------------------------------------------------------------------------------------------------------------------


**Visualization 6: Male Survivor to Classes**


![Desktop-screenshot png viz 6](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/aab5d9f5-d70a-48a1-9f08-cb9914f3d1e5)

- Finding: First Class had the highest number of male survivors, followed by Second Class and then Third Class.
  Consistent with the trend seen in female survivors, male passengers in higher classes had better survival rates.

- Number of male survivors in First Class: **43.0%**
- Number of male survivors in Second Class: **16.1%**
- Number of male survivors in Third Class: **40.8%**



---------------------------------------------------------------------------------------------

**Visualization 7: Number of Males Onboard According to Classes**


- Finding: The distribution of males onboard shows a higher representation in Third Class, consistent with overall passenger demographics.
  This reflects the larger number of lower-class passengers, including males, onboard the Titanic. And similar to the finding for females, Class 3 had a larger proportion of male passengers compared to other classes.

- Number of males onboard in First Class: **22.3%**
- Number of males onboard in Second Class: **21.9%**
- Number of males onboard in Third Class: **55.8%**

These findings provide insights into the differential impact of passenger class and gender on survival rates during the Titanic disaster, highlighting socio-economic factors and evacuation dynamics as key determinants of survival outcomes.


### Conclusion

In conclusion, this analysis underscores the critical role of the passenger class in determining survival outcomes during the Titanic disaster. By leveraging data-driven insights to gain a deeper understanding of historical events and their implications for safety measures. This report serves as a testament to the power of data analysis to unravel complex narratives and shape informed decisions.

**1) The Critical Role of Passenger Class:**
Our analysis reveals a stark correlation between passenger class and survival rates. Passengers in higher classes, with likely access to better amenities and evacuation procedures, had significantly higher chances of survival. This emphasizes the importance of equitable safety measures across all passenger categories to enhance overall survival rates in maritime disasters.


**2) Possibility of Ship Overloading:**
While not directly analyzed in this report, historical records suggest that the Titanic may have been operating at or near its maximum capacity because there was a probability that the life jacket and lifeboat were not enough, raising concerns about the impact of overloading on evacuation efforts and survival rates. Further studies could delve into this aspect to understand its potential impact on the disaster.

**3) Ticket Racketeering Concerns:**
The possibility of ticket racketeering, although not proven in this analysis, remains a historical concern associated with the Titanic disaster. Fraudulent practices related to ticket distribution could have compromised passenger safety and contributed to the chaotic evacuation process.

**4) Lack of Regard for Safety Measures:**
The Titanic disaster exposed gaps in safety protocols and emergency response procedures, leading to avoidable loss of life. This analysis underscores the importance of prioritizing safety measures, including adequate lifeboat capacity, crew training, navigation vigilance, and passenger education, to mitigate risks in future maritime endeavors.

### Recommendations and Insights

1. **Enhanced Safety Protocols for Lower-Class Passengers:**
   - Given the observed disparity in survival rates across passenger classes, it would have been crucial to prioritize safety protocols for lower-class passengers. This includes ensuring equitable access to lifeboats, conducting regular safety drills, and providing clear evacuation instructions to mitigate risks during emergencies.

2. **Conducting Further Research on Additional Survival Factors:**
   - While passenger class played a significant role in survival outcomes, further research is warranted to explore additional factors impacting survival. Factors such as age, family size, cabin location (proximity to evacuation points), and passenger demographics could provide valuable insights into survival factors and overall safety measures.

5. **Education and Awareness Campaigns:**
   - Education and awareness campaigns for passengers regarding emergency procedures would have been thoroughly carried out, and safety equipment locations, and evacuation routes  essential. Thus empowering passengers with knowledge and preparedness can improve response times and overall survival rates during the emergency.


### PLEASE NOTE:
**_Research indicates that the RMS Titanic had a total of 2,224 passengers and crew members aboard during its fateful maiden voyage in April 1912. This inclusive count encompasses passengers from all classes (First, Second, and Third) as well as the ship's crew.
Of these 2,224 individuals, approximately 710 survived the tragedy. Calculating the survival percentage reveals that about 31.9% of those onboard the Titanic managed to survive the disaster_**.




**Dashboard Preview:**

![dashboard new titanic](https://github.com/yemifatodu/THE-TITANIC-PROJECT-VOYAGE-OF-FATE/assets/147722919/fec0e5b7-2e51-4171-b521-750e46314f5f)

[VIEW DASHBOARD HERE](https://public.tableau.com/views/TitleVoyageofFateUnravelingtheTitanicTragedy/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

This PNG file offers a glimpse of the complete dashboard, showcasing essential visualizations and insights from this project.

In addition, you can access the dataset used for this analysis through the following link:

**Dataset Link:**
[Link to the Dataset](https://1drv.ms/x/c/0dd91a18f690ef3a/ETuXUrYvWa9AikD5lH1R-2wBXNprUUketl8YROmEs4ABWQ)

This link leads to the dataset utilized in the analysis, ensuring transparency and the ability to replicate the findings presented in the report.
