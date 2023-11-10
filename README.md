# Data Science Salaries 2023

<img width="1060" alt="Screenshot 2023-11-10 at 3 59 41 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/5060e13d-1fb4-4b59-a485-03136493e6cd">

# project-1

This project will investigate average data science salaries compiled across a number of companies 2020-2023 in relation to factors like experience level, job title, company location/size. 

It will answer the following questions: 

- How does average salary vary in relation to experience?
- How does salary vary based on job title?
- How does company location impact salary? What about company size?
- How does employment type effect salary?
- How are the findings relevant?
- What are the limitations of the data frame?

Hypothesis: There is a positive relationship between average data science salaries and experience level,  job title, and company size: the higher the experience level, the more senior the job title, and the greater the company size — the higher the average salary. 

Statistical test: conduscting data analysis using pandas, numpy, scipy.stats and matplotlib to compile summary statistics in Jupyter notebook and thus calculate, and compare average data science salary based on a variety of factors. 

Executing ANOVA Test to except/reject null hypothesis. 

<img width="1048" alt="Screenshot 2023-11-10 at 4 00 18 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/25fb2d84-7728-42b4-8933-5c6827f6dc90">

<img width="1021" alt="Screenshot 2023-11-10 at 4 01 07 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/62a97177-41ad-456d-add7-06236b05d358">

<img width="1032" alt="Screenshot 2023-11-10 at 4 01 22 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/d573fef1-cb9c-4702-aad5-8f063cf35a36">

<img width="1024" alt="Screenshot 2023-11-10 at 4 01 35 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/70991d47-dc94-4460-a631-b38a7b047d59">

<img width="1032" alt="Screenshot 2023-11-10 at 4 02 01 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/97fb7c1f-6571-42b7-a0b5-7e96c5eac791">

<img width="1015" alt="Screenshot 2023-11-10 at 4 02 17 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/58ce0fb3-4a30-46c5-a3e4-9b0a1b1da40a">

<img width="1019" alt="Screenshot 2023-11-10 at 4 02 33 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/604c0f18-6f99-46aa-98ff-d7688233f21a">

<img width="1029" alt="Screenshot 2023-11-10 at 4 02 50 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/f8887ddc-543a-4849-bce3-171dc7fa4e8d">

<img width="1026" alt="Screenshot 2023-11-10 at 4 03 04 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/7f1e5958-f86d-4cf8-b9a9-5fcdb73bddc4">

<img width="1025" alt="Screenshot 2023-11-10 at 4 03 21 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/e74f6561-6a60-4834-b6a5-e17c134a806b">

<img width="1027" alt="Screenshot 2023-11-10 at 4 03 44 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/95abc349-c504-4e6b-8fac-92c6e73ea716">

<img width="1028" alt="Screenshot 2023-11-10 at 4 03 59 PM" src="https://github.com/anastasiaskr2000/project-1/assets/131491720/7a85dceb-3f4d-4d43-a8df-e4eb54185dac">

Findings: 

We can conclude that employees with Middle to Executive experience levels earn the highest salaries, as proven by average salary per experience level.

There is a steep decrease in average salary from 2021 to 2022, with 2021 reporting the highest average salaries while 2023 is seeing some of the lowest. The highest standard deviation value around year 2022 and the steepest decrease in average salary following this year can be explained by the effect of COVID-19 on businesses and employment, especially as many corporations were forced to administer severe pay cuts & lay off many employees to cut costs. 

Employment type also effects average salary, with freelance (FL) and full-time (FT) employees leading with the highest salaries as opposed to part-time (PT) and contract (CT) employees. This makes sense considering the freedom that a freelance employee has to seek labour with multiple companies at once, choose the best-paying opportunities & work more than an average employee working for one specific company. 

Average salary varies significantly in relationship to job title, as is visualized on scatter plots 1, 2, 3. 

BI Data Analyst (see "Average Salary Based on Job Title 1") & Data Analytics Lead are the most profitable job positions on average, sitting much higher than the cluster of average salary points aggregated towards the centre of the plot. 

Further outliers can be noted on the second scatter plot (see "Average Salary Based on Job Title 2"), such as Data Science Manager, Data Science Tech Lead & Head of Data Science.

Average Salary Based on Job Title 3" likewise presents several outliers which defy the general pattern of aggregation, such as Lead Data Analyst and ML Engineer, as well as less drastic outliers, i.e., Power BI Developer and Product Data Analyst.

Both Employee Residence & Company Location have a significant impact on overall salary. Highest Salaries measured in US dollars are reported in the Unites States of America (US), Great Britain (GB) and Israel (IL), with 3/5 highest reported salaries coming from US-based companies. 

Lowest salaries are reported in Czechia (CZ) and India (IN), with one exception of a US-based company but in relation to an employee residence in India, suggesting lower salary paid out, likely due to outsourcing labour to cut costs.

Company Size is another factor that displays an interesting and not entirely proportional relationship to average salary, as we can see that large and small companies, on average, pay their employees higher wages than mid-sized companies. This makes sense considering larger companies and corporations employ greater numbers of professionals & operate on international levels, incurring larger costs. Smaller companies have fewer employees to pay out and retain, and are forced to distribute income more competitively so as not lose employees to bigger, more widely-known companies.

Since all the p-values are less than the level of significance, we do not have sufficient evidence to reject the null hypothesis stating that the means of each group are equal. However, our p-values being less than 0.05 implies that one group does not have the same mean as others: different levels of distribution imply a difference in salary, hence the signular effect that each category has on average salary. 

We can conclude that the best-paying companies are US, GB and IL, with the exception of outsorcing in such instances when the employee residence differs from company location. Your odds at a high salary are also dependent on company size, and in certain instances, experience level (though not  limited by it). 

Some limitations of this dataset are statistically low p-values and a lack of real company names to relate to real-world scenarios & entice potential clients/audience who might be interested in this research as a means of conducting job search. There is also a timing constraint of only 4 years of data which makes it difficult to consider this an extensively cumulative visualization of data science careers over a significant period of time. Another limitation is the data's accumulation of salaries across a wide range of countries in USD: this limits us to comparing salary based on Western standards of income and living even though for someone in India (a comparatively low-salary country in this dataset) the corresponding salary earned may be sufficient despite not meeting USD benchmark that is used as a comparison point. While we can see varying degrees of impact on salary based on a number of factors, we can conclude using the ANOVA Test that due to different distribution between a variety of categories the average salary is heavily dependant on a number of factors that will skew the result in various combinations. 
