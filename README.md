🔐 Phishing Website Detection Using Machine Learning
With the growing dependence on the internet, cyber threats like phishing have also become more widespread. Attackers often trick users through fake websites or misleading links to collect confidential data such as login credentials or banking information.

While traditional detection methods exist, attackers are constantly improving their techniques. Machine Learning (ML) offers a powerful solution by recognizing patterns and anomalies in URLs, making it effective in identifying phishing websites.

🛠️ Setup Instructions
This project is built using Python 3.6.10.
If you haven't installed Python, download it from the official site.
Once you clone the repository, install the required libraries using:

pip install -r requirements.txt


📁 Project Structure

         ├── pickle
│   └── model.pkl
├── static
│   └── styles.css
├── templates
│   └── index.html
├── Phishing URL Detection.ipynb
├── Procfile
├── README.md
├── app.py
├── feature.py
├── phishing.csv
├── requirements.txt


💻 Tools & Technologies


Python 3.6

Flask Web Framework

Scikit-learn, XGBoost, CatBoost

Pandas, NumPy

Matplotlib, Seaborn

HTML5/CSS3 (Frontend)

📈 Model Performance
Model	Accuracy	F1 Score	Recall	Precision
Gradient Boosting	97.4%	0.977	0.994	0.986
CatBoost	97.2%	0.975	0.994	0.989
XGBoost	96.9%	0.973	0.993	0.984
MLP (Neural Net)	96.9%	0.973	0.995	0.981
Random Forest	96.7%	0.971	0.993	0.990
SVM	96.4%	0.968	0.980	0.965
Decision Tree	96.0%	0.964	0.991	0.993
K-Nearest Neighbors	95.6%	0.961	0.991	0.989
Logistic Regression	93.4%	0.941	0.943	0.927
Naive Bayes	60.5%	0.454	0.292	0.997

🧠 Key Insights
Certain features such as HTTPS, Anchor URLs, and Website Traffic play a crucial role in phishing detection.

Among all tested models, Gradient Boosting Classifier showed the highest accuracy, making it the most reliable for this task.

Hyperparameter tuning and feature selection significantly enhance model performance.

📌 Summary
This project focuses on building and comparing multiple machine learning algorithms to detect phishing URLs. Through analysis and model training, we discovered which features and models perform best in distinguishing between safe and malicious links.

The Gradient Boosting approach stood out with over 97% accuracy, indicating its effectiveness in identifying phishing threats and helping protect users from online scams.
