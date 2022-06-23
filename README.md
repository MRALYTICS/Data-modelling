# HOW I MODEL A DATA IN POWERBI(# NG30DAYSOFLEARNInG)
...
# WHAT IS DATA MODELLING
Data modelling is the process of analysing and defining all the different data your business collects and produces, as well as the relationships between those bits of data. The process of modelling your data creates a visual representation of data as it’s used at your business, and the process itself is an exercise in understanding and clarifying your data requirements.Data modelling is a technique used in NORMALIZING data ,that is breaking them down into a fact table and dimension table.

 Fact Table: Contains data about an event, holding aggregated numeric data that you want to analyze. Dimension Table: Tables that keep metadata that describe the fact table that can be used to filter the fact table ; Typically in a data model you would have a single fact table and multiple dimension tables related to each other through keys.In other words fact table contains permanent data why dimenssion tables contains continuous data.
 

![STAR SCHEMA](https://user-images.githubusercontent.com/107101960/175217865-0f4d9f6d-980f-4e14-b4fd-16eae3bfa2d0.png)


# Case study: A superstore data
A denormalized data in excel

![Screenshot (191)](https://user-images.githubusercontent.com/107101960/175220925-ea0d8856-be06-4312-9648-50bc819193a4.png)
 
I normalised the data by breaking the data into the groups below![Screenshot (184)](https://user-images.githubusercontent.com/107101960/175222609-2a175167-c84c-4f36-80f1-abff9c10006a.png)

... 1 costumer table 2 Location 3 product table 4 sales rep table. this tables are called dimension table.
  The sales data contains unique keys(fAct table) that are both presents in the dimension table like the costumer id and so on...
  
   After normalizing the data i head to powebi to open the data 
    ![image](https://user-images.githubusercontent.com/107101960/175222293-c7520717-aa7e-44b3-91e4-632491cc1490.png)

I did some transormation on the product table data to change the first row to header and close and apply.
  i then click on the model view tab in ecxel and finally connect the keys in the dimension tables to the fact table
  ![Screenshot (190)](https://user-images.githubusercontent.com/107101960/175222916-63b1e8cb-726b-491e-a5d6-b1f46fe37e29.png)

  






