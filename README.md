[![GitHub license](https://img.shields.io/github/license/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg)](https://github.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg)](https://GitHub.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg)](https://GitHub.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg)](https://GitHub.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


[![GitHub watchers](https://img.shields.io/github/watchers/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg?style=social&label=Watch&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg?style=social&label=Fork&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/network/)
[![GitHub stars](https://img.shields.io/github/stars/SINGHxTUSHAR/Credit-Card-Fraud-Detection.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/stargazers/)

[![Open in Visual Studio Code](https://img.shields.io/static/v1?logo=visualstudiocode&label=&message=Open%20in%20Visual%20Studio%20Code&labelColor=2c2c32&color=007acc&logoColor=007acc)](https://open.vscode.dev/SINGHxTUSHAR/Credit-Card-Fraud-Detection)

![IMG_85 (3)](https://github.com/SINGHxTUSHAR/Credit-Card-Fraud-Detection/assets/113624520/2d609a9a-6443-4657-9860-894b02aea99e)


# Credit Card Fraud Project &#x1F4B3;

**Brief:** The **Credit Card Fraud Project** is a comprehensive endeavor aimed at developing systems and strategies to detect and prevent fraudulent activities related to credit card usage. It involves utilizing advanced technologies such as data analytics, machine learning, and artificial intelligence to analyze transactional data, identify suspicious patterns, and flag potentially fraudulent transactions. The project's goal is to safeguard consumers' financial information, minimize financial losses for individuals and businesses, and maintain the integrity of the global financial system.

## Data Dictionary 📄✏ :

* LIMIT_BAL: This feature represents the credit limit assigned to the individual's credit card. It indicates the maximum amount of credit the person can utilize.

* SEX: This feature represents the gender of the credit card holder. While gender itself may not directly impact credit card fault detection, it can be considered as a demographic factor that might have some influence on creditworthiness.

* EDUCATION: This feature indicates the educational background of the credit card holder. It can provide insights into the person's level of education, which might indirectly correlate with their financial stability and ability to manage credit.

* MARRIAGE: This feature represents the marital status of the credit card holder. Similar to gender, marital status can be a demographic factor that could potentially impact credit card fault detection.

* AGE: This feature denotes the age of the credit card holder. Age can be an important factor in assessing creditworthiness as it often correlates with financial responsibility and stability.

* PAY_0, PAY_1, PAY_2, PAY_3, PAY_4, PAY_5, PAY_6: These features represent the repayment status of the credit card for the past six months. The values indicate the payment status (e.g., -1 represents payment delay for one month, 0 represents payment on time, 1 represents payment delay for two months, and so on). These features are crucial in determining the payment behavior of the individual over time.

* BILL_AMT1, BILL_AMT2, BILL_AMT3, BILL_AMT4, BILL_AMT5, BILL_AMT6: These features represent the amount of bill statement for the respective months. They provide information about the outstanding balance on the credit card at specific points in time.

* PAY_AMT1, PAY_AMT2, PAY_AMT3, PAY_AMT4, PAY_AMT5, PAY_AMT6: These features represent the amount of payment made by the credit card holder for the respective months. They indicate the actual payments made to reduce the outstanding balance.

* default payment next month: This is the target variable or the dependent variable that indicates whether the credit card holder defaulted on their payment in the following month (1 for default, 0 for no default). This is the variable that the credit card fault detection model aims to predict.

* Dataset is taken from Kaggle and stored in MongoDB



## Installing 💿 :
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
