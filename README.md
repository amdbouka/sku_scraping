# sku_scraping
Replace 'products.csv' with the path to your input CSV file containing the SKUs.<br>
Replace 'products_with_description.csv' with the desired name for your output CSV file.<br>
The script reads the SKUs from the CSV file and stores them in the sku_list.<br>
For each SKU, it calls the get_product_description function to retrieve the product description and stores it in the descriptions dictionary.<br>
Finally, it writes the SKU-description pairs to the output CSV file. Each row in the output CSV file will contain the SKU and its corresponding description.<br>
