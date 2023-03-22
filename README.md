# ZARA_us_python_project
This is a python-pandas project based on ZARA US fashion products dataset.

***About this project: Zara is one of the biggest international fashion companies, and it belongs to Inditex, one of the world's largest distribution groups. In this project, I will analyze ZARA fashion products dataset in the US region. The data set is sourced from the Kaggle website. The platform I chose for this project is Python-pandas.
![image](https://user-images.githubusercontent.com/123319398/226766685-58a5b89a-e1ca-4102-8756-e5469560b2dc.png)


**Step 1 -  Looking at the type of data: The dataset is in “json” file format.  Firstly, I will import all the essential directories in the jupyter notebook, and then read the json data file and create a data frame for the analysis. The fields are url, name, sku, mpn, language, description, brand, price, currency, size_list, availability, images, condition, color, scraped_at.

![image](https://user-images.githubusercontent.com/123319398/226768035-402ecf13-0df8-4ea2-9b4c-fb4fcdfb98bc.png)


**Step 2 – Transformation/ Cleaning of data : 
•	Deleting a column ’mpn’ as it had the same data in ‘sku’ column.
•	Checking and dropping null values
•	Converting datatype of ‘price’ column from float to integer for future reference
•	Replacing ‘’ with ‘out of stock’ value in ‘availability’ column

![image](https://user-images.githubusercontent.com/123319398/226768096-6236ddd1-fe2d-4d37-b899-2bf9afd00010.png)


**Step 3 – Questions to analyze the data : After preparing the data, I shortlisted following business questions to understand the data:
•	Find the highest and lowest priced item?
•	Show/plot the top 5 and bottom 5 products on the basis of price in a graph?
•	Find how many products are InStock?
•	Plot a pie chart to show the percentage of availability of the items?
•	Plot the graph with the number of products in ‘ZARA’ and ‘ZARAHOME’ brand?

![image](https://user-images.githubusercontent.com/123319398/226768567-84fef20d-4fd2-4369-8c21-6cd4438a8d99.png)


**Step 4 – Visualize the data : For visualization, I used vertical bar graph, horizontal bar graph and a pie chart for showing the distribution of data. I also used different types of font colors and colors on bar to highlight the key areas.

![image](https://user-images.githubusercontent.com/123319398/226768158-9e1a8842-8698-4230-972c-f421b1c0f3e6.png)

![image](https://user-images.githubusercontent.com/123319398/226769038-43442fc7-6913-4d56-9da4-fe9de8c579e5.png)



***Findings and Conclusions : After analysing the data, I found out that Jute Rug is the most expensive product in all the categories, which is priced at $449. It was evident that 84% products were In-stock. Zara brand has 1270 products while Zara Home brand has 246, which means Zara does not sell more Home products than fashion products.
