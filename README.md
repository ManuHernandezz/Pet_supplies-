# Pet_supplies-

PetMind is a retailer of products for pets. They are based in the United States.

PetMind sells products that are a mix of luxury items and everyday items. Luxury items include toys. Everyday items include food.

The company wants to increase sales by selling more products for some animals repeatedly. 

They have been testing this approach for the last year. 

They now want a report on how repeat purchases impact sales. 

## Data

The data is available in the table `pet_supplies`.

The dataset contains the sales records in the stores last year. 

| Column Name | Criteria                                                |
|-------------|---------------------------------------------------------|
|product_id | Nominal. The unique identifier of the product. </br>Missing values are not possible due to the database structure.|
| category | Nominal. The category of the product, one of 6 values (Housing, Food, Toys, Equipment, Medicine, Accessory). </br>Missing values should be replaced with “Unknown”. |
| animal | Nominal. The type of animal the product is for. One of Dog, Cat, Fish, Bird. </br>Missing values should be replaced with “Unknown”. |
| size | Ordinal. The size of animal the product is for. Small, Medium, Large. </br>Missing values should be replaced with “Unknown”.|
| price | Continuous. The price the product is sold at. Can be any positive value, round to 2 decimal places. </br>Missing values should be replaced with the overall median price. |
| sales | Continuous. The value of all sales of the product in the last year. This can be any positive value, rounded to 2 decimal places. </br>Missing values should be replaced with the overall median sales. |
| rating | Discrete. Customer rating of the product from 1 to 10. </br>Missing values should be replaced with 0. |
| repeat_purchase | Nominal. Whether customers repeatedly buy the product (1) or not (0). </br>Missing values should be removed. |
