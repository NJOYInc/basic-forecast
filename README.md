# basic-forecast

This case study is designed to understand how you think and approach problems rather than specifically assess your technical skills. You may submit your responses in any format though a Jupyter Notebook would probably best demonstrate your process. There is no time limit and you can submit your responses at your convenience.

# Objective
The csv file in this repository contains some anonymized retail sales data which captures how three different brands have performed at three different retailers through 2019-2020. We want to understand how this category might evolve in 2021 by doing some basic forecasting based on the available data. Please use the csv and any external data sets or libraries to answer the following questions.

# Questions

Based on the data attached, what do you infer are the key drivers of market share in this category? What meaningful changes do you see within the category during the time period covered by the data?

We want to set a benchmark for expected performance for 2021. Based on the attached file please predict weekly unit sales for all brands and retailers in the category combined for the first quarter of 2021.

Brand C is planning to introduce a new product configuration in 2021 with 4 units per package. Forecast the unit sales for this product at $19.99 and $14.99 unit prices.

## Data Dictionary

This is for the attached file. Every record is a weekly aggregation of sales for each brand at a retail chain.

| field                   | definition                                                                 |
|-------------------------|----------------------------------------------------------------------------|
| chain_name              | The retailer where the product was sold                                    |
| product_family          | The brand of the product                                                   |
| brand_flavor            | The flavor of the product                                                  |
| store_state             | The state where the product was sold                                       |
| week_ending             | The Saturday of the week in which the product was sold                     |
| brand_units_per_package | The number of product units within the package purchased by the customer   |
| package_sales           | The sum of packages sold to customers                                      |
| dollar_sales            | The sum of revenue associated with the package sales                       |
| selling_stores          | The unique count of stores in the chain and state where the sales occurred |

