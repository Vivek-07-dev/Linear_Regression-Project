# Linear_Regression-Project
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)

## Description
This project uses 'Ecommerce customers' Data (Made-up data) of imaginary company that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.  
We used a linear regression model to predict the 'Yearly Amount Spent' by the customers based on number of features. And on the basis of regression coefficients of the model, decide whether 'mobile app' or 'Website' results in greater 'Yearly Amount Spent' by the customers.

## 📋 Summary
* **Objective:** To help a company (imaginary) decide whether they should focus their efforts on their mobile app experience or their website.
* **Dataset:** Used a Made-up data containing attributes like 'Email', 'Address', 'Avatar' and numerical columns like 'Avg. Session Length', 'Time on App', 'Time on Website', 'Length of Membership'.
* **Key Finding:** Emergency calls sharply increase during standard daytime hours (15:00 – 17:00) and heavily taper off on weekends(Sat/Sun) compared to weekdays.

## 🛠️ Tech Stack
* **Language:** Python 3.12
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 🗂️ Dataset Features
The raw dataset includes the following core fields:
* `Email`: Email of customer
* `Address`: Physical Address of Customer
* `Avatar`: Designated color Avatar
* `Avg. Session Length`: Average session of in-store style advice sessions.
* `Time on App`: Average time spent on App in minutes
* `Time on Website`: Average time spent on Website in minutes
* `Length of Membership`: How many years the customer has been a member. 

## 🚀 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Vivek-07-dev/Linear_Regression-Project.git
   ```

2. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. **Open the notebook:**
   Launch Jupyter Notebook and run `ecommerce_regression.ipynb`.

## 📊 Project Steps & Methodology
* **Feature Engineering:** Splitting the `title` column to create a new `Reason` categorical column (EMS, Fire, Traffic).
* **Time Series Extraction:** Extracting `Hour`, `Month`, and `Day of Week` from the `timeStamp` string column.
* **Exploratory Data Analysis:** Grouping, aggregation, and querying to find the top townships and zip codes for emergency dispatches.
* **Advanced Visualizations:** Utilizing Seaborn `countplot`, `lmplot`, `heatmap`, and `clustermap` to map call frequencies over hours and days.

## 📈 Key Insights & Visualizations
* **Top Reason for Calls:** **EMS (Emergency Medical Services)** consistently stands out as the most common overall reason for emergency dispatches, followed closely by Traffic accidents.
