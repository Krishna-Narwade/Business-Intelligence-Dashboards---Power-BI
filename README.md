# Business-Intelligence-Dashboards-Power-BI

Hi , This Repository Contains End to End BI Dashboards for hospitality Domain 

[!Dashboard](https://github.com/Krishna-Narwade/Business-Intelligence-Dashboards---Power-BI/blob/main/Required%20Files/Hospitatlity%20Rervenue%20Insight.pdf)

**Domain:  Hospitality**                                                        
**Function: Revenue**

**Problem Statement**

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years.

Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

Task:  
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download section.

Create the metrics according to the [metric list](Metric List).
Create a dashboard according to the [mock-up](Mock up dashboard) provided by stakeholders.
Create relevant insights that are not provided in the metric list/mock-up dashboard.

=======================================================================================================================================================================

**Solution**
To solve I have followed the Below steps: 

**Step 1) :   To start any Analytics Project , we should we should understand the problem first.**

**Step 2) :   Data Transdormation (Power Query)**
              Load the data in Power BI and Do some Data Transformation. 
              In Our case We had more cleaned data , So I just some columns like , **week no :** which gives the week number from the date. **day_type:** such as
              weekday or Weekend. In Hotelling Industry specifically, The weekdays are from Sunday to Thursday and Friday and Saturday are considered tobe Weekend. 
              All these things were done using Power Query
              
**Step 3) :   Creating the Proper Data Modelling schema(Start Schema) and Making Proper Realtions amongs Fact and dim tables.** 
              For this project, We have around 5 Tables , from which 2 are Fact Tables and 3 are Dimnensions Table.
              So each table is correctly mapped with it corresponding Table(with proper Key)
             
     
**Step 4):    Some More Data Transformation (DAX)**
              By using DAX I have created around 23 key measures mentioned in the metrics list using Power BI DAX Measures.
              Few of the DAX functions I have used are CALCULATE , ALL , DIVIDE, AVERAGE
 
**Step 5):    Building the required Visuals and Formatting**
              I have created all the required viuals with some advanced functionality such as adding :arrow_down: , :arrow_up: and Creating the tooltip etc.
             
**Step 6):    Communicate the results to the Stakeholder and Take feedback**
              It is very important to communicate with the stakeholder and take a repetitive feedback from them untill you get the perfect dashboard.
              
              
              
       
             

             




