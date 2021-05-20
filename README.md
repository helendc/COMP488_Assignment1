# Task
Provided with transactional data from a small business owner, we give a data-driven business recommendation to help the coffee shop's profitabliity. Our analysis is focused in the following areas:
>- retaining customers
>- increasing daily transactions
>- managing a rather large assortment of products 

# Process
1. Data Cleaning 
> - remove unnecessary columns 
> - format dataframe with DateTimeIndex
> - convert dtypes of Discount and Gross Sales columns 
2. Data Wrangling
> - sort items into more informative categories we defined
> - determine cost of all items for the store, create a column for cost
> - create a profit column (profit = gross sales - cost + discounts)
3. Analysis of Gross Sales and Profit 
4. Analysis of Cost and Revenue
5. Analysis of Consumer Preferences and its seasonal dependency

# Conclusions
**Recommendation 1: Cut the size of the menu (seasonally)**
> We recommend that the coffee shop adjusts their menu by season to account for changing popularity of their items. It is demonstrable that the following items become more popular (higher average daily sales) during the respective seasons:
> 1. Hot coffee in winter
> 2. Tea in winter
> 3. Cold coffee in summer
> 4. Lattes in the fall

**Recommendation 2: Coffee of the day recommendations**
> Check the preferred coffee for the weekday, weekend, and by season. When looking at the total sales of coffee of the day compared to the total profits it produces, it becomes clear that there is a large portion of profits that are being missed out on with the coffee of the day. We recommend raising the price for the coffe that peaks during these times to increase profits per sale of one of the largest sellers that produces shockingly low profits comparatively.
> Monday is not a top performing day in any category. Promoting a fun and festive coffee of the day on Monday could be especially useful for driving traffic, since CotD is popular throughout the week.
