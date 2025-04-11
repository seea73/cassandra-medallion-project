
# 📦 Cassandra Medallion Architecture Project

This project demonstrates the implementation of a **Medallion Architecture** using **Apache Cassandra** as the storage backbone. The Medallion Architecture, comprising Bronze, Silver, and Gold layers, is designed to efficiently handle data ingestion, processing, and analytics.

## 📂 Project Structure

- **colab_code/**: Contains Jupyter notebooks for data processing and analysis.
- **cql/**: Includes Cassandra Query Language (CQL) scripts for database schema creation and data manipulation.
- **screenshots/**: Visual representations and screenshots related to the project.

## 🛠️ Getting Started

### Prerequisites

- **Apache Cassandra**: Ensure Cassandra is installed and running. [Installation Guide](https://cassandra.apache.org/doc/latest/getting_started/installing.html)
- **Jupyter Notebook**: For running the notebooks in the `colab_code` directory. [Installation Guide](https://jupyter.org/install)

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/seea73/cassandra-medallion-project.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd cassandra-medallion-project
   ```

3. **Set Up Cassandra Keyspaces and Tables**:

   - Start the Cassandra server.
   - Execute the CQL scripts in the `cql` directory using `cqlsh`:

     ```bash
     cqlsh -f cql/your_script.cql
     ```

## 🏗️ Medallion Architecture Overview

1. **Bronze Layer**: Raw data ingestion layer. Data is collected and stored in its original format.
2. **Silver Layer**: Cleansed and enriched data. Transformations are applied to ensure data quality and consistency.
3. **Gold Layer**: Aggregated and optimized data, ready for analytics and reporting.

## 🚀 Usage

- **Data Processing**: Utilize the notebooks in the `colab_code` directory to process and analyze data across the Medallion layers.
- **Database Operations**: Use the CQL scripts in the `cql` directory to create keyspaces, tables, and perform data operations in Cassandra.

## 📸 Screenshots

For visual insights into the project's implementation and results, refer to the `screenshots` directory.


## 📝 License

This project is licensed under the [MIT License](LICENSE).
