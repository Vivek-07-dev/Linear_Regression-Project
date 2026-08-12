# Linear_Regression-Project
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)

## Description
This project uses 'Ecommerce customers' Data (Made-up data) of imaginary company that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.  
We used a linear regression model to predict the 'Yearly Amount Spent' by the customers based on number of features. And on the basis of regression coefficients of the model, decide whether 'mobile app' or 'Website' results in greater 'Yearly Amount Spent' by the customers.

## 📋 Summary
* **Objective:** To help a company (imaginary) decide whether they should focus their efforts on their mobile app experience or their website.
* **Dataset:** Used a Made-up data containing attributes like 'Email', 'Address', 'Avatar' and numerical columns like 'Avg. Session Length', 'Time on App', 'Time on Website', 'Length of Membership'.
* **Key Finding:**
  1. Length of Membership is the strongest predictor of yearly spending, followed by Time on App.  
  2. Time on Mobile App is also a good indicator of increase in yearly spend by customer.
  3. In-store sessions/meetings with a personal stylist has also some significant positive relationship with cusomer's spending.
  4. Time on Website is barely increasing customer's yearly spending. 

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
* **Exploratory Data Analysis:** Used Seaborn (`jointplot`, `pairplot`, `lmplot`) to analyze correlations between numerical features and the target variable (`Yearly Amount Spent`).
* **Data Splitting:** Separated data into features ($X$) and target ($Y$), followed by a (`train_test_split`).
* **Model Evaluation:** Evaluated predictions using Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and $R^2$ score.
* **Residual Analysis:** Plotted residual histograms to ensure a normal distribution of errors.

## 📈 Coefficient Analysis
Holding all other features fixed, a 1-unit increase in:  
Avg. Session Length $\rightarrow$ +$25.98 spent  
Time on App $\rightarrow$ +$38.59 spent  
Time on Website $\rightarrow$ +$0.19 spent  
Length of Membership $\rightarrow$ +$61.27 spent  

## Conclusion: 
Company should focus more on their mobile app, as Time on Website is barely increasing customer's yearly spending.


## 👥 Author
* **Vivek Pal** - [GitHub Profile](https://github.com/Vivek-07-dev/) / [LinkedIn](https://www.linkedin.com/in/vivek-pal-498145314)

