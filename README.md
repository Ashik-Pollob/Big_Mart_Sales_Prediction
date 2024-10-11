# Big_Mart_Sales_Prediction
The BigMart dataset have 2013 sales data for 1559 products across 10 stores in different cities. Here, certain attributes of each product and store have been defined. The aim is to build a predictive model.
## Data Source 
The "The BigMart Sales Prediction" data is available at [Kaggle](https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets).
## Variables
### Independent Features:
- Item_Identifier ---- Unique product ID
- Item_Weight ---- Weight of product
- Item_Fat_Content ---- Whether the product is low fat or not
- Item_Visibility ---- The % of the total display area of all products in a store allocated to the particular product
- Item_Type ---- The category to which the product belongs
- Item_MRP ---- Maximum Retail Price (list price) of the product
- Outlet_Identifier ---- Unique store ID
- Outlet_Establishment_Year ---- The year in which the store was established
- Outlet_Size ---- The size of the store in terms of ground area covered
- Outlet_Location_Type ---- The type of city in which the store is located
- Outlet_Type ---- Whether the outlet is just a grocery store or some sort of supermarket
### Dependent Feature:
Item_Outlet_Sales ---- sales of the product in t particular store. This is the outcome variable to be predicted.
## Figures
- Dependent variable<br>
![predicted variable](https://github.com/user-attachments/assets/3de9ae0c-f14c-4751-90cf-5971d862fd9a)
![Numerical Features](https://github.com/user-attachments/assets/a2ce80f0-6b43-401d-b978-6f92ef156733)
![Categorical Features](https://github.com/user-attachments/assets/9ab3ae4b-a1ba-45c6-8dd9-1f2f8d974a5f)
![XGB Scatter](https://github.com/user-attachments/assets/36ffd327-c138-4e68-8710-f8b95f754083)
![XGB Redsidual](https://github.com/user-attachments/assets/8dc65a4c-5fa9-481d-bf31-7a5388e98396)
![LR Scatter](https://github.com/user-attachments/assets/8b542ddb-2be4-42e6-99db-f82540868834)
![LR Residual](https://github.com/user-attachments/assets/75012d01-23b5-4868-b308-7fade8945fc0)
![KNN Scatter](https://github.com/user-attachments/assets/3e769bc6-1a99-4a3e-9afd-83b205fa0c33)
![KNN Residual](https://github.com/user-attachments/assets/0b606ee9-ded5-4fdd-9679-02a4d144a1a8)

