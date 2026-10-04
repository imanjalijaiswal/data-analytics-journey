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


### Day 10 — JOINs & Combining Tables

Worked with the sales and products datasets and practiced using SQL `JOIN` operations to combine information from multiple tables and perform more advanced business analysis.

Practiced:

* Understanding why `JOIN` operations are needed
* Understanding relationships between tables
* Using `INNER JOIN` to combine matching records
* Using `LEFT JOIN` to keep all records from the left table
* Understanding the difference between `INNER JOIN` and `LEFT JOIN`
* Finding unmatched records using `LEFT JOIN` and `IS NULL`
* Using `RIGHT JOIN`
* Understanding the concept of `FULL OUTER JOIN`
* Understanding `CROSS JOIN` and Cartesian products
* Using table aliases to make JOIN queries easier to read
* Using the `ON` condition to define relationships between tables
* Joining tables using a common product field
* Combining `JOIN` with `WHERE`
* Combining `JOIN` with `ORDER BY`
* Combining `JOIN` with `LIMIT`
* Creating calculated fields using columns from multiple tables
* Calculating estimated product cost using units and unit cost
* Calculating estimated profit using revenue and product cost
* Calculating revenue per unit
* Using `JOIN` with `GROUP BY`
* Using multiple aggregate functions after joining tables
* Using `JOIN` with `HAVING`
* Using `JOIN` with `CASE`
* Creating category-level and product-level performance reports
* Understanding which table should be used as the left table
* Identifying ambiguous columns when multiple tables contain similar field names
* Understanding the JOIN mental model
* Combining JOINs with previously learned SQL concepts

Applied these concepts to answer practical business questions such as:

* How can sales records be combined with product information?
* How can product category and unit cost be added to sales data?
* Which high-revenue orders belong to specific product categories?
* How can sales for selected products be analyzed using information from another table?
* How can all sales records be retained even when product information is missing?
* Which sales records do not have a matching product in the product master table?
* Which products exist in the product master table but have no sales?
* How can estimated product cost be calculated using information from two tables?
* How can estimated profit be calculated using revenue and product unit cost?
* Which orders have the highest estimated profit?
* How much revenue is generated by each product category?
* Which products generate the highest total revenue or sales volume?
* Which categories meet specific revenue and order requirements?
* Which products meet specific order, unit, and revenue thresholds?
* How can products and categories be classified using `CASE` based on their performance?
* What percentage of category revenue comes from high-value orders?
* How can a complete product performance report be created using multiple SQL concepts?

The practice also strengthened the use of previously learned SQL concepts such as `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`, aggregate functions, calculated fields, `CASE`, and `NULL` handling.

A major focus of Day 10 was understanding how information is distributed across different tables. For example, the `sales` table contains transaction-level information such as orders, units, and revenue, while the `products` table contains product-level information such as category and unit cost. `JOIN` allows these pieces of information to be combined for analysis.

The practice also introduced the importance of choosing the correct JOIN type. `INNER JOIN` returns matching records from both tables, while `LEFT JOIN` keeps all records from the left table even when a matching record does not exist in the right table. This makes `LEFT JOIN` particularly useful for identifying missing or unmatched records during data-quality analysis.

The analyst-oriented exercises focused on creating:

* Sales and product information reports
* Product matching and data-quality reports
* Product cost and estimated profit analysis
* Product-level performance reports
* Category-level performance reports
* High-revenue and high-volume analysis
* Revenue-per-unit analysis
* Conditional performance classifications
* High-value revenue contribution analysis
* Multi-condition business reports

The Day 10 challenges required combining multiple SQL concepts in a single query, including `JOIN`, aggregation, calculated fields, `HAVING`, `CASE`, sorting, and filtering.

This exercise strengthened my ability to work with relational data across multiple tables and helped me move from analyzing a single sales table toward more realistic data-analytics queries involving table relationships, data-quality checks, calculated business metrics, and multi-table performance reporting.



### Day 11 — Multiple-Table JOINs

Practiced combining information from multiple related tables using SQL JOINs.

The exercises focused on understanding how tables are connected, building multi-table queries step by step, filtering joined data, performing grouped analysis, and identifying data-quality issues.

Practiced:

- Understanding why multiple-table JOINs are needed
- Identifying which table contains each required piece of information
- Building JOIN queries one table at a time
- Joining three tables
- Joining four tables
- Using table aliases
- Qualifying columns using table aliases
- Understanding different JOIN relationships
- Using multiple JOIN conditions
- Using JOIN with WHERE
- Filtering data using columns from different tables
- Using JOIN with ORDER BY
- Using JOIN with calculated fields
- Calculating estimated cost using columns from different tables
- Calculating estimated profit using joined data
- Using JOIN with GROUP BY
- Grouping by columns from different tables
- Using multiple aggregate functions with JOINs
- Using JOIN with HAVING
- Filtering grouped results using aggregate conditions
- Using CASE with grouped JOIN results
- Combining multiple LEFT JOINs
- Mixing INNER JOIN and LEFT JOIN
- Understanding how LEFT JOIN preserves unmatched records
- Identifying missing product and customer records
- Understanding correct JOIN relationships
- Avoiding incorrect JOIN conditions
- Understanding one-to-one and one-to-many relationships
- Understanding how JOINs can multiply rows
- Building a relationship map before writing a JOIN
- Using multiple tables for business-oriented analysis

Applied multiple-table JOINs to answer business questions such as:

- Which product category belongs to each sale?
- Which customer and city are associated with each order?
- Which salesperson handled each order?
- Which high-value Electronics sales came from Kathmandu customers?
- How much revenue was generated by each customer city and product category?
- Which city-category combinations had at least 3 orders and more than ₹150,000 revenue?
- How can all sales be preserved even when related information is missing?
- Which sales contain missing product or customer master-data records?
- What is the estimated cost and estimated profit of each sale?

The practice helped me move from joining two tables to building structured multi-table queries and understanding how JOINs interact with filtering, aggregation, HAVING, calculated fields, and data-quality analysis.

It also strengthened the ability to think about a database as a set of related tables rather than treating each table as an isolated dataset.


### Day 12 — Subqueries

Practiced using SQL subqueries to solve analytical and business-oriented problems where one query depends on the result of another query.

The exercises focused on understanding inner and outer queries, comparing individual records against calculated benchmarks, working with multiple returned values, checking whether related records exist, and performing multi-level analysis using derived tables.

Practiced:

- Understanding subqueries
- Understanding inner queries and outer queries
- Understanding scalar subqueries
- Using aggregate functions inside subqueries
- Using subqueries with WHERE
- Comparing individual values against aggregate results
- Using AVG() with subqueries
- Using MAX() with subqueries
- Using MIN() with subqueries
- Using SUM() with subqueries
- Using IN with subqueries
- Using NOT IN with subqueries
- Using ANY with subqueries
- Using ALL with subqueries
- Understanding the difference between ANY and ALL
- Using EXISTS with subqueries
- Using NOT EXISTS with subqueries
- Understanding correlated subqueries
- Comparing each row against a group-specific average
- Comparing each customer's sales against their own average
- Finding customer-specific maximum values
- Using subqueries with multiple tables
- Using subqueries instead of JOINs for selected problems
- Using subqueries in the FROM clause
- Creating derived tables
- Performing multi-level aggregation
- Calculating customer-level revenue before calculating an overall customer average
- Filtering aggregated results using an outer query
- Combining multiple subqueries in one query
- Using subqueries for business benchmarks
- Understanding relationships between columns when using subqueries

Applied subqueries to answer business questions such as:

- Which sales are above the overall average revenue?
- Which sale has the highest revenue?
- Which sale has the lowest revenue?
- Which orders have above-average units?
- Which sales belong to customers from Kathmandu?
- Which sales belong to non-Kathmandu customers?
- Which sales contain products belonging to the Electronics category?
- Which orders contribute more than 10% of total company revenue?
- Which sales have revenue greater than every Electronics sale?
- Which sales have revenue greater than at least one Electronics sale?
- Which customers have made at least one purchase?
- Which customers have never made a purchase?
- Which sales are above their own customer's average revenue?
- Which sale is the highest-value sale for each customer?
- What is the total revenue generated by each customer?
- Which customers have total revenue above the average customer revenue?
- Which orders satisfy multiple business conditions using subqueries?

The practice helped me understand how subqueries can be used to break complex analytical problems into smaller logical steps.

It also strengthened my understanding of the difference between:

- Overall averages and group-level averages
- Single-value and multi-value subqueries
- IN, ANY, and ALL
- EXISTS and NOT EXISTS
- Independent and correlated subqueries
- Row-level analysis and multi-level aggregation

The exercises built on the JOIN concepts from Day 11 and introduced another important SQL technique for solving analytical and business problems.


### Day 13 — CTEs

Practiced using SQL Common Table Expressions (CTEs) to organize complex analytical queries into smaller, named steps.

The exercises focused on understanding how CTEs work, creating intermediate result sets, performing aggregations, filtering calculated results, using multiple CTEs, joining CTEs with existing tables, and building multi-step business analysis pipelines.

Practiced:

* Understanding Common Table Expressions (CTEs)
* Using the `WITH` clause
* Creating named CTEs
* Understanding the scope of a CTE
* Understanding that CTEs exist only for the current SQL statement
* Using CTEs as intermediate result sets
* Selecting data from a CTE
* Filtering CTE results
* Sorting CTE results
* Using aggregate functions inside CTEs
* Using `SUM()` with CTEs
* Using `COUNT()` with CTEs
* Using `AVG()` with CTEs
* Using `MAX()` with CTEs
* Using `GROUP BY` inside CTEs
* Using `CASE` expressions inside CTEs
* Classifying sales based on revenue
* Creating customer-level revenue summaries
* Creating regional performance summaries
* Creating category-level performance summaries
* Creating product-level performance summaries
* Creating salesperson performance summaries
* Using CTEs with multiple calculations
* Using CTEs with `JOIN`
* Joining CTE results with existing database tables
* Using multiple CTEs in the same query
* Joining results from multiple CTEs
* Allowing one CTE to use an earlier CTE
* Building multi-step analytical pipelines
* Using CTEs to simplify nested subqueries
* Comparing CTEs with subqueries and derived tables
* Understanding CTEs versus temporary tables
* Using CTEs for business-oriented analysis
* Working with customer revenue and order metrics
* Comparing aggregated customer results
* Analyzing regional and category performance
* Building customer performance reports
* Understanding the basic idea of recursive CTEs

Applied CTEs to answer business questions such as:

* Which sales are high-value sales?
* Which sales are above the overall average revenue?
* How should sales be classified based on revenue?
* What is the total revenue generated by each customer?
* Which customers generated more than a specified revenue amount?
* How can customers be classified based on their total revenue?
* What is the revenue and unit performance of each region?
* Which regions have revenue above the average regional revenue?
* How are different product categories performing in terms of revenue, cost, profit, and units?
* What is the revenue and order performance of each customer?
* How are salespeople performing based on revenue, profit, units, and order count?
* How are products performing based on revenue, profit, units, and orders?
* How can multiple CTEs be combined to create a customer performance summary?
* Which customers have revenue above the average customer-level revenue?
* Which high-value customers also have multiple orders?
* Which products generate higher levels of profit?
* Which salespeople perform above the average salesperson-level revenue?
* How does revenue vary across region and category combinations?
* Which high-value customers generated the highest individual sales?
* How can multiple CTEs be combined to create a complete customer performance report?

The practice helped me understand how CTEs can break complex SQL problems into clear analytical steps instead of putting all logic into deeply nested queries.

It also strengthened my understanding of the difference between:

* Row-level calculations and group-level calculations
* Average individual sales and average group totals
* CTEs and subqueries
* CTEs and derived tables
* CTEs and temporary tables
* Single CTEs and multiple CTEs
* Independent CTEs and CTEs that depend on earlier CTEs
* Intermediate calculations and final filtering
* Individual records and aggregated business metrics

The exercises also reinforced the importance of using the correct relationships when joining tables and CTEs, as well as calculating business metrics such as profit using the correct revenue and cost relationship.

The practice built on the subquery concepts from Day 12 and introduced CTEs as a cleaner way to organize multi-step SQL analysis and business-oriented queries.


### Day 14 — Window Functions

Practiced using SQL Window Functions to perform analytical calculations across related rows while keeping the individual records in the result.

The exercises focused on understanding how window functions differ from `GROUP BY`, using the `OVER()` clause, dividing calculations into partitions, ranking records, calculating running totals and averages, comparing sequential rows, and combining window functions with CTEs for more advanced analysis.

Practiced:

* Understanding SQL Window Functions
* Understanding the `OVER()` clause
* Using aggregate functions as window functions
* Using `SUM()` as a window function
* Using `AVG()` as a window function
* Using `MAX()` as a window function
* Using `MIN()` as a window function
* Using `COUNT()` as a window function
* Understanding the difference between `GROUP BY` and Window Functions
* Understanding how Window Functions keep individual rows
* Using `PARTITION BY`
* Understanding how partitions divide rows for analytical calculations
* Using `ORDER BY` inside the `OVER()` clause
* Understanding the difference between Window `ORDER BY` and final `ORDER BY`
* Using `ROW_NUMBER()`
* Using `RANK()`
* Using `DENSE_RANK()`
* Understanding how `ROW_NUMBER()`, `RANK()` and `DENSE_RANK()` handle ties
* Ranking records across the complete sales dataset
* Ranking sales separately within each salesperson
* Creating running totals
* Creating running totals for the complete company
* Creating running totals separately for each salesperson
* Creating running averages
* Using `LAG()` to access previous rows
* Using `LEAD()` to access following rows
* Comparing the current sale with the previous sale
* Calculating revenue changes between consecutive sales
* Comparing individual sales with salesperson-level metrics
* Comparing individual sales with customer-level metrics
* Calculating each sale's contribution to customer revenue
* Calculating each sale's contribution to company revenue
* Using CTEs with Window Functions
* Filtering Window Function results using CTEs
* Finding the highest-value sale for each salesperson
* Finding the top sales for each salesperson
* Building multi-step analytical reports
* Combining multiple Window Functions in one query

Applied Window Functions to answer business questions such as:

* What is the overall average revenue across all sales?
* How does each sale compare with the company's average revenue?
* What is the total company revenue shown beside every individual sale?
* What is the total revenue generated by each salesperson?
* How many orders has each salesperson handled?
* How does every sale rank based on revenue?
* What is the difference between `ROW_NUMBER()`, `RANK()` and `DENSE_RANK()`?
* What is the rank of each sale within its salesperson?
* What is the highest-revenue sale for each salesperson?
* What is the running company revenue over time?
* What is the running revenue for each salesperson?
* What was the revenue of the previous sale?
* How much did revenue change from the previous sale?
* What is the revenue of the next sale?
* What are each salesperson's total and average revenues alongside their individual sales?
* What are each customer's total and average revenues alongside their individual purchases?
* What percentage of a customer's revenue was contributed by each sale?
* What percentage of total company revenue was contributed by each sale?
* What are the top two sales for each salesperson?
* How can multiple Window Functions be combined to create a salesperson performance report?

The practice helped me understand that Window Functions perform calculations across related rows without collapsing the individual records.

It also strengthened my understanding of the difference between:

* `GROUP BY` and Window Functions
* `OVER()` and `PARTITION BY`
* Window `ORDER BY` and final `ORDER BY`
* Overall calculations and partition-level calculations
* `ROW_NUMBER()` and `RANK()`
* `RANK()` and `DENSE_RANK()`
* Running totals and regular totals
* `LAG()` and `LEAD()`
* Individual-level metrics and group-level metrics
* Window Functions and aggregate queries
* Window Functions and CTEs

The exercises also reinforced the importance of choosing the correct partition and ordering columns depending on the business question.

The practice built on the CTE concepts from Day 13 and introduced Window Functions as an important SQL technique for analytical reporting, ranking, comparisons, and time-based analysis.


### Day 15 — PARTITION BY & Advanced Window Analysis

Practiced using `PARTITION BY` with SQL Window Functions to perform analytical calculations within specific groups while keeping every individual sale visible in the result.

The exercises focused on understanding how `PARTITION BY` divides rows into logical groups for window calculations, how partition-level calculations differ from running calculations, and how `PARTITION BY` can be combined with `ORDER BY` for chronological analysis.

Practiced:

* Understanding `PARTITION BY`
* Understanding how `PARTITION BY` divides rows into logical calculation groups
* Understanding that Window Functions keep individual rows instead of collapsing them
* Understanding the difference between `GROUP BY` and `PARTITION BY`
* Using `PARTITION BY` with `SUM()`
* Using `PARTITION BY` with `AVG()`
* Using `PARTITION BY` with `COUNT()`
* Partitioning analysis by salesperson
* Partitioning analysis by customer
* Partitioning analysis by region
* Partitioning analysis by category
* Understanding when to use different partition columns
* Using multiple columns inside `PARTITION BY`
* Combining `PARTITION BY` and `ORDER BY`
* Understanding the difference between a partition-level calculation and a running calculation
* Creating salesperson-level total revenue beside every individual sale
* Creating salesperson-level average revenue beside every individual sale
* Comparing individual sales with salesperson averages
* Creating customer-level total and average revenue
* Ranking sales separately within each salesperson
* Using `ROW_NUMBER()` within partitions
* Using `RANK()` within partitions
* Using `DENSE_RANK()` within partitions
* Understanding how ties affect `ROW_NUMBER()`, `RANK()` and `DENSE_RANK()`
* Finding the highest-revenue sale for each salesperson
* Using CTEs to filter Window Function results
* Creating running revenue separately for each salesperson
* Creating running averages separately for each salesperson
* Using `LAG()` within partitions
* Finding the previous sale of the same salesperson
* Calculating revenue changes between consecutive sales
* Calculating percentage contribution within a partition
* Calculating each sale's contribution to salesperson revenue
* Calculating each sale's contribution to customer revenue
* Calculating each sale's contribution to category revenue
* Calculating regional revenue and average sale value
* Creating regional running revenue
* Combining multiple Window Functions in a single analytical report
* Using `PARTITION BY` with chronological analysis
* Understanding Window Function frames
* Understanding the concept of rolling calculations
* Understanding named Windows
* Using CTEs with Window Functions for advanced filtering

Applied `PARTITION BY` and advanced Window Functions to answer business questions such as:

* What is the total revenue generated by each salesperson while keeping every sale visible?
* What is the average sale value for each salesperson?
* How does each sale compare with its salesperson's average sale?
* What is each customer's total revenue and average purchase value?
* How does each sale rank within its salesperson?
* What is the difference between `ROW_NUMBER()`, `RANK()` and `DENSE_RANK()` within a partition?
* What is the highest-revenue sale for each salesperson?
* What is the running revenue of each salesperson over time?
* What is the running average for each salesperson?
* What was the previous sale made by the same salesperson?
* How much did revenue change from the previous sale?
* What percentage of a salesperson's revenue came from each individual sale?
* What is the total and average revenue for each region?
* What percentage of category revenue came from each individual sale?
* What are the top two individual sales for each salesperson?
* Which sales are above their salesperson's average?
* What is each customer's contribution from an individual purchase?
* What is the running revenue for each region?
* How can multiple Window Functions be combined into a salesperson analytical report?

The practice strengthened my understanding of the difference between:

* `GROUP BY` and `PARTITION BY`
* `PARTITION BY` and `PARTITION BY` combined with `ORDER BY`
* Partition-level totals and running totals
* Partition-level averages and running averages
* Overall ranking and ranking within a group
* `ROW_NUMBER()` and `RANK()`
* `RANK()` and `DENSE_RANK()`
* `LAG()` across the complete dataset and `LAG()` within a partition
* Individual sale values and group-level metrics
* Total revenue and percentage contribution
* Window Functions and CTEs
* Window calculations and filtering
* Regular analytical calculations and chronological calculations

The practice also reinforced an important way of thinking about Window Functions:

**`PARTITION BY` answers "Which rows should be analyzed together?"**

**`ORDER BY` inside the Window Function answers "In what order should those rows be analyzed?"**

This helped me understand why a query such as `SUM(revenue) OVER(PARTITION BY salesperson)` produces the total revenue of the salesperson beside every sale, while `SUM(revenue) OVER(PARTITION BY salesperson ORDER BY date)` produces a running revenue value.

The exercises built on the Window Function concepts from Day 14 and developed more advanced analytical skills using partitions, rankings, running calculations, comparisons, contribution analysis, `LAG()`, CTEs, and combined Window Functions.

Day 15 strengthened my ability to choose the correct partition based on the business question and to combine `PARTITION BY`, `ORDER BY`, and different Window Functions to create detailed analytical reports without losing the individual sales records.


