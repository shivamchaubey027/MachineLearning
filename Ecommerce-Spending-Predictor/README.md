# **How much will the user spend?**  
## Should the company invest more in upgrading the mobile UI or the web experience?  

## **Project Overview**  
This project builds a **linear regression model** to predict how much a customer is likely to spend based on different user behaviors. The dataset includes features like time spent on the website, time spent on the mobile app, and other customer attributes.  

## **Dataset**  
The dataset contains customer details such as:  
- **Time on Website**: Minutes spent on the company’s website  
- **Time on App**: Minutes spent using the mobile app  
- **Length of Membership**: How long the customer has been a member  
- **Yearly Amount Spent**: Target variable (amount spent by the customer)  

## **Approach**  
1. **Exploratory Data Analysis (EDA)**: Visualizing relationships between variables  
2. **Feature Selection**: Identifying important predictors  
3. **Building the Model**: Training a linear regression model  
4. **Evaluation**: Checking accuracy using metrics like R² score and Mean Squared Error  

## **Results**  
- The model gives insights into whether **website engagement** or **mobile usage** has a stronger correlation with customer spending.  
- Businesses can use this to decide where to focus their improvements—whether to optimize the **app experience** or **enhance the website** for better conversions.  

## **Files in this Repository**  
- `Ecommerce_Model.ipynb` → Jupyter Notebook containing the full analysis and model  
- `dataset.csv` → Dataset used for training  
- `README.md` → Project description  

## **How to Run**  
1. Clone the repository  
   ```bash
   git clone 
   cd 
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook  

## **Future Improvements**  
- May Try **Polynomial Regression** or **Decision Trees** for better predictions  
- Add **real-time prediction API** for business use  
- Include **more customer behavior features** to improve accuracy  
