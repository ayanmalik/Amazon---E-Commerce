# Amazon---E-Commerce

### Dashboard Link : https://bit.ly/49cQKz6

### About Amazon.In

Amazon. In one of Leading e-commerce platform that sells many product lines, including media (books, movies, music,
and software), apparel, baby products, consumer electronics, beauty products, gourmet food, groceries, health and personal care,
kitchen items, jewelry etc.
 

# Amazon E-Commerce Dashboard: 

Using Power BI integrated data from Kaggle as CSV, created three pages Report where end user can go through multiple insights about                        
products e.g., Total sale/ Sold Units by State and City. Reviews, Returned by Category and Products etc.



# Steps followed : 

- Step 1 : Downloaded the Data from Kaggle as CSV.
- Step 2 : Load data into Power BI Desktop, dataset is a csv file.
- Step 4 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 5 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 6 : It was observed that in none of the columns errors & empty values were present in Dataset.
- Step 7 : Since dataset is not strctured in Proper way so Aplied steps Like Promoted Headers.
- Step 8 : Since the Image URL and Product Category was Presented as muptiple in a single column so Split the Column using delimeater and and Removed extra Column.
- Step 9 : Calender table wasn't Requried, Didn't try to increase Model Size by Genrating Calender Table.
- Step 10 : Since the dataset contains only Two Tables, thus in order to Create relationships, Create Many to many Relationship Between Amazon-Fashion - YT and Amazon Sales Table.
And Filter Cardinality was Single Directional.

# Snapshot of Data Model and Relationship.          

![image](https://github.com/ayanmalik/Meven-Cycle-Sales-And-Profit/assets/15996271/e361ccc9-7244-4a31-b445-e15d57ff7c60)

- Step 11 : In the report view, under the Overview tab, Set the canvas Color as Grey.

### *** Visuals And Tabs ***


# OverView Page:

OverView is a detailed summary about Product's state and Status.

- Step 12 : Added 1 Rectengle Shape to align Page nevigation button to nevigate all three pages and set the name of buttom as OverView, Products and Products View.


![image](https://github.com/ayanmalik/Meven-Cycle-Sales-And-Profit/assets/15996271/cd47e138-4495-4362-af93-dfb364d6cb87)



- Step 13: Added a custom named Text search Slicer on the rectengle shap to that  Products can be search by it's Category.

![image](https://github.com/ayanmalik/Meven-Cycle-Sales-And-Profit/assets/15996271/21310313-a26b-46d3-ba7d-4dbbc615a4dd)


- Step 14: Added Amazon Logo on that shape as well.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/a5b1c749-0a86-4b57-987c-611fae96bee7)


- Step 15: Added New Slicer to showcase the products Category.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/3ebe4bc1-c6a4-4ec2-b63a-63ac44dd0e3b)

- Step 16: Added a slicer to shwocase the products status.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/c1d9d56c-a793-4a2b-9ff4-1d227adefd60)


- Step 17: Added two Clustred bar chart to showcase Total sale by City and Total sale by State.

Here I have combine both charts to showcase Total unit/Sale by City and State. End user can switch the Sale/Units by pressing the buttons Sale and Units.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/e472797c-05c0-4c64-a865-02af3840685a)

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/b390083c-e459-4904-ab1e-2b574d14bc7b)


- Step 18: Area Chart Visual was added to showcase total sale/Units by Months. The sale and Units will be switch by Pressing Sale and Units Buttons.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/704baad6-0287-494b-a738-1d5d8ce782b7)


- Step 19: Three Card visual were added to show OverAll sale, Total Product sale, Total sold Units.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/8f71169c-1889-4084-8b2d-e83a85233b31)


### Overview page is ready to Functions

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/1a5c5dff-c307-4a8d-a866-557670d07c8e)



# Products Page:

On Products page the end user can All producuts with it's Category.



- Step 20: Rectengle shape was copied along with Navigation Button, Seach Visual and Logo and set on Top of the Canvas.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/ad29bc8f-e953-45d8-a033-c6c4673f02f1)


- Step 21: Added New Slicer to showcase the products Category.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/3ebe4bc1-c6a4-4ec2-b63a-63ac44dd0e3b)

- Step 22: Another New Slicer added to showcase Products.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/a98e35f7-1f7f-4656-a186-a790fca59529)

- Step 23: A new page added to as tooltip and set as a tooltip on Products.

If the end user will hover over on any of product Tooltip will work accordingly.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/a07c5afe-72fc-4950-a8f9-1733eaa13a45)

### Products Page Ready to function

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/7d162300-afbf-4bc0-92aa-4c1e3839f671)

# Product View Page: 

By Clicking Navigation Button named Products View, The end user can navigate to the Product View page.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/e90be573-4cb1-4ac4-b860-1705f2533cab)

- Step 24: Rectengle shape was copied along with Navigation Button, Seach Visual and Logo and set on Top of the Canvas.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/5fef7511-d44e-4551-bd9e-c8f24c2a73a9)

- Step 25: New Slicer was added to bottom of the canvas to showcase All products so that end user can click any of product and can check all insights.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/98f3ccff-5b6b-47ab-8743-2fb4d293ccc2)

layout set to single RAW and style set to cards and shap is set Rectangle so that products can be clicked.

- Step 26: Another new card added to the canvas show bigger image of the selected Product.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/ed3d4132-b532-4b0f-9d8b-545707c68104)


- Step 27: Another Text shap added to the canvas to showcase Products details. 


![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/31736490-07d4-46fe-8257-44943eba897c)


- Step 28: 5 Card Visuals were added to the canvas to show Total Sale amount of the products, Total Sold Units, Number of Return Order, Selling Price and Number of Customer Reviews.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/01b5f8a4-a6b2-477e-bb54-7cc51bc85780)

- Step 29: Another Area chart Visual Added to showcase product sale by Month.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/93142eda-c40a-4221-8faa-c81e6f520be2)


- Step 30: A Date visual added to the canvas so that user can choose the date.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/d57cf51c-b87d-4bc7-be24-5d71bd925267)

### Product View Ready To Function

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/f11a366d-c63c-4819-a237-5a465e5a6cfe)
 

## Calculated Column was added to the data Model because we have to calculate the Total amount.

Following DAX expression was written for the same,

		Total Amount = 
			   'Amazon Sales'[Qty]*'Amazon Sales'[Amazon-Fashion - YT.sales_price]

## New Table was added to Datamodel to Configure the Salection of Button action Sale and Units.


Following DAX expression was written for the same,


    Sale_Option = 
            DATATABLE(
                    "Type",STRING,
                    "Name",STRING
                ,{
                    {"1","Sale"},
                    {"2","Units"}
                }
    )

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/6219b2df-828a-440b-96f8-26621cb7c20a)



## New Measure Table was added to Data Model So that all measures can be organized.
        
- Step 31 : New measure was created to calculate To OverAll Sale.

Following DAX expression was written for the same,
        
             All Over Sales = 
                        CALCULATE(
                             [Filter Sale] ALL('Amazon-Fashion - YT'                               [Category] 
                             )
                        )

A Card visual was used to represent Overall Sale


![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/f1bfe8c8-1b79-48af-a4e4-23faa19996e9)

  - Step 32 : New measure was created to calculate To Sale.

Following DAX expression was written for the same,


        Total Sale_Amount = 
                        SUM(
                        'Amazon Sales'[Amazon-Fashion - YT.sales_price]
                    )


- Step 33 : New measure was created to calculate To Sold Units.

Following DAX expression was written for the same,

        Total Units = 
                SUM(
                    'Amazon Sales'[Qty]
                 )

   
 - Step 34 : New measure was created to filter Sale and Sold Units.

Following DAX expression was written for the same,

    Filter Sale = 
        Var _select =
            SELECTEDVALUE(
                Sale_Option[Type]
            )

    RETURN 
        IF(
        _select="1",[Total Sale_Amount],[Total Units]
        )

      

Two Clustered Bar chart and One Area Chart visuals was used to represent it.
         
![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/901e34dd-2bb5-4596-b9e7-0bb474831cef)
![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/7135d390-740e-41e3-bdda-91a5d5cd1680)
![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/7691a263-7bca-41a9-8c85-285d56e3e0c2)
 
- Step 35 : New measure was created to get result of Sale.


Following DAX expression was written for the same,

    Selection Sale = 
        Var _select =
            SELECTEDVALUE(
                Sale_Option[Type]
            )

        RETURN 
         [Total Sale_Amount]  


- Step 36 : New measure was created to to get result of Units.

Following DAX expression was written for the same,


        Selection Units = 
            Var _select =
            SELECTEDVALUE(
                Sale_Option[Type]
            )

            RETURN 
                [Total Units]



- Step 37 : New measure was created to change Title of the Visual (Clustered Bar chart of City).

Following DAX expression was written for the same,


     Selection City = 
            Var _select =
            SELECTEDVALUE(
                Sale_Option[Type]
             )

        RETURN 
            IF(
             _select="1","Sale By City","Units By City"
            )


Clustered Bar chart visual was used to represent it.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/05f092c1-5c92-4e48-ae97-113501d5768d)

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/0b6063fa-75b5-4798-a0ee-ef42f8b20e92)



- Step 38 : New measure was created to change Title of the Visual (Clustered Bar chart of State).

Following DAX expression was written for the same,


	Selection State = 
        Var _select =
            SELECTEDVALUE(
                 Sale_Option[Type]
            )

        RETURN 
            IF(
             _select="1","Sale By State","Units By State"
        )



Another Clustered Bar chart visual was used to represent it.


![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/d12e3f8c-2551-4cb0-993e-8bb0516dff9d)
![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/312dd43a-3243-4574-9b76-eeebd4328792)



- Step 39 : New measure was created to get smaller Bars of Clustered Bar chart.

Following DAX expression was written for the same,

	Lables PlaceHolder = 0

This Measure was used in Clustered Bar chart visual.


![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/901e34dd-2bb5-4596-b9e7-0bb474831cef)


- Step 40 : New measure was created to change Title of the Visual (Area chart).

Following DAX expression was written for the same,



    Selection Months = 
        Var _select =
        SELECTEDVALUE(
            Sale_Option[Type]
            )

        RETURN 
            IF(
             _select="1","Sale By Months","Units By Months"
            )



![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/ed296313-0b4a-4ae0-823d-107449c4c10d)

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/02db5ce8-8b57-43c9-9ed6-4b51d401fc04)



- Step 41 : New measure was created to total Reviews.

Following DAX expression was written for the same,



    Reviews = 
        Var _rev = SUM(
            'Amazon-Fashion - YT'[no_of_reviews]
            )

        RETURN
            IF(
            _rev = BLANK(),0,_rev
            )




Card visual was used to represent it.


![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/feedaf5e-6bed-4550-9d66-2e075c1b6011)


- Step 41 : New measure was created to total Returned Orders.

Following DAX expression was written for the same,




    Returned_Orders = 
        Var _Return = 
            CALCULATE(
                SUM(
                    'Amazon Sales'[Qty]
                    ),
        'Amazon Sales'[Status]="Shipped - Returned to Seller")

        RETURN 
            IF(
                _Return = BLANK(),0,_Return
                )



A Card visual was used to represent it.

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/823f2454-f575-45cb-8cc7-92ac50ed8d22)


### A 4 pages report was created on Power BI Desktop & it was then published to Power BI Service.

 - Step 42 : The report was then published to Power BI Service.

 # Snapshot of Dashboard (Power BI Service)

![Amazon Published to Workspace](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/6d0ae0fc-bb2a-4943-8f3c-19dbe453cf89)
 
# Report Snapshot (Power BI DESKTOP)

![image](https://github.com/ayanmalik/Amazon---E-Commerce/assets/15996271/c42790d6-b162-4937-80bf-d15fd09d807b)








