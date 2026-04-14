Fraud Detection in Government Schemes 

Overview
This project aims to identify fraudulent beneficiaries in government schemes using a combination of logical rules and anomaly detection techniques. It focuses on detecting unusual patterns in user data such as excessive claims, mismatched financial information, and repeated use of accounts or devices.

Features
* Detects users with unusually high number of claims
* Identifies mismatch between income and claimed amount
* Flags duplicate bank accounts
* Detects multiple users operating from the same device
* Assigns a risk score to each user
* Classifies users into High, Medium, and Low risk
* Provides reasons for flagged fraud cases
* Visualizes fraud patterns using graphs

Approach
Rule-Based Detection

Basic checks are applied to identify known fraud patterns:
* High claim frequency
* Income mismatch
* Duplicate account usage
* Shared device usage

Anomaly Detection
An anomaly detection model is used to identify unusual behavior in the dataset without relying on labeled data.

Final Decision
The final fraud classification is based on a combination of:

* Calculated risk score
* Detected anomalies

Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

Output

The system generates:
* Fraud/Legit classification
* Risk score for each user
* Risk category (High / Medium / Low)
* Reasons for fraud detection
* Graphical analysis of fraud patterns

Project Structure
* "fraud_detection.ipynb" – Main notebook containing all code and results
* "README.md" – Project description

 Note:-The dataset used in this project is generated for testing and demonstration purposes.
 Future Improvements
* Use real-world datasets for better accuracy
* Deploy as a web application
* Improve detection using advanced models
* Add real-time monitoring features

Author
Developed as part of a hackathon problem on fraud detection.
