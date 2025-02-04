# SQL-projects
--Order by price
Select *
From superstore
Order by price;
--Find the Sum
Select Sum(price)
From Superstore
order by stock_quantity =2135.29;
--Average price of items in Kitchen supply
Select AVG(price)
From Superstore
Where category = "Kitchen Supplies";
