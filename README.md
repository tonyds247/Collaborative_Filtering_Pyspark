# Collaborative_Filtering_Pyspark
The focus of this project is collaborative filtering, which was implemented using ALS (Alternating Least Squares) in PySpark.

Data source: Shopee ecommerce Platform


---
1st result:
- Root-mean-square error = 2.2644496107391916

---
Tuning Model:
rootmse =1.0815501961792808

Result is better

--- 
A recommend for user
Row(user_id_idx=31, recommendations=[Row(product_id_idx=24311, rating=5.205354690551758), Row(product_id_idx=24530, rating=5.156948566436768), Row(product_id_idx=21747, rating=5.105452060699463), Row(product_id_idx=23243, rating=5.101497173309326), Row(product_id_idx=29670, rating=5.064798831939697), Row(product_id_idx=17271, rating=5.025424957275391), Row(product_id_idx=18881, rating=5.009730339050293), Row(product_id_idx=21690, rating=5.002012252807617), Row(product_id_idx=27479, rating=4.996496200561523), Row(product_id_idx=20285, rating=4.994470119476318)])
