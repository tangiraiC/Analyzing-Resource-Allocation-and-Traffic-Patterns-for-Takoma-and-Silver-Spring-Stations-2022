# Analyzing-Resource-Allocation-and-Traffic-Patterns-for-Takoma-and-Silver-Spring-Stations-2022
A project done for the course Applied managerial statistics using r programming qmd

**To: Managing Partner Shawn Janzen**

**From: Lincoln Chanakira and Angela Ngano**

**Subject line :Analyzing Resource Allocation and Traffic Patterns for Takoma and Silver Spring Stations– 2022 Study Insights**

**Date :** September 17th, 2024

In light of the close proximity of the Takoma and Silver Spring train stations, we undertook a studytoensure a fair and efficient allocation of resources between the two stations. This research aims to predict resource demands by analyzing key variables such as service type and traffic levels. UtilizingtheWMATA dataset, the analysis focuses on data from the year 2022, specifically targeting the TakomaandSilver Spring stations to uncover actionable insights for improving service efficiency. 

**Hypothesis Statement:** The Traffic levels at Takoma and Silver Spring stations in 2022 have a significant impact on the type of service provided. 

**Weekdays Show Highest Traffic Demand:** The analysis reveals that traffic levels are significantl higher on weekdays compared to weekends, suggesting a need for increased service frequency during these peak times to better accommodate passenger demand. 
**Weekend Traffic is Lighter:** Traffic at both stations is notably lighter on weekends, indicating potential for service reductions. The Traffic Level variable was derived from
recoding of the entries or boarding a numeric variable which consisted of the average number of passenger entries, recorded by faregates in rail stations(Washington Metropolitan Area Transit Authority, 2024).It is categorized into 3 groups namely light ,moderate and high with light being the lowest going upwards respectively. The table reflects a diverse distribution of traffic levels, withthemajority falling into the moderate category whereas both light and high traffic levels reflect a balanceddistribution.

<img width="293" alt="Screenshot 2024-11-01 at 12 42 18" src="https://github.com/user-attachments/assets/4f713d72-3afc-4ddb-8f6f-eecd513ab56c">

The **Service Type** variable represents the type of rail schedule Metro planned to run on that day of service day of the week, typically divided into categories such as Weekday , Saturday and Sundayandholiday schedules (Washington Metropolitan Area Transit Authority, 2024). Our subset of data includesonly weekdays, Saturday, and Sunday.While most transit services are provided on weekdays, bothSaturday and Sunday show similar service frequencies. As part of our analysis, a Chi-square test was conducted to examine the association between traffic level and service type, using a significance level of 0.05. The test results indicated a Chi -square of **X²(4, N = 365) = 252.54**, p value < 2.2e-1. The results indicate a statistically significant relationshipbetween traffic levels at Takoma and Silver Spring stations and the type of service provided. Withap- value well below 0.05, we can reject the null hypothesis, suggesting that traffic levels influence the typeof service. The effect size (Cramér's V = 0.42) indicates a moderate relationship between the variables, and a power of 1 shows a high likelihood of the test results being reliable.
<img width="629" alt="Screenshot 2024-11-01 at 12 46 16" src="https://github.com/user-attachments/assets/fe22d49d-df90-4fe0-9604-9c547098b17a">


Weekdays exhibit majority of high traffic (67%), indicating that services are more concentrated duringheavy traffic periods whereas Sundays are dominated by light traffic (51%), contrasting with the lowlight traffic on weekdays (1%). Saturdays have a more balanced spread between light, moderate, and hightraffic, unlike the clear skew toward heavy traffic on weekdays. While the tests suggest a significant relationship between traffic levels and service type, there could have been other external factors suchas
limited sample diversity that might have also affected the outcome. Therefore expanding the sample andincluding more variables could improve future analyses. Based on the observed traffic patterns, we recommend increasing service frequency on weekdays to accommodate higher demand and a reductioninservice during weekends, especially Sundays, could help optimize resource allocation, given the lower traffic levels observed on those days. 

**Bibliography**
Washington Metropolitan Area Transit Authority. (2024). Ridership data portal metadata (Version2024-01-24). https://www.wmata.com/initiatives/ridership-portal/upload/RDP-Metadata-2024-01-24.pdf
