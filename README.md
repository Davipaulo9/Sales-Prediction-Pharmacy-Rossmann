# Sales Forecast | Rossmann Drugstore Chain

![rossmann_store1](https://user-images.githubusercontent.com/30410050/185254615-515bffcc-43d4-4831-a58d-ed1d895c1307.jpg)




# 1.0. Business problem

Rossmann's Chief Financial Officer will be implementing within the next weeks important remodeling across all units for the drugstore chain. 
To be able to complete such massive task, he decided to request from the Data Science team, a sales's projection for the next six weeks. With this information in hands, a responsible payment plan can be implemented with minimum financial risks to the stakeholders.  

# 2.0. Understanding the Business

<li><strong>What's the motivation?</strong></li> Requested by the CFO to remodel the stores.

<li><strong> What is the root problem?</strong></li> Dificulty in determine the investment amount available for the remodeling.

<li><strong>What's the delivery method</strong></li> 
 
In this fictional scenario, our data source is a .csv file from a Kaggle competition, but it could be from the company's database, a set of spreadsheets, or other sources. You can access the data source on https://www.kaggle.com/c/rossmann-store-sales.

# Strategy

The Data team decided to implement the CRISP model ( Cross Industry Standard Process for Data Mining ). A ciclic and flexible methodology with quick turnaround.
A brief description below.


![CRISP_model](https://user-images.githubusercontent.com/30410050/185259805-bfa281c7-430a-4ec4-a50e-040f5563aa6d.png)

# 3.0 Business Assumptions

Rossmann Pharmacy expected fross income is betweeen R$5000 and R$22000. 

<li><strong>Stores sortment aren't equivalent in terms of type and quantity.</strong></li> 
<li><strong>Opening days vary from store to store</li> 
<li><strong>There are seasonal promotions that affect some but not all stores across</li> 


# 4.0 Solution Strategy

I've decided to pursue the following strategy to tackle the challenge.
 
 <strong>Step 1. Data Description: </strong>Remove empty or invalid registries. Update Data Types on all columns.

 <strong>Step 2. Feature Engineering: </strong> Derived new features to pursue a thourough analysis

 <strong>Step 3. Data Filtering: </strong> Data that isn't important or will not impact our analysis will be dropped out. 

 <strong>Step 4. Exploratory Data analysis: </strong> Univariate, Bivariate and Multivariate data Analysis were performed in order to obtain statistical properties. Find correlations between feattures and test hypothesis. 
 
 <strong>Step 5. Data Preparation: </strong> A boolean value was attributed to Promo column to identify if they ran a promo or not. 
 
 <strong>Step 6. Feature Selection: </strong>
 
 <strong>Step 7. Machine earning Modelling: </strong>
 
 <strong>Step 8. Model-2-Business: </strong>
 
 <strong>Step 9. Deploy Model to Production: </strong>
