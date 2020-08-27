# Chronic Kidney Disease -- Factor Analysis

Chronic kidney disease has become a serious public health issue around the world. The overall prevelance of CKD in the general population is approximately 14% and is still increasing. The high growth of CKD can result
in considerable healthcare cost and impose restrictions on many patients' daily livings. One way to reduce the economic burden of CKD would be <b>early intervention</b>, with <b>early diagnosis and treatment</b>, it
is possible to slow the progression of CKD.

Therefore, <b>our target</b> is to help healthcare organization to identify the individuals with high risk of CKD. In order to achieve it, <b>our approach</b> is to collect public data and use them to build the final predictive model. 
Considering the survey costs and survey quality, we want to keep our survey process simple but effective, that is, to ask public only several determined questions. According to previous research, CKD can be cuased by 
different risk factors such as race, gender, age, and family history. Moreover, smoking, obesity, hypertension, and diabetes mellitus can also lead to CKD. So <b>our challenge</b> is how to identify the most important risk
factor among all possible information. 


<b> This notebook covers:</b><br>
1. Data Cleaning<br>
2. Data Exploration<br>
3. Feature Selection<br>
* Bayes Theory
* Random Forest
4. Data Modeling and Evaluation<br>


<b>Conclusions:</b>

From our analysis, "Age" is a highly important factor, indicating that elderly people are more prone to develop CKD. Beside, factors such as "Hypertension", "Diabetes", "Anemia", "Stroke" are also likely to lead to kidney disease. Other factors like "Smoker", "Weight" and some other healthy issues such as "CHF (Congestive Heart Failure)", "CVD (cardiovascular disease)" could also constitute risks.

In order to make our survey easy for interviewees to conduct, we decided to chose 6 strongest risk factors as our survey questions. In this way, our final predictive model can be more simple and interpretable.


<b>Recommendations:</b>

Finally, we hope people can pay more attention to their health as well as their families. Chronic kidney disease may not become apparent until your kidney function is significantly impaired. Thus, taking regular screenings for CKD is necessary if you are at high risk (check our analysis), especially for elderly people, and controlling conditions like diabetes (check our analysis) can also help.
