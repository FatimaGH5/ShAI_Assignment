# ShAI_Assignment
The assignment marks the initial step in the inclusion process for the ShAI Bootcamp.

                                      Employee Salary Analysis Report

1. Basic Data Exploration:

The dataset comprises 148,654 records of employees with 13 columns, covering various job titles and years.

The data type of coloumns is varying between int ,float and object

Names and Data types of each column: Id int64 EmployeeName object JobTitle object BasePay float64 OvertimePay float64 OtherPay float64 Benefits float64 TotalPay float64 TotalPayBenefits float64 Year int64 Notes float64 Agency object Status float64

These missing values were observed in some columns in the dataset.

BasePay 609 OvertimePay 4 OtherPay 4 Benefits 36163 Notes 148654 Status 148654

2. Descriptive Statistics for the salary('TotalPay'):

Basic statistics, including mean, median, mode, minimum, and maximum salary, were calculated.
The salary distribution has a range of 568213.560, with a mean of 74768.322.
Standard deviation indicates the degree of variability in salaries.
3. Data Cleaning:

To handle missing data by suitable method .
Notes and Status coloumns have not any value, all rows in there are null .we can not fill all null values with suitable values ,so i removed the two coloumns.
In OvertimePay column ,In order to do not affect the accuracy will fill the null values with mean value .median value for OvertimePay is rejected to fill with null becuase that always zero and the min -0.010.
In OtherPay column ,In order to do not affect the accuracy will fill the null values i mean value.Don not choose the median value becuase it is so small according to the mean and max of OtherPay.
In Benefits and BasePay columns are float type coloumn,In order to do not affect the accuracy will fill the null values with median value . In these two columns the mean and median are close.
median value is a measure of central tendency that is not affected by extreme values (outliers) in the dataset for each coloumn.
4. Basic Data Visualization:

Created histograms to visualize the distribution of salaries.
the histogram shows that the most frequent salary is about 85,000-90,000 and the least frequent salary is about 300,000.
Used pie charts to represent the proportion of employees in different departments(JobTitle).that shows the most frequent job in the data is transient operator.
5. Grouped Analysis:

The data was grouped by'Year' , 'JobTitle' , 'JobTitle' and 'Year' , 'Agency' and by 'OvertimePay', and summary statistics were calculated for each group.
Average salaries were compared across different groups, revealing insights into variations based on grouping criteria.
6. Simple Correlation Analysis:

There are 8 numerical columns Id,BasePay,OvertimePay,OtherPay,Benefits,TotalPay,TotalPayBenefits and Year .found the correlation between TotalPay and other numerical columns ,also plotted a scatter plot to visualize the relationship. .
The correlation between TotalPay and there self is 1.
The least correlation is -0.21 that between TotalPay and Id.
The most correlation is 0.98 that between TotalPay and TotalPayBenefits.
7.Recommendations and Further Investigation:

Benefits Optimization: Given the strong correlation between 'TotalPay' and 'TotalPayBenefits,' there is an opportunity to further investigate and optimize the benefits structure. This could involve assessing the impact of different benefit components on overall compensation.

Deep Dive into Departmental Dynamics: The observed departmental composition provides a foundation for a more in-depth exploration of each department's specific salary dynamics. Understanding the variations within departments can guide targeted HR policies and incentives.

Longitudinal Analysis: Conducting a longitudinal analysis over multiple years could reveal trends and patterns in salary changes. This can provide insights into the organization's growth, economic conditions, and evolving compensation strategies.

Employee Satisfaction Surveys: Complementing the quantitative analysis with qualitative insights through employee satisfaction surveys can provide a holistic understanding of how compensation impacts employee morale and satisfaction.

8.Conclusion:

In conclusion, this analysis equips stakeholders with actionable insights to enhance compensation strategies, streamline HR policies, and foster a work environment conducive to employee satisfaction and organizational success. Ongoing monitoring and iterative analyses will further refine these insights, ensuring adaptability to changing organizational dynamics.
This report provides a concise overview of the key findings and suggests areas for further exploration and analysis.
