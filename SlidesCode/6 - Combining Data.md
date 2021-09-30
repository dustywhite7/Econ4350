---
marp: true
title: Topic 6 - Combining Data Sets and Fields
theme: default
class: default
size: 4:3
---

# Combining Data Sets and Fields

---

# Data in modern business

Why is our data valuable?

---

# Open-Source and data as an asset

![bg left 100%](google_open_source.png)

---

# Business data has immense value

But sometimes we need to increase the context of our data by combining it with other data

---

# Brazilian Retail Data

The Kaggle website has [Brazilian retail data](https://www.kaggle.com/olistbr/brazilian-ecommerce#) available for us to experiment with. 

Let's combine these data sources to create insight. I have [trimmed the data down](https://github.com/dustywhite7/Econ4350/tree/master/Data/BrazilianSalesDataRS) to just Rio Grande do Sul (again) so that Power BI doesn't explode.

---

# Blend the data sources

Start with the following files:

1) customers.csv
2) geolocation.csv
3) olist_products.csv
4) product_names.csv
5) order_items.csv
6) orders.csv

---

# Blend the data sources

![](DataDiagram.png)

---

# What if we want to know more?

We could combine the data with **public microdata** to better understand our consumers in different locations!

Let's blend the sales data with our demographic data from our health care maps last week.

---

# Summary

- We can combine data sets so long as we know the common variables
- We can create combinations of fields, too!

---

# Calculated Fields and Formulas

Just like in Excel (or in any programming language!), we are able to create new fields on the fly in Power BI.

Here is a [detailed tutorial with additional links on Calculated Columns](https://docs.microsoft.com/en-us/power-bi/transform-model/desktop-tutorial-create-calculated-columns)

---

# Using Power BI

As we visualize our data, the primary limitation is our ability to imagine new ways to present the information at our finger tips!