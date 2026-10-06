
# SQL — Complete Concept Checklist for Data Engineer Interviews

## 1. SQL Fundamentals
- SQL fundamentals
- Relational model
- Tables
- Rows
- Columns
- Attributes
- Tuples
- Relations
- Schemas
- Databases
- Catalogs
- Views
- SQL dialects
- ANSI SQL
- SQL standards
- SQL statements
- SQL clauses
- SQL expressions
- SQL operators
- SQL identifiers
- SQL literals
- Reserved keywords
- Comments
- Aliases
- Qualified names

## 2. Data Types
- Numeric data types
- Integer types
- Decimal types
- Floating-point types
- Fixed-point numbers
- Character types
- Variable-length strings
- Boolean types
- Binary types
- Date types
- Time types
- Timestamp types
- Time-zone-aware timestamps
- Intervals
- JSON
- XML
- Arrays
- Structs
- Records
- Maps
- Variant/semi-structured types
- User-defined types
- Type precedence
- Type compatibility
- Implicit conversion
- Explicit conversion
- Casting
- Precision
- Scale
- Numeric overflow
- String encoding
- Character sets
- Collations

## 3. NULL and Three-Valued Logic
- NULL semantics
- NULL vs empty string
- NULL vs zero
- NULL comparisons
- Three-valued logic
- TRUE
- FALSE
- UNKNOWN
- NULL propagation
- NULL arithmetic
- NULL concatenation
- NULL sorting
- NULL grouping
- NULL aggregation
- NULL join behavior
- NULL filtering
- NULL-safe equality
- NULL handling functions
- NULL-related `IN` behavior
- NULL-related `NOT IN` behavior

## 4. SELECT and Projection
- Projection
- Column selection
- Expressions
- Computed columns
- Column aliases
- Qualified columns
- Wildcard projection
- Distinct projection
- Expression evaluation
- Logical query processing
- SQL evaluation order

## 5. Filtering
- Row filtering
- Predicate evaluation
- Comparison predicates
- Logical predicates
- Boolean expressions
- Range predicates
- Membership predicates
- Pattern matching
- Regular expressions
- Predicate precedence
- Predicate pushdown
- SARGability
- Search predicates

## 6. Sorting and Ordering
- Ordering
- Ascending order
- Descending order
- Multi-column ordering
- Expression ordering
- NULL ordering
- Deterministic ordering
- Stable ordering
- Ordering after aggregation
- Ordering with window functions

## 7. DISTINCT and Duplicate Handling
- Duplicate rows
- Duplicate elimination
- DISTINCT semantics
- Multi-column distinctness
- DISTINCT aggregation
- Duplicate detection
- Duplicate removal
- Deduplication strategies
- Deterministic deduplication

## 8. Limiting and Pagination
- Result limiting
- Offset pagination
- Keyset pagination
- Seek pagination
- Cursor-based pagination
- Pagination consistency
- Pagination performance
- Deterministic pagination

---

# 9. Aggregation

- Aggregation
- Aggregate functions
- COUNT
- SUM
- AVG
- MIN
- MAX
- DISTINCT aggregation
- NULL-aware aggregation
- Conditional aggregation
- Multiple aggregations
- Aggregation granularity
- Aggregation cardinality
- Partial aggregation
- Hierarchical aggregation
- Approximate aggregation
- Statistical aggregation
- String aggregation
- Array aggregation
- JSON aggregation

## 10. GROUP BY
- Grouping
- Grouping keys
- Multiple grouping keys
- Grouping expressions
- Grouping granularity
- GROUP BY semantics
- GROUP BY vs DISTINCT
- GROUP BY vs window functions
- GROUP BY with joins
- GROUP BY with NULLs
- Functional dependencies
- Grouping sets
- ROLLUP
- CUBE
- GROUPING SETS
- GROUPING metadata

## 11. HAVING
- Post-aggregation filtering
- HAVING semantics
- WHERE vs HAVING
- Aggregate predicates
- Group-level filtering

---

# 12. Joins

- Join fundamentals
- Join predicates
- Join cardinality
- Join selectivity
- Inner joins
- Left outer joins
- Right outer joins
- Full outer joins
- Cross joins
- Self joins
- Equi joins
- Non-equi joins
- Theta joins
- Range joins
- Composite-key joins
- Natural joins
- Semi joins
- Anti joins
- Correlated joins
- Lateral joins
- Temporal joins
- As-of joins
- Lookup joins
- Dimension joins

## 13. Join Cardinality and Data Duplication
- One-to-one relationships
- One-to-many relationships
- Many-to-one relationships
- Many-to-many relationships
- Row multiplication
- Join explosion
- Fan-out
- Duplicate propagation
- Aggregation after joins
- Pre-aggregation before joins
- Join grain
- Grain mismatch
- Join key uniqueness

## 14. Advanced Join Behavior
- Join predicate placement
- ON vs WHERE
- Outer join filtering
- NULL join behavior
- Join elimination
- Join reordering
- Join associativity
- Join commutativity
- Cartesian products
- Broadcast joins
- Hash joins
- Merge joins
- Nested-loop joins

---

# 15. Subqueries
- Subqueries
- Scalar subqueries
- Single-row subqueries
- Multi-row subqueries
- Correlated subqueries
- Uncorrelated subqueries
- Nested subqueries
- Subqueries in SELECT
- Subqueries in WHERE
- Subqueries in FROM
- Subqueries in HAVING
- Subquery optimization
- Correlated subquery performance
- Subquery-to-join transformations

## 16. EXISTS / IN
- EXISTS
- NOT EXISTS
- IN
- NOT IN
- Semi-join semantics
- Anti-join semantics
- NULL behavior
- EXISTS vs IN
- NOT EXISTS vs NOT IN

---

# 17. Common Table Expressions

- CTE fundamentals
- Multiple CTEs
- Chained CTEs
- CTE scope
- CTE materialization
- CTE inlining
- Recursive CTEs
- Recursive query structure
- Hierarchical queries
- Tree traversal
- Graph traversal
- Sequence generation
- Recursive termination

---

# 18. Set Operations
- UNION
- UNION ALL
- INTERSECT
- EXCEPT
- MINUS
- Set semantics
- Duplicate preservation
- Duplicate elimination
- Column compatibility
- Data-type compatibility
- Set operation ordering

---

# 19. CASE and Conditional Logic
- CASE expressions
- Searched CASE
- Simple CASE
- Conditional expressions
- Nested CASE
- Conditional aggregation
- Conditional classification
- NULL handling through conditional logic
- Boolean expressions

---

# 20. SQL Functions

### String Functions
- String manipulation
- Concatenation
- Substring extraction
- String length
- Trimming
- Padding
- Case conversion
- Replacement
- Splitting
- String searching
- Pattern matching
- Regular expressions
- String normalization

### Numeric Functions
- Rounding
- Truncation
- Absolute values
- Sign functions
- Power
- Square root
- Modulo
- Mathematical functions
- Statistical functions

### Conversion Functions
- Type casting
- String-to-number conversion
- Number-to-string conversion
- String-to-date conversion
- Date-to-string conversion
- Boolean conversion

### NULL Functions
- COALESCE
- NULLIF
- NULL replacement
- NULL-safe comparisons

---

# 21. Date and Time
- Date arithmetic
- Time arithmetic
- Timestamp arithmetic
- Date differences
- Time differences
- Interval arithmetic
- Date extraction
- Date truncation
- Date rounding
- Calendar concepts
- Week calculations
- Month calculations
- Quarter calculations
- Year calculations
- Fiscal calendars
- Business calendars
- ISO weeks
- Leap years
- Month-end calculations
- Start/end-of-period calculations

## 22. Time Zones
- UTC
- Local time
- Time-zone conversion
- Time-zone offsets
- Daylight saving time
- Time-zone-aware timestamps
- Time-zone-naive timestamps
- Timestamp normalization

---

# 23. Window Functions

- Window functions
- Window partitions
- Window ordering
- Window frames
- Window aggregation
- Window ranking
- Window navigation
- Window distribution

### Ranking
- ROW_NUMBER
- RANK
- DENSE_RANK
- NTILE

### Navigation
- LAG
- LEAD
- FIRST_VALUE
- LAST_VALUE
- NTH_VALUE

### Window Aggregation
- Running totals
- Cumulative aggregates
- Moving aggregates
- Partition-level aggregates
- Percent-of-total calculations

### Window Frames
- ROWS
- RANGE
- GROUPS
- UNBOUNDED PRECEDING
- UNBOUNDED FOLLOWING
- CURRENT ROW
- Preceding frames
- Following frames
- Frame boundaries
- Peer groups

---

# 24. Advanced Analytical SQL

- Top-N analysis
- Top-N per group
- Bottom-N analysis
- Ranking within groups
- Percentiles
- Median
- Quartiles
- Deciles
- Percentile distributions
- Cumulative distribution
- Relative ranking
- Percent-of-total
- Running percentages
- Moving averages
- Rolling aggregates
- Period-over-period analysis
- Month-over-month analysis
- Year-over-year analysis
- Quarter-over-quarter analysis
- Growth rates
- Change detection
- Trend analysis

---

# 25. Gaps and Islands
- Gaps-and-islands problem
- Consecutive sequences
- Consecutive dates
- Consecutive events
- Grouping contiguous records
- Sequence identification
- Streak detection
- Missing-period detection
- Islands construction
- Gap identification

---

# 26. Deduplication
- Exact duplicates
- Logical duplicates
- Business-key duplicates
- Latest-record deduplication
- Earliest-record deduplication
- Deterministic deduplication
- Window-based deduplication
- Duplicate ranking
- Duplicate detection
- Source-system duplicates

---

# 27. Slowly Changing Dimensions
- Dimension history
- SCD concepts
- Type 0
- Type 1
- Type 2
- Type 3
- Effective dates
- Expiration dates
- Current-record indicators
- Surrogate keys
- Natural keys
- Historical joins
- Temporal dimension joins

---

# 28. Temporal SQL
- Temporal data
- Valid time
- Transaction time
- Bitemporal data
- Effective dating
- Temporal ranges
- Point-in-time queries
- As-of queries
- Historical state reconstruction
- Temporal joins
- Slowly changing records

---

# 29. Event and Transaction Analysis
- Event sequencing
- Event ordering
- Previous-event analysis
- Next-event analysis
- Event deltas
- Event intervals
- State transitions
- Status changes
- First-event detection
- Last-event detection
- Repeat-event detection
- Event frequency
- Event windows
- Event deduplication

---

# 30. Sessionization
- Session identification
- Inactivity thresholds
- Event gaps
- Session boundaries
- Session IDs
- User sessions
- Web sessions
- Application sessions
- Event stream sessionization

---

# 31. Data Quality SQL
- NULL detection
- Duplicate detection
- Referential integrity checks
- Uniqueness checks
- Domain validation
- Range validation
- Format validation
- Completeness checks
- Consistency checks
- Accuracy checks
- Freshness checks
- Referential integrity
- Orphan records
- Unexpected cardinality
- Unexpected row counts
- Data anomaly detection

---

# 32. Relational Constraints
- Primary keys
- Foreign keys
- Unique constraints
- NOT NULL
- CHECK constraints
- DEFAULT constraints
- Referential integrity
- Cascading actions
- Constraint enforcement
- Constraint validation
- Deferred constraints

---

# 33. Database Objects
- Tables
- Temporary tables
- Global temporary tables
- Views
- Materialized views
- External tables
- Derived tables
- Sequences
- Synonyms
- Schemas
- Stored procedures
- User-defined functions
- Triggers

---

# 34. DDL
- CREATE
- ALTER
- DROP
- TRUNCATE
- RENAME
- COMMENT
- Table creation
- Column modification
- Constraint creation
- Schema creation
- Object dependencies

---

# 35. DML
- INSERT
- UPDATE
- DELETE
- MERGE
- UPSERT
- Multi-row inserts
- Conditional updates
- Conditional deletes
- Insert-select
- Update-from
- Merge semantics

---

# 36. Transactions

- Transactions
- ACID
- Atomicity
- Consistency
- Isolation
- Durability
- COMMIT
- ROLLBACK
- SAVEPOINT
- Autocommit
- Transaction boundaries
- Transaction isolation

## 37. Isolation Levels
- Read Uncommitted
- Read Committed
- Repeatable Read
- Snapshot Isolation
- Serializable
- Dirty reads
- Non-repeatable reads
- Phantom reads
- Lost updates
- Write skew
- Snapshot anomalies

---

# 38. Concurrency
- Concurrent transactions
- Locking
- Shared locks
- Exclusive locks
- Row-level locks
- Page-level locks
- Table-level locks
- Deadlocks
- Lock escalation
- Blocking
- MVCC
- Optimistic concurrency
- Pessimistic concurrency

---

# 39. Views and Materialized Views
- Views
- Updatable views
- Non-updatable views
- View dependencies
- View security
- Materialized views
- Materialized view refresh
- Incremental refresh
- Full refresh
- Query rewriting
- Materialized view performance

---

# 40. Indexes

- Index fundamentals
- B-tree indexes
- Hash indexes
- Bitmap indexes
- Clustered indexes
- Non-clustered indexes
- Composite indexes
- Covering indexes
- Unique indexes
- Partial indexes
- Filtered indexes
- Expression indexes
- Functional indexes
- Full-text indexes
- Index selectivity
- Index cardinality
- Index maintenance
- Index fragmentation
- Index-only scans
- Index usage

---

# 41. Query Performance

- Query optimization
- Cost-based optimization
- Rule-based optimization
- Query planner
- Query optimizer
- Execution plan
- Explain plan
- Explain analyze
- Query cost
- Cardinality estimation
- Selectivity estimation
- Statistics
- Table statistics
- Column statistics
- Histograms
- Query rewriting
- Predicate pushdown
- Projection pushdown
- Partition pruning
- Join elimination
- Constant folding
- Subquery optimization

---

# 42. Execution Plans

Understand:

- Sequential scan
- Full table scan
- Index scan
- Index seek
- Index-only scan
- Bitmap scan
- Nested-loop join
- Hash join
- Merge join
- Sort
- Aggregate
- Hash aggregate
- Group aggregate
- Window aggregation
- Materialization
- Spooling
- Exchange
- Shuffle
- Broadcast
- Gather
- Parallel execution

---

# 43. SQL Performance Tuning

- Query bottleneck identification
- Slow-query analysis
- Query profiling
- Execution-plan analysis
- Index tuning
- Join optimization
- Aggregation optimization
- Predicate optimization
- Subquery optimization
- CTE optimization
- Sorting optimization
- DISTINCT optimization
- Window-function optimization
- Partition pruning
- Data skipping
- Statistics maintenance
- Avoiding unnecessary scans
- Avoiding unnecessary joins
- Avoiding row explosion
- Avoiding unnecessary materialization

---

# 44. Data Warehousing SQL

- OLTP vs OLAP
- Fact tables
- Dimension tables
- Star schema
- Snowflake schema
- Galaxy schema
- Fact grain
- Dimension grain
- Degenerate dimensions
- Junk dimensions
- Role-playing dimensions
- Conformed dimensions
- Surrogate keys
- Natural keys
- Factless fact tables
- Accumulating snapshots
- Periodic snapshots
- Transaction facts

---

# 45. Advanced Data Warehouse Concepts
- Slowly changing dimensions
- Late-arriving dimensions
- Late-arriving facts
- Early-arriving facts
- Unknown members
- Referential integrity
- Historical reconstruction
- Point-in-time reporting
- Snapshotting
- Incremental loading
- Full loading
- Change data capture
- Upserts
- Merge strategies
- Idempotent transformations

---

# 46. SQL for ETL / ELT

- Extraction
- Transformation
- Loading
- Staging tables
- Intermediate tables
- Target tables
- Incremental transformations
- Full transformations
- Incremental loads
- Watermarks
- High-water marks
- Change detection
- CDC processing
- Deduplication
- Data standardization
- Data cleansing
- Data enrichment
- Data reconciliation
- Data validation

---

# 47. Incremental Processing

- Incremental loads
- Full loads
- Watermarking
- High-water mark
- Low-water mark
- Timestamp-based incremental loading
- ID-based incremental loading
- CDC-based loading
- Change tracking
- Late-arriving data
- Out-of-order data
- Backfills
- Reprocessing
- Idempotency

---

# 48. Advanced SQL Patterns

You should know how to solve the classic:

- Second-highest value
- Nth-highest value
- Top-N per group
- Latest record per entity
- First record per entity
- Duplicate detection
- Duplicate removal
- Missing records
- Missing dates
- Missing sequences
- Consecutive dates
- Consecutive values
- Gaps and islands
- Running totals
- Moving averages
- Cumulative metrics
- Ranking
- Percentile analysis
- Median calculation
- Pivoting
- Unpivoting
- Conditional pivoting
- Row-to-column transformation
- Column-to-row transformation
- Hierarchical traversal
- Parent-child relationships
- Recursive relationships
- Sessionization
- Funnel analysis
- Cohort analysis
- Retention analysis
- Churn analysis
- Conversion analysis
- State-transition analysis
- Change-point detection
- Slowly changing dimensions
- Point-in-time joins
- As-of joins

---

# 49. Pivoting and Reshaping
- Pivot
- Unpivot
- Crosstab
- Conditional pivot
- Dynamic pivot
- Row-to-column transformation
- Column-to-row transformation
- Wide-to-long transformation
- Long-to-wide transformation

---

# 50. JSON and Semi-Structured Data
- JSON data types
- JSON parsing
- JSON extraction
- JSON path expressions
- Nested JSON
- JSON arrays
- JSON objects
- Array expansion
- Flattening
- Exploding
- Unnesting
- Struct access
- Nested field access
- Semi-structured querying
- Schema-on-read

---

# 51. Arrays and Nested Data
- Arrays
- Array indexing
- Array slicing
- Array aggregation
- Array expansion
- Array flattening
- UNNEST
- Explode
- Nested structures
- Repeated fields
- Structs
- Maps

---

# 52. Advanced Analytical Concepts
- Cohort analysis
- Retention analysis
- Funnel analysis
- Conversion rates
- Churn analysis
- Customer lifetime analysis
- Pareto analysis
- Frequency analysis
- Recency analysis
- Ranking analysis
- Distribution analysis
- Time-series analysis
- Seasonality
- Rolling metrics
- Period comparisons
- Segmentation
- Behavioral analysis

---

# 53. Statistical SQL
- Mean
- Median
- Mode
- Variance
- Standard deviation
- Percentiles
- Quantiles
- Distribution
- Correlation
- Covariance
- Regression functions
- Z-scores
- Outlier detection
- Approximate statistics

---

# 54. Advanced Relational Theory

For the hardest interviews:

- Relational algebra
- Selection
- Projection
- Cartesian product
- Union
- Intersection
- Difference
- Join algebra
- Relational division
- Functional dependencies
- Candidate keys
- Superkeys
- Primary keys
- Foreign keys
- Normalization
- Denormalization
- 1NF
- 2NF
- 3NF
- BCNF
- 4NF
- 5NF
- Lossless decomposition
- Dependency preservation

---

# 55. Query Correctness

- Query grain
- Data grain
- Cardinality
- Functional dependencies
- Duplicate propagation
- Join correctness
- Aggregation correctness
- NULL correctness
- Temporal correctness
- Deterministic results
- Edge cases
- Empty datasets
- Duplicate datasets
- Missing data
- Boundary conditions

---

# 56. Distributed SQL / Data Engineering SQL

Particularly important for Spark, Databricks, Snowflake, BigQuery, Trino, Presto, Redshift, etc.

- Distributed query execution
- Parallel query execution
- Data partitioning
- Hash partitioning
- Range partitioning
- Data shuffling
- Shuffle joins
- Broadcast joins
- Distributed aggregation
- Partial aggregation
- Data skew
- Partition pruning
- Predicate pushdown
- Projection pushdown
- Columnar execution
- Vectorized execution
- Distributed sorting
- Spill-to-disk
- Memory pressure
- Query stages
- Exchange operations

---

# 57. Data Skew

- Join skew
- Aggregation skew
- Key skew
- Hot partitions
- Uneven partition sizes
- Skew detection
- Skew mitigation
- Salting
- Broadcast strategies
- Partitioning strategies

---

# 58. Columnar Data and SQL

- Columnar storage
- Row-oriented storage
- Column-oriented storage
- Column pruning
- Predicate pushdown
- Compression
- Encoding
- Data skipping
- Min/max statistics
- Zone maps
- File statistics

---

# 59. Partitioning

- Table partitioning
- Range partitioning
- List partitioning
- Hash partitioning
- Composite partitioning
- Partition pruning
- Partition elimination
- Partition-wise joins
- Partition maintenance
- Partition evolution
- Partition selection
- Partition skew

---

# 60. Distributed Data Warehouses / Lakehouses

Understand SQL behavior in:

- PostgreSQL
- MySQL
- SQL Server
- Oracle
- Snowflake
- BigQuery
- Redshift
- Databricks SQL
- Spark SQL
- Trino
- Presto
- Athena
- Hive

Know the important **dialect differences**, especially around:

- Date functions
- String functions
- NULL behavior
- Window functions
- JSON
- Arrays
- MERGE
- QUALIFY
- LIMIT/TOP/FETCH
- Set operations
- Recursive CTEs
- Temporary tables
- Materialized views

---

# 61. Security

- Database authentication
- Authorization
- Users
- Roles
- Privileges
- GRANT
- REVOKE
- Object-level permissions
- Column-level security
- Row-level security
- Dynamic data masking
- Data masking
- Views for security
- Least privilege
- SQL injection
- Parameterized queries
- Prepared statements
- Sensitive-data access

---

# 62. Stored SQL Logic

- Stored procedures
- User-defined functions
- Scalar functions
- Table-valued functions
- Stored functions
- Variables
- Control flow
- Exception handling
- Cursors
- Triggers
- Procedural SQL
- Dynamic SQL

---

# 63. Metadata and System Catalogs

- Information schema
- System catalogs
- Table metadata
- Column metadata
- Constraint metadata
- Index metadata
- Query history
- Query statistics
- Execution metadata
- Dependency metadata
- Data lineage

---

# 64. SQL Transactions in Data Engineering

- Transaction boundaries
- Atomic loads
- Transactional ETL
- Commit/rollback
- Partial failure
- Retry behavior
- Idempotency
- Exactly-once semantics
- At-least-once semantics
- Duplicate prevention
- Concurrent writes

---

# 65. Data Reconciliation

- Source-to-target reconciliation
- Row-count reconciliation
- Aggregate reconciliation
- Hash reconciliation
- Checksum validation
- Control totals
- Balance validation
- Duplicate reconciliation
- Missing-record reconciliation
- Referential reconciliation
- Incremental reconciliation

---

# 66. SQL Debugging

- Syntax errors
- Semantic errors
- Type errors
- Cardinality errors
- Logic errors
- Join errors
- Aggregation errors
- NULL-related errors
- Duplicate-related errors
- Temporal errors
- Performance errors
- Data-quality errors
- Incorrect grain
- Unexpected row multiplication
- Incorrect filtering
- Incorrect window frames

---

# 67. Production SQL Engineering

- Query maintainability
- Query readability
- Modular SQL
- Reusable SQL
- Parameterized SQL
- Idempotent SQL
- Deterministic SQL
- Testing SQL
- Version-controlled SQL
- SQL code review
- SQL standards
- Naming conventions
- Documentation
- Dependency management
- Data lineage
- Observability
- Query monitoring
- Query alerting

---

# 68. SQL Testing

- Unit testing SQL
- Integration testing
- Data-quality testing
- Schema testing
- Constraint testing
- Null testing
- Duplicate testing
- Boundary testing
- Regression testing
- Reconciliation testing
- Property-based testing
- Golden datasets
- Test fixtures
- Expected-result validation

---

# 69. SQL Optimization at Senior/Staff Level

- Query plan interpretation
- Cardinality estimation
- Cost estimation
- Join-order optimization
- Join algorithm selection
- Index strategy
- Partition strategy
- Clustering strategy
- Data distribution
- Statistics
- Materialization
- Caching
- Query result caching
- Intermediate-result reuse
- Predicate pushdown
- Projection pushdown
- Partition pruning
- Data skipping
- Broadcast strategies
- Skew mitigation
- Parallelism
- Resource utilization
- Memory optimization
- Spill management
- Warehouse sizing

---

# 70. SQL Interview Problem-Solving Concepts

Finally, you should be able to recognize and solve problems involving:

- Aggregation
- Filtering
- Joins
- Anti-joins
- Semi-joins
- Subqueries
- CTEs
- Recursive CTEs
- Set operations
- Window functions
- Ranking
- Deduplication
- Gaps and islands
- Time-series analysis
- Event sequencing
- Sessionization
- Pivoting
- Unpivoting
- Hierarchies
- Graph-like relationships
- Slowly changing dimensions
- Temporal joins
- Point-in-time analysis
- Cohorts
- Funnels
- Retention
- Churn
- Incremental processing
- CDC
- Data quality
- Reconciliation
- Query optimization
- Execution plans
- Distributed SQL
- Data skew
- Warehouse optimization

---

## The hierarchy I would use for your preparation

If your objective is specifically **cracking the toughest Data Engineer interviews**, prioritize the syllabus in this order:

**Tier 1 — Non-negotiable**
1. SELECT / WHERE / GROUP BY / HAVING
2. JOINs
3. NULLs
4. Aggregations
5. CASE
6. Subqueries
7. CTEs
8. Set operations
9. Window functions
10. Date/time
11. Deduplication
12. Top-N / ranking
13. Gaps & islands
14. Query execution order
15. Query grain and cardinality

**Tier 2 — Senior DE level**
16. Advanced window functions
17. Recursive CTEs
18. Temporal SQL
19. SCDs
20. Sessionization
21. Cohort/funnel/retention analysis
22. Pivot/unpivot
23. JSON/semi-structured data
24. Advanced joins
25. Incremental SQL / CDC
26. Data-quality SQL
27. Query optimization
28. Execution plans
29. Indexes
30. Partitioning

**Tier 3 — Advanced DE / Staff-level**
31. Relational algebra
32. Query optimizer internals
33. Cardinality estimation
34. Transaction isolation
35. MVCC
36. Locking/concurrency
37. Distributed SQL
38. Shuffle
39. Data skew
40. Columnar execution
41. Distributed joins
42. Distributed aggregation
43. Warehouse/lakehouse optimization
44. Advanced statistics
45. SQL security
46. Production SQL engineering
