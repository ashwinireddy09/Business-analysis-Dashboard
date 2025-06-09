# Crowdfunding Analysis-business analysis(interactive dashboard creation using MS Excel)
## Project Objective
a crowdfunding platform like Kickstarter, the objective is to analyze campaign performance, user behavior, and funding trends to provide actionable insights. The goal is to support data-driven decisions that enhance user experience, improve platform features, and increase successful project outcomes.

## Dataset used
- <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/Crowdfunding_Creator.xlsx">Dataset</a>
- <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/Crowdfunding_Location.xlsx">Dataset</a>
- <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/crowdfunding_Category.xlsx">Dataset</a>

## Questions (KPIs)
1. Convert the Date fields to Natural Time ( Currently the dates are in Epoch time Read the attached Artical for Reference on Epoch Time 
             https://www.epochconverter.com/ )
2. Build a Calendar Table using the Date Column Created Date ( Which has Dates from Minimum Dates and Maximum Dates)
  Add all the below Columns in the Calendar Table using the Formulas.
   A.Year
   B.Monthno
   C.Monthfullname
   D.Quarter(Q1,Q2,Q3,Q4)
   E. YearMonth ( YYYY-MMM)
   F. Weekdayno
   G.Weekdayname
   H.FinancialMOnth ( April = FM1, May= FM2  &. March = FM12)
   I. Financial Quarter ( Quarters based on Financial Month FQ-1 . FQ-2..)

3. Build the Data Model using the attached Excel Files.

4. Convert the Goal amount into USD using the Static USD Rate.

5. Projects Overview KPI :
     Total Number of Projects based on outcome 
     Total Number of Projects based on Locations
     Total Number of Projects based on  Category
     Total Number of Projects created by Year , Quarter , Month

6.  Successful Projects
     Amount Raised 
     Number of Backers
     Avg NUmber of Days for successful projects

7.  Top Successful Projects :
    Based on Number of Backers
    Based on Amount Raised.

8. Percentage of Successful Projects overall
   Percentage of Successful Projects  by Category
   Percentage of Successful Projects by Year , Month etc..
   Percentage of Successful projects by Goal Range ( decide the range as per your need )

- Dashboard Interaction <a href="https://github.com/ashwinireddy09/Business-analysis-Dashboard/blob/main/Screenshot%202025-03-04%20115647.png">View Dashboard</a>

   ## Process
   - Verify Data for any missing values and anomalies, and sort out the same.
   - Made sure data is consistent and clean with respect to data type, data format and values used
   - create pivot table according to the question asked.
   - merge all pivot tables into one dashboard and apply slicer to make dynamic.


## Dashboard
![Screenshot 2025-03-04 115647](https://github.com/user-attachments/assets/6678f091-0bfa-4434-82e2-07f64ea957c6)


## Project Insight
- Redesign Platform : Incorporate best practices and user feedback to optimize the crowdfunding website's design and functionality.
- Enhance Campaign Tools : Provide creators with more powerful features to manage, promote, and analyze their crowdfunding initiatives.
- Improve User Experience : Streamline the user journey, from campaign discovery to pledge completion, to increase conversion and engagement.




