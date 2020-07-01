# Shopee Code League 2020 - Order-Brushing (Challenge #1)

This my first attempt participating in a data analytics competition and also my first notebook that I publish online.

Overview on the challenge : 
Abnormal user behaviours on e-commerce platform can be detected in various ways. For example, if an item in a shop is a best seller but many of tis orders come from the same buyer, we have a reason to suspect that the seller is conducting order brushing. Order Brushing is a technique that may be employed by sellers to create fake orders so as to inflate a particular item's rating.

Task : 
1. Identify all shops that are deemed to have conducted order brushing
2. For each shope identified, find the buyer(s) who are suspected to have conducted order brushing for that shop

For the purpose of this challenge, shops are deemed to have conducted if their concentrate rate is greater than or equal to 3 at any instance

Concentrate rate = No. of orders within 1 hour/ Number of unique buyers within 1 hour

For the purpose of this challenge, suspicious buyers are the one who contributed the highest proportion of orders to a shop that has been deemed to have conducted order brushing. In the case where there are more than 1 suspicious buyers, all those users have to be identified and recorded.

Input data description (order.csv) : 
- Each orderid represents a distinct transaction
- Each unique shopid is a distinct seller
- Each unique user is a distinct buyer
- Event Time is the exact time that an order was made
