# Customer Segmentation with RFM Analysis

## Project Overview
This project implements customer segmentation using RFM (Recency, Frequency, Monetary) analysis on a retail business dataset. The goal is to identify and categorize customer groups based on their purchasing behavior, allowing for more targeted marketing strategies.

## Table of Contents
- [Dataset Description](#dataset-description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [RFM Analysis Process](#rfm-analysis-process)
- [Results](#results)

## Dataset Description
The dataset contains sales transaction data with the following attributes:
- InvoiceID: Unique identifier for each transaction
- Date: Transaction date
- ProductID: Unique identifier for each product
- TotalSales: Total sales amount for the transaction
- Discount: Discount amount applied
- CustomerID: Unique identifier for each customer
- Quantity: Number of products sold in the transaction

## Requirements
- Python 3.x
- pandas
- numpy
- matplotlib

## Installation
1. Clone this repository: git clone https://github.com/mert-ipek05/Customer-Segmentation-with-RFM.git
2. Install the required packages: pip install pandas numpy matplotlib

## Usage
1. Open the Jupyter notebook `Untitled.ipynb`.
2. Run the cells in order to perform the RFM analysis and generate customer segments.

## RFM Analysis Process
1. Data loading and preprocessing
2. Calculation of RFM metrics
3. Scoring and segmentation of customers
4. Visualization of customer segments

## Results
The analysis segments customers into 10 categories:
- Hibernating
- Loyal Customers
- Champions
- At Risk
- Potential Loyalists
- About to Sleep
- Need Attention
- Promising
- Can't Lose
- New Customers

A pie chart visualizing the distribution of these segments is included in the notebook.

