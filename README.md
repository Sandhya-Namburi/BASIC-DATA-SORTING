Basic Data Sorting & Filtering (Excel)

Sorting and filtering the Sample Superstore dataset in Excel to answer 5 simple business questions. Built as part of my Data Analytics practice track (Task 11).

Objective
Practice basic data exploration without changing the original data.

## Dataset
Sample Superstore: 9,994 order records with order ID, dates, ship mode, segment, region, category, product, sales, quantity, discount and profit.

## Questions Answered
| # | Question | Filters Used | Answer |
|---|---|---|---|
| 1 | Big Technology orders in the West region | Region = West, Category = Technology, Sales > 1000 | 60 rows, $126,674 |
| 2 | Highest single sale | Sort Sales, largest first | $22,638.48 (Cisco TelePresence System EX90) |
| 3 | Furniture lines with heavy discount that lost money | Category = Furniture, Discount >= 30%, Profit < 0 | 527 rows, $54,541 loss |
| 4 | Office Supplies sold to Corporate customers in Central | Segment = Corporate, Region = Central, Category = Office Supplies | 417 rows, $41,138 |
| 5 | Same Day shipped orders in 2017 above $200 | Ship Mode = Same Day, Order Date in 2017, Sales > 200 | 36 rows, $27,381 |

## How I Did It
- Kept the **Raw Data** sheet unchanged and worked on separate sheets
- Applied multiple filters (text, number and date filters) and sorted results
- Saved each filtered result in its own sheet (Q1 to Q5)
- Checked counts and totals with COUNTIFS and SUMIFS formulas

## Key Learnings
- Filtering hides rows without deleting them, so nothing is lost
- Keeping raw data untouched makes every result easy to re-check
- Heavy discounts on Furniture lead to many loss-making sales
- Most of the top 10 sales are Technology items

## Tools
Excel

## Files
- `Sorting_Filtering_Task11.xlsx`: workbook with Answers, Raw Data and Q1 to Q5 sheets

## Author
Sandhya Namburi
