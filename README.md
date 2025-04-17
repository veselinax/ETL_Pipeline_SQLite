# ETL Pipeline with SQLite

This project demonstrates an **ETL (Extract, Transform, Load) pipeline** built using **Python** and **SQLite**. The pipeline automates the process of extracting raw data from CSV files, performing necessary transformations (such as cleaning, processing, and formatting), and loading the transformed data into an SQLite database for analysis.

## Project Files

- **ETL_Pipeline_SQLite.ipynb**: Complete ETL pipeline code, including data extraction, transformation, and loading into SQLite.

## Methods & Tools

- **Python programming language**: Main language used for the pipeline.
- **SQLite**: Database used to store the transformed data.
- **Pandas**: Data manipulation library for cleaning and transforming the data.
- **Jupyter Notebook**: Interactive environment to write and execute the pipeline.
- **Matplotlib**: Used for visualizations.

### Data Cleaning
The raw data was cleaned to ensure consistency. Duplicates were removed, and missing values were handled appropriately.

### Data Transformation
Various transformations were applied to the data, including:
- Normalization of certain fields
- Handling categorical variables
- Formatting data into a structured form suitable for loading into the database

### Data Loading
The transformed data was loaded into an **SQLite database** using the `sqlite3` module. The database is structured to allow easy querying and further analysis.

## Key Findings

- **Data Processing**: The ETL pipeline efficiently extracts, transforms, and loads data, which can be queried for deeper insights.
- **Scalability**: This pipeline can be modified to work with additional data sources or larger datasets.
- **Flexibility**: The code structure allows for easy extension to more complex data transformations and additional error handling mechanisms.

## Author

Veselina Veselinova  
veselina.vx@gmail.com

## Conclusion

This ETL pipeline automates the extraction, transformation, and loading of data into an SQLite database. It is designed to be easily customizable for different data processing needs, and it offers a flexible foundation for more advanced data analysis.
