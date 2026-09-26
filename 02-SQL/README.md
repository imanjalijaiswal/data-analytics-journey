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

### Day 5 — GROUP BY & Aggregate Analysis

Worked with the sales dataset and practiced summarizing data using `GROUP BY` and aggregate functions to answer business-oriented analysis questions.

Practiced:
- Using `GROUP BY` to create groups from related records
- Using `COUNT()` to count orders and values
- Using `SUM()` to calculate total revenue, units, and cost
- Using `AVG()` to calculate average revenue and units
- Using `MIN()` to find minimum values
- Using `MAX()` to find maximum values
- Combining multiple aggregate functions in a single query
- Grouping data using multiple columns
- Grouping sales by region, product, category, and salesperson
- Using `WHERE` before `GROUP BY` to filter individual records
- Using `HAVING` to filter grouped results
- Understanding the difference between `WHERE` and `HAVING`
- Combining `WHERE`, `GROUP BY`, and `HAVING`
- Sorting aggregated results using `ORDER BY`
- Limiting grouped results using `LIMIT`
- Working with `NULL` values inside grouped results
- Using `COALESCE()` with grouped data
- Creating regional, product, category, and salesperson performance summaries
- Solving analyst-oriented aggregation problems

Applied these concepts to answer practical business questions such as:
- How many orders came from each region?
- How many orders were handled by each salesperson?
- Which products generated the most revenue?
- What was the average revenue per order in each region?
- What were the minimum and maximum revenue values for each product?
- How many units were sold for each product?
- How did revenue vary across regions and products?
- Which regions generated more than a specified amount of total revenue?
- Which products or salespeople handled more than a specified number of orders?
- Which regions had high total revenue after applying row-level filters?
- Which products had high sales volume and revenue?
- What were the top and bottom regions, products, and salespeople based on aggregated metrics?

The practice also introduced more advanced business-analysis queries by combining row-level filtering with grouping, aggregation, group-level filtering, sorting, and limiting.

The Day 5 challenges focused on creating complete business reports for regional and product performance and applying multiple aggregate functions together.

This exercise strengthened my ability to summarize transactional data and convert individual sales records into meaningful business-level insights using SQL aggregation.


### Day 6 — Advanced Aggregate Analysis

Worked with the sales dataset and practiced advanced aggregate analysis by combining `GROUP BY`, aggregate functions, filtering, `HAVING`, sorting, and limiting to answer more complex business questions.

Practiced:

* Using multiple aggregate functions in a single query
* Using `COUNT()` to calculate total orders
* Using `SUM()` to calculate total units and revenue
* Using `AVG()` to calculate average revenue
* Using `MIN()` and `MAX()` to identify minimum and maximum values
* Grouping data using multiple columns
* Grouping sales by region, product, category, and salesperson
* Analyzing region-product combinations
* Analyzing category-region combinations
* Using `WHERE` before `GROUP BY` to filter individual records
* Using `HAVING` to filter aggregated groups
* Combining `WHERE`, `GROUP BY`, and `HAVING`
* Using `ORDER BY` to rank aggregated results
* Using `LIMIT` to retrieve top and bottom results
* Finding top products, regions, categories, and salespeople based on aggregated metrics
* Excluding missing salespeople from performance analysis
* Calculating revenue per unit
* Creating regional performance summaries
* Creating product performance summaries
* Creating salesperson performance summaries
* Solving analyst-oriented aggregation problems
* Translating business requirements into multi-step SQL queries

Applied these concepts to answer practical business questions such as:

* How many orders, units, and revenue came from each region?
* What was the average, minimum, and maximum revenue for each region?
* How did sales performance vary across region and product combinations?
* Which regions generated more than a specified amount of revenue?
* Which products generated more than a specified amount of revenue?
* Which salespeople handled more than a specified number of orders?
* Which products had an average revenue above a specified threshold?
* Which categories sold more than a specified number of units?
* Which were the top and bottom products by total revenue?
* Which regions had the highest total units sold?
* Which salespeople generated the highest total revenue?
* Which region-product combinations generated the highest revenue?
* Which products met multiple performance requirements involving orders, units, and revenue?

The practice also focused on combining row-level and group-level conditions. Queries were built using `WHERE` to filter individual sales records before grouping and `HAVING` to filter the resulting aggregated groups.

Business-oriented exercises included creating:

* Regional performance reports
* Product performance reports
* Salesperson performance reports
* High-value regional analysis
* Product filtering based on multiple performance conditions
* Regional, product, and salesperson performance challenges

The Day 6 challenges required combining multiple SQL concepts in a single query, including filtering, grouping, aggregation, `HAVING`, sorting, and limiting results.

This exercise strengthened my ability to move from simple aggregation to more realistic analytical SQL queries and to translate multi-condition business requirements into structured SQL analysis.


### Day 7 — String Functions & Text Data Cleaning

Worked with the sales dataset and practiced using SQL string functions to transform, clean, standardize, combine, and analyze text data.

Practiced:

* Using `CONCAT()` to combine multiple text values
* Using `CONCAT_WS()` to combine text values with a separator
* Handling `NULL` values when combining text
* Using `COALESCE()` with string functions
* Using `UPPER()` to standardize text into uppercase
* Using `LOWER()` to standardize text into lowercase
* Using `TRIM()` to remove leading and trailing spaces
* Using `LTRIM()` to remove leading spaces
* Using `RTRIM()` to remove trailing spaces
* Using `LENGTH()` to calculate string length in bytes
* Using `CHAR_LENGTH()` to calculate character count
* Using `LEFT()` to extract characters from the beginning of a string
* Using `RIGHT()` to extract characters from the end of a string
* Using `SUBSTRING()` to extract specific portions of text
* Using `REPLACE()` to replace text values
* Combining multiple string functions for data cleaning
* Using string functions inside `WHERE` conditions
* Using transformed text with `ORDER BY`
* Grouping data using transformed text with `GROUP BY`
* Creating cleaned and standardized text labels
* Handling missing salesperson information while creating text outputs

Applied these concepts to answer practical data-cleaning and text-analysis questions such as:

* How can region and product information be combined into a readable sales label?
* How can multiple text columns be combined using a consistent separator?
* How can product and region names be standardized using uppercase or lowercase formatting?
* How can unnecessary spaces be removed from text values?
* How can the length and character count of text values be analyzed?
* How can specific characters be extracted from product, region, and salesperson names?
* How can portions of text be extracted using `SUBSTRING()`?
* How can text values be replaced or standardized using `REPLACE()`?
* How can missing salesperson values be displayed as `UNASSIGNED`?
* How can cleaned text be used for grouping and reporting?
* How can multiple string functions be combined to create standardized business labels?

The practice also combined string functions with concepts learned in previous days, including `WHERE`, `GROUP BY`, `ORDER BY`, `COUNT()`, `SUM()`, aliases, `NULL` handling, and `COALESCE()`.

Analyst-oriented exercises focused on product standardization, regional analysis, salesperson reporting, product text analysis, and creating standardized sales labels.

The challenges extended these concepts into practical reporting tasks by combining text cleaning with sales information, performance metrics, grouping, and sorting.

This exercise strengthened my understanding of SQL text manipulation and introduced an important data-analytics workflow: taking raw text, cleaning and standardizing it, transforming it into useful reporting fields, and then using the cleaned values for analysis.



### Day 8 — Numeric Functions & Calculated Fields

Worked with the sales dataset and practiced using SQL arithmetic operations, numeric functions, and calculated fields to create useful business metrics from existing sales data.

Practiced:

* Creating calculated fields from existing columns
* Using arithmetic operators such as `+`, `-`, `*`, `/`, and `%`
* Calculating revenue per unit
* Using `ROUND()` to control decimal places
* Using `FLOOR()` to round values down
* Using `CEIL()` to round values up
* Using `TRUNCATE()` to remove decimal places without rounding
* Using `ABS()` to calculate absolute differences
* Using `MOD()` to calculate remainders
* Identifying even and odd unit values
* Calculating percentage contributions
* Calculating discount amounts
* Calculating revenue after discounts
* Calculating tax amounts
* Calculating final amounts after tax
* Combining numeric calculations with `ROUND()`
* Using calculated fields with `WHERE`
* Using calculated fields with `ORDER BY`
* Using calculated fields with `GROUP BY`
* Using calculated fields with `HAVING`
* Creating multiple calculated metrics in a single query
* Understanding the difference between a calculated field and an actual table column
* Using `NULLIF()` to handle potential division-by-zero situations
* Combining numeric calculations with aggregation functions such as `SUM()`, `COUNT()`, and `AVG()`

Applied these concepts to answer practical business questions such as:

* What is the revenue generated per unit for each order?
* Which orders have the highest or lowest revenue per unit?
* Which orders have an even or odd number of units?
* How much discount would be applied to an order at a specified discount rate?
* What would the revenue be after applying a discount?
* How much tax would be added to an order?
* What would the final amount be after applying tax?
* How far is each order's revenue from a specified target?
* Which products generate the highest revenue per unit?
* Which regions generate the highest revenue per unit?
* Which salespeople generate more than a specified amount of total revenue?
* Which products meet multiple performance requirements involving orders, units, revenue, and revenue per unit?

The practice also strengthened the use of calculated fields together with previously learned SQL concepts such as `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`, `NULL`, and aggregate functions.

A major focus of the practice was understanding the difference between calculating a metric at the individual-row level and calculating it after grouping.

The analyst-oriented exercises focused on creating:

* Product performance reports
* Regional performance reports
* Salesperson performance reports
* Revenue-per-unit analysis
* Discount and tax calculations
* High-value product analysis
* Regional revenue analysis
* Salesperson performance analysis
* Multi-condition business reports

The challenges required combining multiple SQL concepts in a single query, including aggregation, calculated fields, `HAVING`, sorting, limiting, and filtering missing salesperson information.

This exercise strengthened my ability to create business metrics from raw numerical data and helped me move from basic SQL calculations toward more realistic analytical queries and performance reports.


### Day 9 — CASE Expressions & Conditional Analysis

Worked with the sales dataset and practiced using SQL `CASE` expressions to apply conditional logic, classify data, create calculated results, and perform conditional analysis.

Practiced:

* Using `CASE` expressions to create conditional results
* Using `WHEN`, `THEN`, and `ELSE`
* Understanding how `CASE` evaluates multiple conditions
* Understanding the importance of condition order in `CASE`
* Using simple `CASE` expressions
* Using searched `CASE` expressions
* Using multiple conditions inside `CASE`
* Creating text categories using `CASE`
* Creating numeric results using `CASE`
* Using `CASE` with calculated fields
* Using `CASE` with `NULL` values
* Using `CASE` with `GROUP BY`
* Using `CASE` with aggregate functions
* Using `CASE` with `SUM()` for conditional aggregation
* Counting records based on conditions using `SUM(CASE...)`
* Calculating conditional revenue using `SUM(CASE...)`
* Using `CASE` with `ORDER BY`
* Calculating percentages using conditional aggregation
* Understanding the difference between `CASE` and `WHERE`
* Understanding the difference between `CASE` and `COALESCE()`
* Using aliases for `CASE` results
* Creating performance categories
* Creating business-oriented conditional reports
* Combining `CASE` with previously learned SQL concepts

Applied these concepts to answer practical business questions such as:

* How can orders be classified as high, medium, or low value?
* How can sales regions be classified based on total revenue?
* How many high-value, medium-value, and low-value orders exist?
* How much revenue comes from different order categories?
* Which products meet specific revenue and performance conditions?
* Which salespeople meet specific performance requirements?
* How can missing salesperson information be handled using conditional logic?
* How can products be classified based on revenue per unit?
* What percentage of orders in each region are high-value orders?
* What percentage of a product's revenue comes from high-value orders?
* Which categories or regions generate the highest revenue?
* How can a salesperson's performance be classified based on total revenue?
* How can multiple business conditions be combined into one performance report?

The practice also focused on understanding how `CASE` works at different levels of analysis. `CASE` can be used to classify individual rows, perform conditional aggregation, or create categories from already aggregated results. MySQL evaluates the `WHEN` conditions and returns the result for the first condition that is true.


The practice also strengthened the understanding of percentage calculations using conditional aggregation. 
The analyst-oriented exercises focused on creating:

* Order classification reports
* Regional revenue classification
* Product performance reports
* Salesperson performance reports
* High-value order analysis
* Conditional revenue analysis
* Conditional order-count analysis
* Revenue contribution percentages
* Product performance categories
* Regional performance categories
* Multi-condition business reports

The Day 9 challenges required combining multiple SQL concepts in a single query, including `CASE`, aggregate functions, calculated fields, `HAVING`, sorting, and filtering.

This exercise strengthened my ability to use SQL conditional logic for business analysis and helped me move from simply retrieving and aggregating data toward creating meaningful classifications, performance categories, conditional metrics, and business-oriented reports.

