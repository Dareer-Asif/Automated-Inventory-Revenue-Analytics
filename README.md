# Automated Inventory & Profit Margin Tracking Engine

## Problem Statement
Manual cell-formula spreadsheets cause duplicate row inflation, static reorder alerts, and broken margin tracking across multi-channel sales and vendor purchase orders.

## Architecture & Technical Workflow
- **Power Query ETL Pipeline:** Extracts and cleans multi-source transaction data, normalizing schema structures.
- **Star Schema Data Modeling:** Implemented inside Power Pivot to establish relationship flows across Sales, Purchases, and Catalog dimensions.
- **DAX Measures:** Custom row-iterators and dynamic context-aware formulas for accurate inventory valuation, margin tracking, and reorder alerts.
