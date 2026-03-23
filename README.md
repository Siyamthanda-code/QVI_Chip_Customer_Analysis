# QVI Chip Customer Analysis 🥔

## Project Overview
This project analyzes customer purchasing behavior for the chip category using transaction data and customer segmentation datasets. The objective is to identify key customer segments, understand their purchasing patterns, and provide data-driven strategic recommendations to the Category Manager.

## Key Findings
The analysis highlighted three primary segments driving chip sales:

1.  **Older Families (Budget):** The top segment by total sales, indicating high purchase volume and brand loyalty.
2.  **Young Singles/Couples (Mainstream):** A large segment contributing significant total sales, though with a lower average spend per customer, suggesting frequent but smaller transactions.
3.  **Retirees (Mainstream):** A consistent, high-value segment contributing significantly to overall revenue.

## Strategic Recommendations
*   **Target High-Value Segments:** Prioritize marketing and promotional efforts on **Older Families** and **Retirees** to maintain loyalty and maximize revenue.
*   **Increase Basket Size:** For the **Young Singles/Couples** segment, implement strategies such as multi-buy deals or bundle offers to increase the average transaction value.
*   **Data Integrity:** One duplicate transaction was identified and removed during the cleaning process to ensure analysis accuracy.

## Repository Structure
```text
.
├── QVI_transaction_data.xlsx       # Raw transaction data
├── QVI_purchase_behaviour.csv      # Raw customer segment data
├── chip_analysis.R                 # R script for data cleaning and analysis
├── customer_segment_analysis.csv   # Final output with segment metrics
└── README.md                       # Project documentation
```

## Tools & Requirements
*   **Language:** R (version 4.5.x)
*   **Libraries:** `readxl`, `dplyr`, `ggplot2`, `stringr`, `lubridate`, `readr`

## How to Run
1.  Clone this repository to your local machine.
2.  Open `chip_analysis.R` in RStudio or your preferred R environment.
3.  Set the working directory to the project folder:
    ```r
    setwd("path/to/your/repository")
    ```
4.  Install required packages if not already installed:
    ```r
    install.packages(c("readxl", "dplyr", "ggplot2", "stringr", "lubridate", "readr"))
    ```
5.  Run the script. It will clean the data, generate visualizations, and export the results to `customer_segment_analysis.csv`.

## Author
**Siyamthanda Amahle Buthelezi**
