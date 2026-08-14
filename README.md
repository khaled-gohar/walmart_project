# Walmart Project

A data pipeline project using Apache Airflow and DBT for Walmart data processing and transformation.

## Project Structure

```
walmart_project/
├── data/                  # Sample data files
│   ├── customers.csv
│   ├── employees.csv
│   ├── order_items.csv
│   ├── orders.csv
│   ├── products.csv
│   └── stores.csv
├── loader.ipynb          # Jupyter notebook for data exploration
├── main.py               # Main application entry point
├── pyproject.toml        # Python project configuration
└── README.md            # This file
```

## Prerequisites

- Python 3.8+
- Apache Airflow
- DBT
- Pandas

## Setup

1. Clone the repository:
```bash
git clone https://github.com/khaled-gohar/walmart_project.git
cd walmart_project
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the main application:
```bash
python main.py
```

## Usage

### Jupyter Notebook
Open and run `loader.ipynb` for interactive data exploration:
```bash
jupyter notebook loader.ipynb
```

### Main Application
Run the main pipeline:
```bash
python main.py
```

## Data Files

The project includes sample CSV files for:
- **customers.csv** - Customer information
- **employees.csv** - Employee records
- **orders.csv** - Order transactions
- **order_items.csv** - Details of items in each order
- **products.csv** - Product catalog
- **stores.csv** - Store locations

## Contributing

Feel free to fork, create a feature branch, and submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
