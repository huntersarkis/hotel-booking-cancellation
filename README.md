
# Hotel Booking Cancellation Analysis

## Project Overview

Hotel cancellations create operational challenges and revenue uncertainty for hotels. When reservations are canceled at the last minute, rooms may remain unsold, reducing revenue and making staffing and inventory planning more difficult.

The purpose of this project is to analyze booking data to identify patterns associated with cancellations and build a predictive model that estimates the likelihood that a reservation will be canceled. The insights from this analysis can help hotels better manage reservations, adjust deposit policies, and reduce financial losses caused by cancellations.

---

## Tools & Technologies

* Python
* Pandas
* Scikit-learn
* Tableau
* Excel
* Jupyter Notebook

---

## Dataset

The dataset contains hotel booking records including reservation details, customer behavior, and cancellation outcomes.

Key features analyzed:

* **lead_time** – Number of days between booking and arrival
* **deposit_type** – Type of deposit required for the booking
* **previous_cancellations** – Number of cancellations by the guest in the past
* **total_of_special_requests** – Number of special requests made by the guest
* **is_canceled** – Whether the reservation was canceled (target variable)

---

## Exploratory Data Analysis

Exploratory analysis was performed using **Tableau and Excel** to understand the distribution of features and their relationship with booking cancellations.

### Visualizations Included

* Lead Time Distribution
* Lead Time vs Cancellation Rate
* Deposit Type vs Cancellation Rate
* Special Requests vs Cancellation Rate
* Previous Cancellations vs Cancellation Rate

### Dashboard Preview

---

## Statistical Analysis

Univariate statistics and hypothesis testing were conducted in Excel to evaluate the relationships between selected features and the cancellation label.

Statistical tests included:

* Summary statistics for each feature
* Correlation analysis for numeric features
* Chi-square test for categorical features

---

## Machine Learning Model

A predictive model was built using  **Random Forest classification** .

### Models Compared

* Logistic Regression
* Decision Tree
* Random Forest

Cross-validation was used to compare models using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

Random Forest performed best and was further optimized using  **GridSearchCV** .

---

## Feature Importance

Feature importance analysis showed that the most influential predictors were:

1. **Non-refundable deposit type**
2. **Lead time**
3. **Previous cancellations**
4. **Total special requests**

These variables provided the most predictive power for estimating cancellation risk.

---

## Business Insights

Key findings from the analysis include:

* Reservations with **non-refundable deposits are far less likely to be canceled**
* **Long lead times increase cancellation risk**
* Guests with **previous cancellations are more likely to cancel again**
* Guests who make **more special requests tend to be more committed to their reservation**

---

## Business Recommendations

Based on the analysis, hotels could reduce cancellations by:

1. Encourage **non-refundable deposits for early bookings**
2. Monitor reservations with **long lead times**
3. Track **guests with repeated cancellations**
4. Use predictive models to **anticipate cancellations and improve revenue planning**

---

## Repository Structure

hotel-booking-cancellation

│

├── data

│

├── excel

│   ├── hotel_univariate_statistics.xlsx

│   └── hotel_bivariate_statistics.xlsx

│

├── images

│   └── dashboard_preview.png

│

├── notebooks

│   └── hotel_cancellation.ipynb

│

├── tableau

│   └── hotel_dashboard.twbx

│

├── requirements.txt

│

└── README.md

---

## Author

Hunter Sarkis

Grand Canyon University

Data Analytics / Analytics Engineering
