# USTACKY PANDAS PROJECT

## DATA ANALYSIS ON  XYZ SUPERMARKET

Company XYZ owns a supermarket chain across, with its major branch located in three(3) cities Abuja, Lagos and Portharcourt with the followong product lines; electrical accessories, Electronic accessories, Home and lifestyle, Food and beverages, Sports and travel, Health and beauty, Fashion accessories. Descriptive Data Analysis was performed on the gathered data from all three branches and insights are generated to help understand trends and determine growth. 

## Project Steps

In the course of the analysis the following steps were taken before and during the analysis; 
1). First, i looked at the description of each feature in other to understand the concept of the supermarket and pinpoint probably areas of interest of the enterprise towards its growth and deployment of effiecient business management

2). Secondly i took a short statistical summary of the data that was gathered from the three main branches and drew a brief insight of it.

3). Moving on, i checked for missing values and noted my observation on that and i checked the current state(datatype) of all the columns using the info() attribute

4). Next up i did a few breakdown of some columns that were meant to have been in datetime format, hence the process of datatype conversion was initiated afterwhich hours, days, weeks and months were extracted from the datetime columnsto the end that more detailed information about periodical trends are obtained

5). Unique values in all categorical features were obtained

6). Performed groupby categorization and aggregation on the data, other columns by city and other columns

7). Lastly i implemented matplotlib and seaborn for the visualization of the data both inferential and descriptive. The visualization is compressed into three parts:
	a). Trend Identification
	b). Correlation
	c). Distribution


## Insights

1). The data was properly collate as there were no missing values or outliers

2). The approximate average unit price and quantity are #20,000 and 6 units respectively making our total sales/revenue to be around #120,000 without incurring tax.
The tax on the supermarket is about 4.5% of the total sales
After accounting for tax the average total value is found to be around #116,000.
Knowing that the average cost of goods sold is apporximately #110,700 and the gross income is approximately #5537 it informs us that the average sales made within the timeframe is about #115,000 

3). The average rating is 6.97 indicating that the supermarket is doing slightly better above average implying that more work needs to be done to improve tghe companies services and products availability to customers

4). All the data are filled with inputs and hence there are no null or empty data cells in the columns

5). We can say inferentially that Port Harcourt has the highest total gross income with Abuja being the second and then Lagos.

6). The city with the highest average rating is and the City with the highest average rating is PortHarcourt with Lagos being the next in line followed by Abuja.

7). The branch with the highest average rating is and the City with the highest average rating is branch C with branch B being the next in line followed by branch A.

8). A large percent of the electrical accessories were paid for using cash channel

9). For home and lifestyle product lines it was majorly purchased using Epay

10). There is a fine distribution of the payment channels used for the food and beverages product line

11). Sports and travel have majority of their products paid in cash

12). Most of the customers purchase for health and beauty products were paid with using Epay

13). A very large amount of the Fashion accessories were paid for using Epay

14). Food And Beverages are sold most in Port-Harcourt

15). Fashion accessories are also sold most in Port-Harcourt

16). Lagos has the highes purchase for electronic equipments

17). Sports and travel products were mostly sold at Abuja

18). Home and lifestyle commoditites are heavily purchased in Lagos

19). All three states have an approximate equal number of sales for health and beauty commodities

20). The supermarket should focus on increasing it marketing strategy for sales of health and beauty products especially in lagos which has high potential yield rate

21). In other for the Branch at portharcourt to do better the sales management should work on generating more incoming through sports and travel, home, and lifestyle commodities. 

22). More efforts need to be put in the Lagos fashion accessory fraction

23). Relative to Lagos and Port Harcourt Abuja branch hasn't been doing well sales wise as regars the yield in sales for the food, beverage, home, lifestyle, health and beauty hence more attention should be given to these areas

24). This indicates that there is high variance in the correlation between the cost of goods sold and the total amount generated

25). Dominant female activity in branch A and B while the men seem to be slightly higher than the females at Branch C

## Future Work

In other to make the work look more robust tasks like the following should have been carried out:
a). Deeper Visualisation
b). Predictive Analytics
c). Addition more features/columns
d). Addition of more financaial columns for a much more economic descriptive analytics


## Standout Section

I did a groupby categorization of the areas with the most rating
I performed a distribution visualisation of sales by gender to see the volume of the total amount contributed by respective gender. It was discovered that  
In the latter parts of the analysis i compared other features to an important column 'RATING' which was not given in the project requirement. I thought it to be crucial to know the reaction of the branches to proucts and services provided, rating based on product line.
