# 📄✏ Credit Card Fraud Project
**Brief:** The **Credit Card Fraud Project** is a comprehensive endeavor aimed at developing systems and strategies to detect and prevent fraudulent activities related to credit card usage. It involves utilizing advanced technologies such as data analytics, machine learning, and artificial intelligence to analyze transactional data, identify suspicious patterns, and flag potentially fraudulent transactions. The project's goal is to safeguard consumers' financial information, minimize financial losses for individuals and businesses, and maintain the integrity of the global financial system.

## Data Dictionary:

* LIMIT_BAL: This feature represents the credit limit assigned to the individual's credit card. It indicates the maximum amount of credit the person can utilize.

* SEX: This feature represents the gender of the credit card holder. While gender itself may not directly impact credit card fault detection, it can be considered as a demographic factor that might have some influence on creditworthiness.

* EDUCATION: This feature indicates the educational background of the credit card holder. It can provide insights into the person's level of education, which might indirectly correlate with their financial stability and ability to manage credit.

* MARRIAGE: This feature represents the marital status of the credit card holder. Similar to gender, marital status can be a demographic factor that could potentially impact credit card fault detection.

* AGE: This feature denotes the age of the credit card holder. Age can be an important factor in assessing creditworthiness as it often correlates with financial responsibility and stability.

* PAY_0, PAY_2, PAY_3, PAY_4, PAY_5, PAY_6: These features represent the repayment status of the credit card for the past six months. The values indicate the payment status (e.g., -1 represents payment delay for one month, 0 represents payment on time, 1 represents payment delay for two months, and so on). These features are crucial in determining the payment behavior of the individual over time.

* BILL_AMT1, BILL_AMT2, BILL_AMT3, BILL_AMT4, BILL_AMT5, BILL_AMT6: These features represent the amount of bill statement for the respective months. They provide information about the outstanding balance on the credit card at specific points in time.

* PAY_AMT1, PAY_AMT2, PAY_AMT3, PAY_AMT4, PAY_AMT5, PAY_AMT6: These features represent the amount of payment made by the credit card holder for the respective months. They indicate the actual payments made to reduce the outstanding balance.

* default payment next month: This is the target variable or the dependent variable that indicates whether the credit card holder defaulted on their payment in the following month (1 for default, 0 for no default). This is the variable that the credit card fault detection model aims to predict.

* Dataset is taken from Kaggle and stored in MongoDB



## 💿 Installing
* Environment setup.
```
conda create --prefix venv python==3.8 -y
```
```
conda activate venv/
````
* Install Requirements and setup
```
pip install -r requirements.txt
```
* Run Application
```
python app.py
```

🔧 Built with
- flask
- Python 3.8
- Machine learning
- Scikit learn


## Setup :

- Clone the repository:
```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```
- Create a virtual environment (optional but recommended):
```bash
python -m venv venv
```
- Activate the virtual environment:
  - On Windows:
   ```bash
   venv\Scripts\activate
   ```
  - On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```

## Usage :

- Open the Jupyter Notebook:
```bash
jupyter notebook
```
- Navigate to the Diamond_Price_Prediction.ipynb notebook and open it.
- Follow the instructions in the notebook to run the code cells.

## Models :
- GaussianNB(Gaussian Naive Bayes) with an accuracy of 0.7792929292929293
- XGBClassifier(XgBoost Classifier) with an accuracy of 0.8203030303030303

## Contributing :
If you'd like to contribute to this project, please follow the standard GitHub fork and pull request process. Contributions, issues, and feature requests are welcome!

## License :
This project is licensed under the <a href="https://github.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/blob/main/LICENSE">MIT License</a> - see the LICENSE file for details.
