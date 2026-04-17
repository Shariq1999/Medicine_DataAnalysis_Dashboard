# Medicine_DataAnalysis_Dashboard
An interactive dashboard that explains showcases purchasing patterns of specific medicines. 

##Data Used
A set of synthetic data was used to make this dahsboard. The dataset simulates a product line that includes types of medicines and subclassification based on the formulations.

##Dashboard
<img width="1102" height="706" alt="Screenshot 2026-04-17 102046" src="https://github.com/user-attachments/assets/c74e08d9-b25e-421f-aebf-9cb0f7a0be35" />




##Solutions Used
Used multiple formulas inside Excel to first create a comprhensive table. 
Used XLOOKUP to lookup Patient-ID and Product-ID to understand the credentials of the person that purchased also the details of the product purchased. INDEX MATCH was used to retrieve the data of the Product ID i.e. the class of medications, unit price, Formulation, quantity.
Once the Table was made, a Pivot Table was created to Summarize the data and make the dashboard. In the Dashboard we used the slicer, Timeline and Charts to create an interactive and Dynamic Dashboard.

##Findings 
We can see the that Anti-biotics and Statins are more widely used. 
We also see that patients from the USA are the Bulk of our Users, so we should prioritize them.
Seasonality of the demand is seen, but accurate forecasting is not currently possible.

P.S. Since this is a synthetic data accurate predictions are not possible. But in reality a dashboard like this could aid in deciding Economic Order Quantity, Safety stock and so on.
The XLSS file with the dashboard has the data as well, for inspection, refer the document named Medicine Purchase Project_2.xlsx

