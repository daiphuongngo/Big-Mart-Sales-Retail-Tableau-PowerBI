# Big-Mart-Sales-Retail

### Category: 

- Retail

- Supermarket

### Overview:

The data scientists at Big Mart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and predict the sales of each product at a particular outlet.

Using this model, Big Mart will try to understand the properties of products and outlets which play a key role in increasing sales.

Please note that the data may have missing values as some stores might not report all the data due to technical glitches. Hence, it will be required to treat them accordingly.

### Target:

Visualizing multiple charts of all significant fields from the train set to analyze and report insights of how Outlet Sales is driven by store & product’s attributes at a retail store and on which variables should be focused further

### Dataset:

Train and Test sets: https://www.kaggle.com/akashdeepkuila/big-mart-sales?select=Train-Set.csv

### Variable Description

ProductID : unique product ID

Weight : weight of products

FatContent : specifies whether the product is low on fat or not

Visibility : percentage of total display area of all products in a store allocated to the particular product

ProductType : the category to which the product belongs

MRP : Maximum Retail Price (listed price) of the products

OutletID : unique store ID

EstablishmentYear : year of establishment of the outlets

OutletSize : the size of the store in terms of ground area covered

LocationType : the type of city in which the store is located

OutletType : specifies whether the outlet is just a grocery store or some sort of supermarket

OutletSales : (target variable) sales of the product in the particular store

### Tool:

- Tableau

### Visualization in Tableau:

#### Establishment Year vs Sum Outlet Sales

![Establishment Year vs Sum Outlet Sales](https://user-images.githubusercontent.com/70437668/138645192-a4cad38a-8c62-4a15-a552-8954bc518faf.jpg)

![Establishment Year vs Sum Outlet Sales](https://user-images.githubusercontent.com/70437668/140600437-b0ea0fcf-2389-4c0d-8604-31ef2bb9ba3b.jpg)

The first Establishment Year experience the highest ever-recorded Total Sum of Outlet Sales at over 3.6 million. Other Establishment Years fluctuated around the Average Total Sum of Outlet Sales at 2,065,861. Only the 1998 saw the lowest Total Sales at 188,340. There might be a significant crisis among the Big Mart or an external factor in this year.

#### Outlet Size vs Sum Outlet Sales

![Outlet Size vs Sum Outlet Sales](https://user-images.githubusercontent.com/70437668/138643910-732c921d-026d-4386-a497-c81987dc84ba.jpg)

![Outlet Size vs Sum Outlet Sales](https://user-images.githubusercontent.com/70437668/140600444-a974db88-2fea-4c28-940a-49cb3e10b5c5.jpg)

Medidum-sized Outlets contributed slightly more than half the Total Sum of Outlet Sales. Low and High-sized outlets gained moderately at 32.16% and 15.09%, respectively. This medium size can be aimed to expand other Big Mart's properties. Other sizes can be maintained or expanded at a low extent to guarantee the market domination.

#### Product Type vs Average Product Visibility

![Product Type vs Average Product Visibility](https://user-images.githubusercontent.com/70437668/138643919-0390f486-edf5-4d7a-9b55-5a552714ead3.jpg)

![Product Type vs Average Product Visibility](https://user-images.githubusercontent.com/70437668/140600446-63fc5262-fc49-449c-841b-cb2e8c942184.jpg)

(Analysis to be continued)

#### Fat Content vs Average Product Visibility

![Fat Content vs Average Product Visibility](https://user-images.githubusercontent.com/70437668/138645426-5f37d6e2-2672-44a6-a693-009797c66814.jpg)

![Fat Content vs Average Product Visibility](https://user-images.githubusercontent.com/70437668/140600438-12006e0d-dbb8-414e-b9b7-0f3119ac076b.jpg)

As the 5 groups are duplicated and can be categorized into 2 groups: Regular and Low Fat. I will select the relevant Fate Content and group them together as below.

#### Fat Content's 2 groups vs Average Product Visibility (revised)

![Fat Content vs Average Product Visibility](https://user-images.githubusercontent.com/70437668/138643931-cf125f1e-ef6e-4374-96db-a1d85cd8701d.jpg)

#### Sum Outlet Sales by Estb Year, Outlet ID, Product Type

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type](https://user-images.githubusercontent.com/70437668/138643941-cd3e5334-34b4-4623-8720-2a3a71a500f0.jpg)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type](https://user-images.githubusercontent.com/70437668/140600450-6a2c3914-4ca1-4aac-a754-16c3b65ee3cb.jpg)

#### Sum Outlet Sales by Estb Year, Outlet ID, Product Type (2)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type (2)](https://user-images.githubusercontent.com/70437668/138643955-f258dc39-7f5a-4a39-817d-6dbb39765498.jpg)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type (2)](https://user-images.githubusercontent.com/70437668/140600453-29e53a94-f31f-4ad5-975b-1aaae863199c.jpg)

#### Sum Outlet Sales by Estb Year, Outlet ID, Product Type (3)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type (3)](https://user-images.githubusercontent.com/70437668/138643964-f49166f5-b063-4947-abd5-61e80406c541.jpg)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type (3)](https://user-images.githubusercontent.com/70437668/140600459-fe0469d1-051a-4c84-954d-9ebee5305f14.jpg)

#### Sum Outlet Sales by Estb Year, Outlet ID, Product Type (4)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type (4)](https://user-images.githubusercontent.com/70437668/138643975-772a58bb-a708-4b68-b817-c81531798863.jpg)

![Sum Outlet Sales by Estb Year, Outlet ID, Product Type (4)](https://user-images.githubusercontent.com/70437668/140600460-6363b513-5a8c-41e7-b69e-92ca00225e2e.jpg)

#### Product Type by Average Maximum Retail Price

![Product Type by Average Maximum Retail Price](https://user-images.githubusercontent.com/70437668/138643989-a543f487-5eac-40f1-9637-026f86d8990b.jpg)

![Product Type by Average Maximum Retail Price](https://user-images.githubusercontent.com/70437668/140600462-3be6eb6e-feda-47fe-bf8c-fe45164e7768.jpg)

#### Outlet Type by Average MRP

![Outlet Type by Average MRP](https://user-images.githubusercontent.com/70437668/138644013-a5b99d52-929c-40a6-9946-58e9d0c4dbec.jpg)

![Outlet Type by Average MRP](https://user-images.githubusercontent.com/70437668/140600464-d8cf484b-2592-4695-b5c2-275512732c32.jpg)

#### Outlet Type by Average MRP (selected healthy products)

![Outlet Type by Average MRP (selected healthy products)](https://user-images.githubusercontent.com/70437668/138644021-96fb8785-3dc6-4ca4-9783-b1d38a0d5ca6.jpg)

![Outlet Type by Average MRP (selected healthy products)](https://user-images.githubusercontent.com/70437668/140600466-c7ea565b-338c-4263-a0e9-cefc699e8f32.jpg)

#### Outlet Type by Average MRP (selected non-healthy products)

![Outlet Type by Average MRP (selected non-healthy products)](https://user-images.githubusercontent.com/70437668/138644029-c19ba955-58bc-4169-b5ef-51dadc9fc524.jpg)

![Outlet Type by Average MRP (selected non-healthy products)](https://user-images.githubusercontent.com/70437668/140600468-1b64dfef-0aa9-444e-94dc-d943cf679a6e.jpg)

#### Product Type by Average Weight

![Product Type by Average Weight](https://user-images.githubusercontent.com/70437668/138644037-13928307-b911-49c9-a941-40eec09ef132.jpg)

![Product Type by Average Weight](https://user-images.githubusercontent.com/70437668/140600471-cb026139-bf6a-43d0-943b-fbd1971b724e.jpg)

#### Location Type / Outlet Size by Sum Outlet Sales

![Location Type - Outlet Size by Sum Outlet Sales](https://user-images.githubusercontent.com/70437668/138644045-f8665d3c-20ba-4253-8043-72bc3a972b31.jpg)

![Location Type - Outlet Size by Sum Outlet Sales](https://user-images.githubusercontent.com/70437668/140600473-435d230b-92b7-42f0-b957-7e58ae8453e8.jpg)

#### Dashboard - Outlet Type

![Dashboard - Outlet Type](https://user-images.githubusercontent.com/70437668/138644055-dc3f47ae-bf8b-42ef-ac45-da1ad6787089.jpg)

#### Dashboard - Total Outlet Sales

![Dashboard - Total Outlet Sales](https://user-images.githubusercontent.com/70437668/138645239-022b8d9f-d8aa-404e-98a0-c40df58b2cf3.jpg)

#### Dashboard - Outlet Type by Average MRP (healthy vs non-healthy)

![Dashboard - Outlet Type by Average MRP (healthy vs non-healthy)](https://user-images.githubusercontent.com/70437668/138644076-a4dcd7f6-851c-420b-b376-f6c38198c97a.jpg)

#### Dashboard - Product Type

![Dashboard - Product Type](https://user-images.githubusercontent.com/70437668/138645352-20af30b7-2530-440a-8726-c767d96535f1.jpg)

