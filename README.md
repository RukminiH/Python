**Project Overview**
This project involves web scraping data from AmbitionBox, a platform providing company reviews, ratings, and job insights. The primary objective is to gather and analyze data on various companies to offer valuable insights for job seekers.

**Key Insights**
**Employee Distribution:**
Companies have a wide range of employee sizes, from as few as 20 to over 100,000 employees.
Distribution plot showcases common employee size ranges.

**Company Ages:**
Companies in the dataset vary significantly in age, from 2 years (e.g., Kyndryl) to 333 years (e.g., Barclays).
Distribution plot highlights the spread of company ages.

**Headquarters Distribution:**
Distribution of companies based on their headquarters provides an overview of business locations.
Notable concentration of companies headquartered in Mumbai (102 companies).

**Additional Office Locations**:
Insights into the number of additional office locations, with most companies having 20 to 220 locations.

**Highly Rated Aspects:**
Horizontal bar chart depicts the top 10 areas where companies excel (e.g., work-life balance, company culture, skill development).
Example: Bharat, Tata companies are highly rated for work-life balance and company culture.

**Company Reviews:**
Violin plot shows the distribution and density of company reviews.
Companies like TCS have up to 68,000 reviews.

**Job Openings:**
Distribution of job openings is right-skewed, with most companies having 1 to 200 openings.

**Company Ratings:**
Visual representation of total ratings reveals common rating ranges between 3.75 to 4.25.
Top-rated companies include Accenture, ICICI, Amazon, IBM, etc.

**AmbitionBox Awards:**
Pie chart displays the percentage breakdown of AmbitionBox award winners, highlighting top companies like Accenture and Wipro.

**Data Cleaning and Preparation**
Verify for duplicate entries and null values.
Assess the DataFrame shape and column data types using the info method.
Inspect unique values in columns, calculate mean and median for numerical data.
Replace missing values using fillna with forward fill method.
Standardize data types using astype.
Drop unnecessary columns using the drop method with inplace=True.
Export the cleaned DataFrame to a CSV file and save it on the desktop.

**Preferred Companies by Job Seekers**
Top Choices: Accenture, Wipro, ICICI, HDFC, Infosys, Capgemini, Genpact, IBM, Reliance, HDB.
Highly Rated: Accenture, ICICI, Amazon, IBM, Larsen, HDB, Vodafone, Deloitte, Reliance, Bharti.
Company Culture, Job Security, Skill Development: Accenture and Titan.
Promotions/Appraisal, Salary & Benefits: Startek and eClerx.
Long History: Barclays, State, Deloitte, American, BT.
Large Workforce: Mahindra, TATA, Indian Reliance, Accenture, HCL, TCS.

**Conclusion**
This project aims to address several challenges faced by job seekers:

**Limited Company Insights:** Job seekers often lack detailed information on potential employers.
**Difficulty in Decision-Making:** Absence of comprehensive reviews makes it hard to align choices with career goals.
**Time-Consuming Research:** Manual research on multiple companies is time-intensive.
**Lack of Transparency:** Job seekers face uncertainty due to a lack of transparency in company practices.
**Risk of Uninformed Choices:** Without centralized reviews, there's a risk of making poor career decisions.
**Limited Peer Insights:** Absence of platforms like AmbitionBox means missing valuable peer insights.

By analyzing and presenting this data, we provide job seekers with valuable information to make informed career choices, enhancing their job search experience.

