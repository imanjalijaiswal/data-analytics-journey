# SQL Daily Practice

This folder documents my structured daily SQL practice as part of my Data Analytics preparation.

The exercises focus on applying SQL concepts to practical, business-oriented data analysis tasks using sales data.

## Practice Topics

- SQL fundamentals
- Data retrieval using SELECT
- Filtering data using WHERE
- Removing duplicate values using DISTINCT
- Sorting data using ORDER BY
- Limiting query results using LIMIT
- Comparison operators
- Conditional filtering
- Sales analysis
- Revenue analysis
- Product analysis
- Regional analysis
- Salesperson analysis
- Business-oriented data analysis

## Daily Practice

### Day 1 — SQL Fundamentals & Data Filtering

Practiced retrieving and filtering sales data using basic SQL queries.

Practiced:

- SELECT
- FROM
- WHERE
- DISTINCT
- Selecting specific columns
- Retrieving complete records
- Filtering data based on text values
- Filtering data based on numeric values
- Using comparison operators
- Analyzing sales by region
- Analyzing sales by salesperson
- Analyzing sales by product
- Identifying high-value orders
- Identifying low-value orders
- Filtering orders based on units sold
- Combining filtering conditions

Applied SQL queries to answer practical business questions such as:

- Which orders were generated in Kathmandu?
- Which salesperson handled specific orders?
- Which products were sold?
- Which orders generated high revenue?
- Which orders had a high number of units?
- Which orders were outside Kathmandu?
- Which products and regions are present in the dataset?

The exercise helped me understand how SQL can be used to retrieve relevant information from a database and filter transaction-level data based on business requirements.

### Day 2 — Sorting, Filtering & Limiting Results

Worked with the sales dataset and practiced organizing query results to identify important records and business information.

Practiced:

- ORDER BY
- ASC
- DESC
- LIMIT
- Sorting by revenue
- Sorting by units sold
- Sorting filtered results
- Combining WHERE with ORDER BY
- Combining ORDER BY with LIMIT
- Finding highest-value orders
- Finding lowest-value orders
- Identifying top-performing products
- Analyzing regional sales
- Analyzing high-value transactions
- Selecting top and bottom records

Applied SQL queries to answer practical business questions such as:

- Which orders generated the highest revenue?
- Which orders generated the lowest revenue?
- Which orders had the highest number of units sold?
- What was the highest-revenue order in Kathmandu?
- Which Electronics orders generated the most revenue?
- Which records should be examined when identifying top-performing sales?

The exercise helped me understand how sorting and limiting query results can be used to quickly identify important records and support business-oriented analysis.

### Day 3 — Advanced Filtering Conditions

Worked with the sales dataset and practiced using advanced filtering conditions to retrieve specific records based on multiple business requirements.

Practiced:

- Using `AND` to combine multiple conditions
- Using `OR` to match alternative conditions
- Using `IN` to filter multiple values
- Using `NOT IN` to exclude multiple values
- Using `BETWEEN` to filter numeric ranges
- Using `NOT BETWEEN` to exclude numeric ranges
- Using `LIKE` for pattern matching
- Using `NOT LIKE` to exclude text patterns
- Using `%` as a wildcard
- Using `_` as a single-character wildcard
- Combining `AND` and `OR`
- Using parentheses to control multiple conditions
- Combining filtering with `ORDER BY`
- Combining filtering with `LIMIT`
- Filtering sales by region
- Filtering sales by product
- Filtering sales by category
- Filtering sales by salesperson
- Filtering sales using revenue and units
- Solving business-oriented filtering problems

Applied these concepts to answer practical business questions such as:

- Which orders came from specific regions?
- Which orders had revenue above a specified amount?
- Which products met specific sales conditions?
- Which salespeople handled selected orders?
- Which orders fell within a specific revenue or unit range?
- Which products matched a particular text pattern?
- Which were the highest-revenue orders within selected conditions?

The exercise also introduced more realistic business-analysis queries by combining multiple filtering conditions with sorting and limiting results.

The Day 3 practice helped strengthen my ability to translate business requirements into SQL filtering conditions and retrieve only the records relevant to a particular analysis.

### Day 4 — NULL, Aliases & Data Exploration

Worked with the sales dataset and practiced handling missing data, improving query output readability, and exploring basic information about the dataset.

Practiced:

* Understanding `NULL` as a missing or unknown value
* Distinguishing `NULL` from `0` and empty text
* Using `IS NULL` to find missing values
* Using `IS NOT NULL` to find available values
* Combining `NULL` conditions with other filtering conditions
* Using `AS` for column aliases
* Using aliases with calculated columns
* Using table aliases
* Using `COALESCE()` to replace missing values when displaying results
* Understanding the difference between `IS NULL` and `COALESCE()`
* Using `COUNT(*)` to count rows
* Using `COUNT(column)` to count non-NULL values
* Using `COUNT(DISTINCT ...)` to count unique values
* Counting missing values using `COUNT()` with `IS NULL`
* Combining filtering, counting, sorting, and limiting
* Performing basic data-quality checks
* Creating business-oriented summary queries

Applied these concepts to answer practical business questions such as:

* Which orders have missing salesperson information?
* Which orders have missing product or revenue information?
* How many orders have a salesperson assigned?
* How many orders have missing sales information?
* How many unique regions, products, categories, and salespeople exist?
* How can calculated values such as profit and revenue per unit be given meaningful names?
* How can missing salesperson information be displayed as `Unknown`, `Not Assigned`, or `Unassigned`?
* Which Kathmandu orders have salesperson information available or missing?
* Which high-revenue orders have missing salesperson information?
* How can sales data be summarized for data-quality reporting?

The practice also combined concepts from previous days, using filtering conditions together with `IS NULL`, `IS NOT NULL`, `ORDER BY`, and `LIMIT`.

This exercise strengthened my understanding of missing data in SQL and helped me apply SQL concepts to basic data-quality checks and business reporting scenarios.

