# Automated Product Search and Recommendation Bot

An Intelligent Process Automation (IPA) solution developed using **UiPath** during the **Capgemini Intelligent Process Automation (IPA) Training**.

## Overview

This project automates product search across multiple e-commerce websites by extracting product details, comparing products based on predefined criteria, and generating recommendation reports. The automation minimizes manual effort and helps users make informed purchasing decisions.

## Features

- Automated product search
- Web automation and data extraction
- Product comparison
- Excel report generation
- Email integration
- Exception handling
- Modular workflow implementation

## Technologies Used

- UiPath
- Web Automation
- Data Scraping
- Excel Automation
- UI Automation
- Selectors
- Exception Handling

## Workflow Modules

| Workflow | Description |
|----------|-------------|
| **Main.xaml** | Controls the complete automation process. |
| **Seq_GetEmail.xaml** | Retrieves product search input from email. |
| **amazonPProduct.xaml** | Extracts product details from Amazon. |
| **flipkartProduct.xaml** | Extracts product details from Flipkart. |
| **Comparision.xaml** | Compares extracted product information and selects the best recommendation. |
| **send_response.xaml** | Sends the recommendation report to the user. |


## Project Flow

1. Receive product search request.
2. Search products on Amazon and Flipkart.
3. Extract product details.
4. Compare products based on predefined criteria.
5. Generate the recommendation report.
6. Send the report to the user via email.

## Note

This repository contains the UiPath project along with workflow screenshots created during the **Capgemini Intelligent Process Automation (IPA) Training**. It is intended for educational and portfolio purposes.

---

**Developed by Sunny Sharma**
