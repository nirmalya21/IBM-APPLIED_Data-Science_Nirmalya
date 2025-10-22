# Peer-Graded Assignment: Analyzing Historical Stock/Revenue Data and Building a Dashboard (TSLA & GME)

This repository contains the complete solution for the analysis and visualization project, focusing on historical stock prices and revenue data for **Tesla (TSLA)** and **GameStop (GME)**.

***

##  Project Overview

This assignment follows a six-step process, covering data extraction, cleaning, and visualization. The entire workflow is documented within the main Jupyter Notebook (`[Your_Notebook_Name].ipynb`).

### **Project Questions & Outputs**

The project successfully addressed the following six required questions:

| Q No. | Task Focus | Company | Libraries Used | Output/Result |
| :---: | :--- | :--- | :--- | :--- |
| **1** | **Stock Data Extraction & Preview** | Tesla (TSLA) | `yfinance` | First 5 rows of `tesla_data`. |
| **2** | **Revenue Data Extraction & Preview** | Tesla (TSLA) | `BeautifulSoup` | Last 5 rows of `tesla_revenue`. |
| **3** | **Stock Data Extraction & Preview** | GameStop (GME) | `yfinance` | First 5 rows of `gme_data`. |
| **4** | **Revenue Data Extraction & Preview** | GameStop (GME) | `BeautifulSoup` | Last 5 rows of `gme_revenue`. |
| **5** | **Dashboard Plotting** | Tesla (TSLA) | `make_graph` (Plotly) | Dual-axis plot of TSLA price and revenue. |
| **6** | **Dashboard Plotting** | GameStop (GME) | `make_graph` (Plotly) | Dual-axis plot of GME price and revenue. |

***

##  How to Run the Code

### Prerequisites

To execute the notebook locally, ensure you have Python and the following libraries installed:

```bash
!pip install pandas
!pip install requests
!pip install bs4
!pip install html5lib 
!pip install lxml
!pip install yfinance
!pip install plotly
!pip install multitasking==0.0.11
