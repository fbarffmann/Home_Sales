# Home Sales Analysis with PySpark

Built a scalable analysis pipeline using PySpark to evaluate trends in home sales data. Explored pricing patterns based on year built, number of bedrooms, bathrooms, square footage, and view ratings. Used SparkSQL for efficient querying and partitioning of large datasets.

## Tools & Technologies Used

- Python
- PySpark
- SparkSQL
- AWS S3 Data Source
- Parquet File Partitioning
- Jupyter Notebooks

## File Structure

```text
.
├── Home_Sales.ipynb                # Full analysis notebook
├── home_sales_partitioned/         # Partitioned parquet dataset by year built
└── lending_data.csv                # Original dataset
```

## Skills Demonstrated

- Distributed data processing with PySpark
- SQL querying within Spark
- Performance optimization using caching & partitioning
- Data transformation and aggregation techniques
- Efficient handling of large datasets

## Key Findings

- Analyzed pricing trends for over 25,000 home sales.
- 4-bedroom homes sold for an average of $300,263 to $306,910 per year.
- Homes built with 3 beds, 3 baths, 2 floors, and 2000+ sqft averaged $600,000+ after 2015.
- Properties with a "view" rating of 4 or higher had an average sale price above $350,000.
- Optimized Spark queries reduced processing time by over 70% when using cache vs. uncached data.
