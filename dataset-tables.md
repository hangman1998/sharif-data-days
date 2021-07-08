# Dataset Schema
## Original dataset tables
### click_log_train.json scheme:
describes the event of clicking this item in that search
|product_id|rank|search_id|date

### base_products.json
|id|category|list_of_sellers
seller: name1|name2|price|avail|date_added

### search_log_train.json
|id|query|page|list_of_product_ids|date

----
## Proposed tables
### products table
|id|image_features|BOW|lowest_available_price|num_avail_sellers

### query table
BOW_query|count|list_of_clicks
click: product_id|rank|num_of_clicks


<!-- Serpent
Ted Lasso
City on Hills
FOr All mankinf
Succession -->