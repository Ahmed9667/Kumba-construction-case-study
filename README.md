# Kumba construction case study

 ## Summary:
 Kumba Construction, a leading firm in the construction industry, has been at the forefront of incorporating innovative technologies to streamline its operations and enhance project outcomes. With a vast array of projects ranging from residential buildings to large infrastructure, the company generates a significant amount of data from various sources, including project management tools, financial systems, and client interactions. Recognizing the potential of this data to drive decision-making and improve efficiency, Kumba Construction has embarked on an initiative to leverage big data analytics, with a focus on PySpark, to transform its data management and analytical capabilities.


## Objetives of Case Study:
1.Implement a Scalable Data Processing Solution: To design and deploy a scalable data processing solution capable of handling large volumes of data efficiently, using PySpark.

2.Streamline Data Management: To develop a standardized approach for data extraction, cleaning, transformation, and loading (ETL), facilitating smoother data flow and accessibility.

3.Enhance Analytical Capabilities: To enable advanced analytics and real-time data processing, allowing for quicker insights and data-driven decision-making.

Integrate Diverse Data Sources: To ensure seamless integration of data from various sources within the company, promoting a unified view of project and operational data.

![image](https://github.com/user-attachments/assets/a378d520-d3ef-4c92-a9d5-b457a4694d0c)


## Project Scope:

### `1.Data Extraction:`
Extracting data from CSV files into PySpark DataFrames. This involves reading CSV files using PySpark, which allows for distributed processing of large datasets that traditional data processing tools cannot handle efficiently.

### `Data Cleaning & Transformation:`
Performing data cleaning and transformation using PySpark. This step includes handling missing values, correcting data types, and transforming data into a suitable format for analysis. The cleaned and transformed data is then written back into CSV files, leveraging PySpark's ability to handle distributed data writing.

#### ERD Diagram:

![schema](https://github.com/user-attachments/assets/3694627f-e0d1-492a-93b2-3d8c613811fe)

### `Data Loading:`
Loading the processed CSV files into a PostgreSQL database using Psycopg2. This entails establishing a connection to the PostgreSQL database from Python, creating the necessary tables, and efficiently loading data into these tables. This step is crucial for making the processed data available for advanced analytics, reporting, and data visualization.

#### Loaded Tables:

![image](https://github.com/user-attachments/assets/ecf20c65-40d0-4dbe-ae67-e5147b8d5977)









