Credit Card Financial Dashboard

A Power BI dashboard built on a SQL Server relational data model, analyzing ~1.85M credit card transactions to surface revenue trends, customer segments, and anomaly-based risk flagging.

Dataset

Sparkov Credit Card Fraud Detection Dataset (Kaggle) — ~1.85M simulated transactions, 999 customers, 693 merchants, real dated transactions from Jan 2019–Dec 2020.

Tech stack
SQL Server — staging load, star-schema data model, risk-scoring views
Power BI / DAX — data model, measures, four-page interactive report
What it does
Star-schema data model: Dim_Customer, Dim_Merchant, Dim_Category, Dim_Date, Fact_Transactions
Anomaly-based risk scoring (SQL view) flagging the top 5% of customers by deviation from their own historical spending pattern
DAX measures for revenue trends, MoM growth, customer segmentation, and transaction patterns
Four report pages: Executive Overview, Risk Monitoring, Customer Segments, Category & Merchant


The full .pbix file is large (SQL Server–connected, 1.85M-row import) and isn't included here — available on request.

Note on the data

This is a simulated dataset (Sparkov), used here to demonstrate SQL Server data modeling and Power BI/DAX skills — not real credit card data.
