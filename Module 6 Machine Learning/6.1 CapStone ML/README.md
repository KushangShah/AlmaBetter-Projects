<!-- institute name and logo -->
<div align='left' style="margin-bottom: 40px;"><a href="https://www.almabetter.com/"><img height="30px" src="images/almabetter_logo.jpeg" alt="AlmaBetter Logo"></a><br>AlmaBetter
</div>

<!-- Indigo Image Logo -->
<div align="center">
    <img src="images/Indigo_Logo.jpg" alt="" width="400" height="235" style="border-radius: 40px;">
</div>
<br>

<!-- project and ML title -->
<h1 align='center' style="margin-bottom: 0px;"><a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&weight=500&size=25&duration=5500&pause=1000&color=00FFFF&center=true&random=false&width=600&lines=IndiGO+Airline+Passenger+Referral+Prediction" alt="Typing SVG" />
</a></h1>

<!-- ML name -->
<h4 align='center' style="margin-top: 0; margin-bottom: 10px;"><a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Playfair+Display&weight=100&size=15&duration=5500&pause=1000&color=0FFFFF&center=true&random=false&width=600&lines=Machine+Learning+Project" alt="Typing SVG" />
</a></h4>



---

<!-- Table of content -->
## Table of Contant

* <p style="font-size:14px;">About this Project.</p>
* <p style="font-size:14px;">Key Concepts.</p>
* <p style="font-size:14px;">Project steps.</p>
* <p style="font-size:14px;">What Data set cointains?</p>
* <p style="font-size:14px;">Main library to be used.</p>
* <p style="font-size:14px;">Insights from Dataset.</p>
* <p style="font-size:14px;">Conclusion.</p>
* <p style="font-size:14px;">Acknowledgment.</p>

<br>

---

<!-- About this Project -->
<br><br>
## About this Project:
<p style="font-size:15px;">
    I am very excited to work on this machine learning project in aviation industry. Airline industry is really interesting. Company like IndiGo not only give flights, but also try to give good travel experience and make strong relation with customer.<br>
    In this project, I try to understand why passenger refer or recommend the airline. I have customer review data from 2006 to 2019. This data help to know what people think about things like comfort, service, and how they feel overall.<br>
    With help of data science and machine learning, we will find some patterns and get useful information. This can help airline to make customer experience better and take smart business decisions. So, if you like data, or aviation, or just want to know more — let’s go and learn how to predict what make people say, "Yes, I recommend this airline!"
    <br><br>
</p>

---
<br><br>
## Key Concepts:

- **Machine Learning Approach:**
  - Supervised Learning (Classification).
  - Predictive modeling using passenger review data.

- **Data Insights:**
  - Feature engineering based on travel experience factors.
  - Data visualization to explore customer behavior and satisfaction.

- **Model Evaluation:**
  - Use of evaluation metrics like accuracy, precision, recall, and F1-score.
  - Comparison of multiple classification models to find the best performer.

## Project Steps:

1. **Data Preparation:**
   - Collected and cleaned passenger review data.
   - Handled missing values and prepared features for modeling.

2. **Exploratory Data Analysis (EDA):**
   - Visualized customer review patterns and key travel factors.
   - Identified trends related to referrals.

3. **Model Development:**
   - Built classification models to predict if a passenger will recommend the airline.
   - Tuned model hyperparameters for better performance.

4. **Evaluation and Deployment:**
   - Tested models on new data to check accuracy.
   - Shared insights to help improve customer satisfaction and referral rates.
<br><br>
---
<br><br>
<!-- What Data set Containes -->
<!-- columns and their descriptions -->
<details open>
    <summary style="font-size: 20px; text-align: center;">
    What Data Set Contains?
</summary>
<br>
<p style="font-size:16px; test-align: left;">
1. airline: Name of the airline company.<br><br>
2. overall: Total score given to the trip (between 1 and 10).<br><br>
3. author: Name of the person who gave the review.<br><br>
4. review_date: Date when the review was written.<br><br>
5. customer_review: Text of the review about the flight.<br><br>
6. aircraft: Type or model of airplane used.<br><br>
7. traveller_type: Type of traveler (like business trip or leisure trip).<br><br>
8. cabin: Which class — like Economy, Business, or First.<br><br>
9. route: The flight route (from where to where).<br><br>
10. date_flown: Date of the actual flight.<br><br>
11. seat_comfort: How comfortable the seat was (rated 1 to 5).<br><br>
12. cabin_service: Service in the cabin (rated 1 to 5).<br><br>
13. food_bev: Food and drink quality (rated 1 to 5).<br><br>
14. entertainment: In-flight entertainment rating (1 to 5).<br><br>
15. ground_service: Service on the ground (check-in, boarding etc.) (rated 1 to 5).<br><br>
16. value_for_money: Is the flight worth the price? (rated 1 to 5).<br><br>
17. recommended: Did the person recommend the airline? (yes or no) — This is the target column.<br><br>
</p>
</details>
<br><br>

---
<br><br>
<!-- Library used in projects and their description -->
<details open> <summary style="font-size: 20px; text-align:center;"> Main Libraries Used </summary> <br> <p style="font-size:16px;">
🔢 NumPy – For efficient numerical operations and array handling.<br>
📊 Pandas – To load, clean, and manipulate structured datasets.<br>
📈 Matplotlib & Seaborn – For visualizing trends, distributions, and feature relationships with the target variable.<br>
🧪 SciPy – Useful for performing statistical tests (e.g., chi-squared test for feature relationships).<br>
🧠 scikit-learn (sklearn) – Core machine learning library for:

<ul> <li>Data preprocessing (LabelEncoder, StandardScaler, MinMaxScaler)</li> <li>Model training (Logistic Regression, Decision Tree, Random Forest, etc.)</li> <li>Model evaluation (accuracy, precision, recall, F1-score, ROC-AUC, etc.)</li> <li>Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)</li> </ul>
⏱️ Time – To track the runtime of model training and evaluation.<br>
🚫 Warnings – Suppresses warning messages to keep the output clean during development.<br>

</p> </details>
<br><br>

---
<br><br>
<details open>
<summary style="font-size: 20px; text-align:center;"> Insights... </summary>
<p align="center">
    <img src="images/MostAircraftUsed.png" alt="Insights Visualization 1" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/LargestFlightConducted.png" alt="Insights Visualization 2" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/NumofReviewsOverTime.png" alt="Insights Visualization 3" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/TravellerTypeByCabinClass.png" alt="Insights Visualization 3" width="400" style="border-radius: 20px; margin: 10px;">
    <img src="images/TravellerTypeRatingVsCabin.png" alt="Insights Visualization 3" width="400" height="160" style="border-radius: 20px; margin: 10px;">
    <img src="images/rf_model.png" alt="Insights Visualization 3" width="400" style="border-radius: 20px; margin: 10px;">
</p>

---
<br><br>
## Conclusion:
<p style="font-size:16px;">
In this project, we systematically cleaned and prepared the data, ensuring quality for analysis. Key features were selected to focus on the most relevant information, improving model performance. Multiple machine learning models were tested, including Logistic Regression, Decision Tree, and Random Forest. Cross-validation and hyperparameter tuning helped optimize results and prevent overfitting. The Random Forest model outperformed others, achieving an impressive 94.27% accuracy and 93.80% F1-score. The Decision Tree model, however, showed signs of overfitting. Overall, the best models demonstrated balanced and consistent metrics. These insights can help airlines enhance customer experience and increase referral rates.
</p>
<br><br>

---
<br><br>
### Acknowledgments:
<p style="font-size: 11px;">
This project is dedicated to leveraging machine learning to improve customer experience in the aviation industry. Special thanks to AlmaBetter for providing the learning platform, guidance, and resources that made this project possible. Gratitude is also extended to the open-source community for the powerful tools and libraries that supported this work.
</p>
<p align="right" > Created with 🧠 by <a href="https://github.com/KushangShah">Kushang Shah</a></p>
<p align="right"> <img src="https://komarev.com/ghpvc/?username=kushang&label=Profile%20views&color=0e75b6&style=flat" alt="kushang" /> </p>