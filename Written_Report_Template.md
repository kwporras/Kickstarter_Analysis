# **Kickstarting with Excel**

## **Overview of Project**

### **Purpose**
To review and analysis kickstarter data to provide insight.
specifically, we focused on when to launch a campaign and with what goal to increase the chance of success.
    
## **Analysis and Challenges**

### **Analysis of Outcomes Based on Launch Date**
The chart below displays the count of successful, failed, and canceled theater campaigns over from 2009 to 2017. 
![alt text](https://github.com/kwporras/kickstarter-analysis/blob/d38f7a3e95d0eb7cfcb8c71e23d375cd1be9892b/Theater_Outcomes_vs_Launch.png)
The purpose of this chart is to provide insight as to which month may increase the chances of a successful campaign launch.
To create this chart the below filters were selected.
![alt text](https://github.com/kwporras/kickstarter-analysis/blob/d38f7a3e95d0eb7cfcb8c71e23d375cd1be9892b/Pivot%20Table%20design%20for%20Theater%20Outcomes%20by%20Launch%20Date.png)

### **Analysis of Outcomes Based on Goals**
The chart below displays the number of successful, failed, and canceled theater campaigns displayed in various increments.
![alt text](https://github.com/kwporras/kickstarter-analysis/blob/d38f7a3e95d0eb7cfcb8c71e23d375cd1be9892b/Outcomes_vs_goals.png)
Additionally, each increments shows the percentage of successful or failed campaigns per increment.
The purpose of this chart is to provide insight what kind of set goals are most successful for theater campaigns.
The chart was created by referencing the percentage formulas.
Percentage formulas are straight forward, however the countifs formula to a little work.
An example of the countifs formula is displayed below.
![alt text](https://github.com/kwporras/kickstarter-analysis/blob/d38f7a3e95d0eb7cfcb8c71e23d375cd1be9892b/Outcomes%20Base%20on%20Goals%20Coutifs%20formula.png)

### **Challenges and Difficulties Encountered**
The counties countifs formula could be difficult for a few people to write, particularly when entering greater/less or equal to signs in the formula. 
The "=" sign have to come after the "> or <" signs. Additionally, the statement needs to but placed in quotation marks.

## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The best outcomes seems to be in summer times, particular May and June, in terms of success and quantity.
  2. The last quarter (October, November, December) has some of the worst outcomes with more failed campaigns and low volume. 

- What can you conclude about the Outcomes based on Goals?
  The majority of successful campaigns are set below $10,000 and those below $5000 have the highest percentage of success. 
- What are some limitations of this dataset?
  The sample size is too small and the location information is vague which make it difficult to know where to actually launch the plays. 
- What are some other possible tables and/or graphs that we could create?
  A pie chart would be interesting to look options other than theaters or a Histogram to filter out any outliers that may skewing the analysis.

 
