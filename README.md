# Home Sales Analysis with PySpark

Built a scalable data analysis pipeline using PySpark to explore pricing trends in home sales across King County, Washington. Leveraged SparkSQL for querying and partitioned the dataset to optimize performance on large-scale data.

## Tools & Technologies Used

- Python
- PySpark
- SparkSQL
- Parquet File Partitioning
- AWS S3 (Data Source)
- Jupyter Notebooks

## File Structure

```text
.
├── Home_Sales.ipynb                     # PySpark analysis notebook
├── home_sales_partitioned/              # Partitioned parquet files by year built
└── Resources/
    └── home_sales.csv                   # Raw home sales dataset
```

## Skills Demonstrated

- Distributed data processing with PySpark
- SQL querying within Spark
- Data partitioning and caching for optimized performance
- Handling large real-world datasets
- Identifying pricing trends from structured data

## Key Findings

- Analyzed over 25,000 home sales in King County, WA.
- 4-bedroom homes sold for an average price between $300,263 and $306,910 per year.
- Homes with 3 beds, 3 baths, 2 floors, and 2,000+ sqft averaged over $600,000 after 2015.
- Homes with a view rating of 4 or higher had an average sale price exceeding $350,000.
- Partitioning data by year built improved query performance by over 70%.
