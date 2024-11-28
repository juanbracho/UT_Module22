# Home Sales Analysis with PySpark

This project demonstrates Big Data analysis techniques using PySpark on a dataset of home sales. The analysis was performed in Google Colab and covers a variety of tasks such as querying data using SQL, optimizing performance with caching and partitioning, and working with Parquet-formatted data.

---

## **Lessons Learned**

Through this assignment, the following concepts and skills were applied:

1. **Big Data Tools**:
   - Utilized PySpark for distributed data processing.
   - Explored Spark SQL for running SQL-like queries on large datasets.

2. **Data Analysis**:
   - Queried data to calculate averages and other statistics.
   - Grouped and aggregated data efficiently.

3. **Performance Optimization**:
   - Cached tables to improve query runtime.
   - Partitioned data by a key (`date_built`) for better performance in querying large datasets.
   - Worked with Parquet format for efficient storage and retrieval.

4. **Google Colab Integration**:
   - Set up a Spark environment on Google Colab.
   - Leveraged cloud tools and PySpark to analyze data effectively.

---

## **Skills Applied**

- Creating and manipulating DataFrames in PySpark.
- Writing SQL queries to extract insights from data.
- Using Spark SQL functions such as `GROUP BY`, `HAVING`, and `ORDER BY`.
- Caching and uncaching tables for runtime optimization.
- Saving and reading Parquet data with partitioning.
- Measuring and comparing query execution times.
- Leveraging Spark’s distributed computing power for Big Data analysis.

---

## **Step-by-Step Instructions to Run**

### Prerequisites:
1. A Google account for using Google Colab.
2. Clone this repository or upload the notebook (`Home_Sales.ipynb`) to your GitHub account.

### Steps:
1. **Open Google Colab**:
   - Go to [Google Colab](https://colab.research.google.com).

2. **Upload the Notebook**:
   - Upload the `Home_Sales.ipynb` file from this repository.

3. **Install and Configure PySpark**:
   - The first code block in the notebook will install PySpark and set up the environment. Run this block to initialize Spark.

4. **Load the Dataset**:
   - The second block downloads the dataset from an AWS S3 bucket. Ensure the internet connection is active and run the block to load the data.

5. **Execute Each Cell Sequentially**:
   - Each cell in the notebook corresponds to a specific task (e.g., creating a temporary table, running SQL queries). Run the cells sequentially to complete the analysis.

6. **Analyze Results**:
   - Outputs for each query and performance comparison will be displayed in the notebook after executing the cells.

7. **Save and Upload Updates to GitHub**:
   - After completing the notebook, save it and upload it to your GitHub repository.

---

## **Key Outputs**

- Average home prices by year based on specific criteria.
- Runtime comparisons between cached and uncached queries.
- Parquet-formatted data stored and queried efficiently.
- Insights into performance optimization techniques in Big Data analysis.

---

## **Acknowledgments**

This project is part of a Data Analytics Bootcamp module on Big Data, focusing on PySpark and its capabilities for processing and analyzing large datasets.
