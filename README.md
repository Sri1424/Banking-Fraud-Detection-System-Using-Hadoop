
The primary goal of this project is to design a honeypot-based network intrusion detection
system (IDS) that can effectively detect and monitor malicious activities in a network. The
objectives are as follows:
 Data Ingestion and Storage: Collect large volumes of banking transaction data and
store it efficiently in HDFS for distributed processing.
 Hadoop-Based System Design: Develop a scalable fraud detection architecture using
Hadoop tools such as HDFS, Hive, and Pig to handle massive financial datasets.
 Data Preprocessing and Feature Extraction: Clean, transform, and preprocess
transaction data while extracting key behavioral features such as transaction amount,
frequency, time, and location.
 Fraud Detection and Analysis: Analyze transaction patterns to identify and classify
suspicious or abnormal activities using machine learning techniques integrated with
Hadoop.
 Evaluate Detection Performance: Assess the system’s effectiveness by measuring
accuracy, recall, false positives, and overall detection efficiency across varied datasets.
 Document Findings: Document the entire setup, methodology, execution, and results,
highlighting insights into fraud patterns and improvements in banking security.
8
2. DATESET DESCRIPTION
Banking Transaction Dataset Overview
The banking transaction dataset is a crucial component of fraud detection systems, designed to
analyze customer transaction patterns and identify abnormal or suspicious activities. This
dataset consists of large volumes of financial transaction records collected from digital banking
platforms, enabling the system to detect irregularities that may indicate fraudulent behavior. By
processing this data through Hadoop’s distributed ecosystem, financial institutions can
efficiently analyze transaction trends, detect anomalies, and understand how fraudulent
activities occur. Such datasets play a vital role in strengthening fraud prevention strategies,
improving security mechanisms, and enhancing decision-making for real-time detection. By
leveraging detailed transaction logs that closely resemble real-world financial operations, the
dataset provides meaningful insights into how fraudulent transactions differ from legitimate
ones, helping improve the accuracy and reliability of the fraud detection model.
Structure and Composition  Total Transactions: 100,000+ financial transaction records used for analysis and model
training.
o Legitimate Transactions: Majority of entries representing normal user
activities.
o Fraudulent Transactions: A smaller portion consisting of labeled fraud
cases used for pattern identification.  Dataset Configuration: Each transaction entry contains multiple attributes that
describe the user’s financial behavior and transaction context.  Feature Categories: The dataset includes 10 major types of transaction features
that closely resemble real banking operations:
o Categories: Transaction Amount, Transaction Time, Transaction
Location, Transaction Type, Account Balance, Merchant Category,
Device/Channel Used, Transaction Frequency, Account Age, and Fraud
Label (0 = genuine, 1 = fraud). 
