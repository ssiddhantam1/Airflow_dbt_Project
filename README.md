# Airflow_dbt_Project
# Dataset

https://www.kaggle.com/datasets/tunguz/online-retail

| Column | Description |
| --- | --- |
| InvoiceNo | Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. |
| StockCode | Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. |
| Description | Product (item) name. Nominal. |
| Quantity | The quantities of each product (item) per transaction. Numeric. |
| InvoiceDate | Invice Date and time. Numeric, the day and time when each transaction was generated. |
| UnitPrice | Unit price. Numeric, Product price per unit in sterling. |
| CustomerID | Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. |
| Country | Country name. Nominal, the name of the country where each customer resides. |

# Pipeline

![image](https://github.com/ssiddhantam1/Airflow_dbt_Project/assets/112921572/d77db08b-f7bc-422a-a4c7-e79d63801073)

# Data modeling

![image](https://github.com/ssiddhantam1/Airflow_dbt_Project/assets/112921572/038233ee-3ccc-4e68-beae-3922ecd29f02)

## Prerequisites

- Docker
- Astro CLI
- Soda
- GC account
