**Marketing-Analytics: Campaign Performance and Customer Segmentation**

Marketing-Analytics is a data-driven project designed to optimize marketing campaigns by extracting data from AWS S3, analyzing campaign performance, segmenting customers based on demographic features, and identifying key factors influencing sales using statistical testing.

**Project Workflow**

**1. Data Extraction from AWS S3**

Data is stored in AWS S3 buckets.
Extracted the data using Boto3, the AWS SDK for Python.
Loaded the extracted data into a Pandas DataFrame for further analysis.

**2. Campaign Analysis**

Evaluated the performance of various marketing campaigns.
Key metrics such as conversion rate, customer engagement, and ROI were analyzed.
Selected the best-performing campaign based on these metrics.

**3. Customer Clustering**

Performed customer segmentation using clustering techniques.
Segmented customers based on:
Age
Income
Clustering helped identify distinct customer groups for targeted marketing.

**4. Statistical Testing**
   
Conducted statistical tests to determine which features significantly impact sales.
Identified influential features such as age, income, or campaign type.
Provided actionable insights for designing data-driven marketing strategies.

**Technologies Used**

Python: Core programming language for data extraction, analysis, and modeling.

Boto3: AWS SDK for Python, used to interact with S3 for data extraction.

Pandas: For data manipulation and cleaning.

Scikit-Learn: For clustering analysis.

SciPy: For statistical testing.

Matplotlib & Seaborn: For data visualization.
