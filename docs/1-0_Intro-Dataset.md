# Index

#### Part I: Data analysis
- [1.0 | Intro into the dataset](1-0_Intro-Dataset.md)
- [1.1 | Setup your data analysis environment](1-1_Environment-Setup.md)
- [1.2 | Further readings on data analysis](1-2_Collection-Data-Analysis-Libraries.md)

#### Part II: Animated data stories
- [2.0 | About data stories](2-0_Intro-Datastories.md)
- [2.1 | Further readings on animated data stories](2-1_Collection-Animated-Datastories.md)

---

# 1.0 Intro into the dataset
## Dataset
We suggest using the following open dataset `dataset\turkish_retail_data`\
_Source (https://www.kaggle.com/berkayalan/retail-sales-data)_

### Overview
This dataset contains 3 years of sales records from a turkish retail company. 

The dataset consists of three `.csv` files, representing a hierarchical data structure: 

- `sales.csv` - Daily sales records covering the years 2017-2019.
- `product_hierarchy.csv` - Data containing the hierarchy and sizes of the products.
- `store_cities.csv` - Data containing the city, type and size information of the stores.

### Features
`sales.csv`:
- `product_id`: The unique identifier of a product `string`
- `store_id`: The unique identifier of a store, references `stores_cities.csv/store_id` `string`
- `date`: Timestamp of the record (YYYY-MM-DD) `string`
- `sales`: Number of items sold at this day `float`
- `revenue`: Daily total sales revenue `float`
- `stock`: End of day stock quantity `float`
- `price`: Product sales price `float`
- `promotype1`: Type of promotion applied on channel 1 `string`
- `promobin1`: Binned promotion rate for applied promotype1 `string`
- `promotype2`: Type of promotion applied on channel 2 `string`
- `promobin2`: Binned promotion rate for applied promotype2 `string`
- `promodiscount2`: Discount rate for applied promo type 2 `string`
- `promodiscounttype_2`: Type of discount applied `string`

`product_hierarchy.csv`:
- `product_id`: references `sales.csv/product_id` `string`
- `cluster_id`: Cluster of products based on Sales `string`
- `product_length`: Length of product `float`
- `product_depth`: Depth of product `float`
- `product_width`: Width of product `float`
- `hierarchy1_id`: 1st level hierarchy: For Example: Foods and Beverages `string`
- `hierarchy2_id`: 2nd level hierarchy: For Example: Beverages `string`
- `hierarchy3_id`: 3rd level hierarchy: For Example: Cola `string`
- `hierarchy4_id`: 4th level hierarchy: For Example: Pepsi cola without sugar `string`
- `hierarchy5_id`: 5th level hierarchy: For Example: Pepsi cola without sugar 300 ML `string`

`store_cities.csv`:
- `storetype_id`: Store type `string`
- `store_size`: Size of the store `float`
- `city_id`: Unique city id  `string`

### More Details

  - Dataset description at [kaggle.com](https://www.kaggle.com/berkayalan/retail-sales-data)
  - Jupyter Notebook [Data Exploration Notebook](../notebooks/1-0_data_exploration.ipynb)

[Next: 1.1 | Setup your data analysis environment](1-1_Environment-Setup.md)
