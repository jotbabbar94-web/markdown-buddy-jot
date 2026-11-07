<!-- AI Assistance Declaration: I used ChatGPT (GPT-6; accessed November 7, 2026) for project ideation, documentation structure, Markdown/R Markdown formatting suggestions, and wording review. Prompts used are recorded in Appendix.md. I will verify the documentation by previewing it, knitting the R Markdown file, testing the R script in RStudio or Posit Cloud, and independently checking calculations. All final calculations and code validation are my responsibility. I am responsible for the accuracy and originality of this work. -->

# Retail Sales Data Analysis

## Project Overview
Retail Sales Data Analysis is a small R project demonstrating how to organize, inspect, and document a dataset using R. It uses fictional synthetic retail transactions only; it contains no real customer or business data.

## Project Objectives
- Organize an R project using a professional folder structure.
- Import and inspect a synthetic CSV dataset.
- Explore transaction quantities by product and region.
- Document one R script using R Markdown.
- Practice Markdown formatting and GitHub version control.

## Project Structure
```text
markdown-buddy-jot/
├── README.md
├── Reflection.md
├── Appendix.md
├── Script_Documentation.Rmd
├── data/
│   └── retail_sales.csv
├── scripts/
│   └── analyze_sales.R
└── docs/
    └── (generated outputs, if any)
```

## Dataset Description
The dataset is located at `data/retail_sales.csv`.

| Variable | Description |
|---|---|
| `Order_ID` | Unique synthetic order identifier |
| `Order_Date` | Date of the transaction |
| `Product` | Product category |
| `Quantity` | Number of units in the transaction |
| `Unit_Price` | Price per unit in fictional currency units |
| `Region` | Fictional sales region |

## Requirements and Dependencies
- R (4.0 or later recommended)
- RStudio Desktop or Posit Cloud
- `readr` package for CSV import

Install the package in the R console:
```r
install.packages("readr")
```

## Installation
1. Download or clone this repository.
2. Open the `markdown-buddy-jot` folder in RStudio.
3. Install the required R package.
4. Open `scripts/analyze_sales.R`.
5. Run the script from the project root.

## Example Usage
```r
source("scripts/analyze_sales.R")
```
The script imports the synthetic dataset, checks its structure and missing values, and prints descriptive summaries.

## Expected Outputs
When the script runs successfully, it prints:
- A preview of the imported dataset.
- Dataset dimensions, column names, and structure.
- Missing-value counts by column.
- Total quantity by product.
- Total quantity by region.

## Validation
Before submission:
- Run the script from the repository root in RStudio or Posit Cloud.
- Confirm the CSV imports without errors.
- Inspect variable types and missing values.
- Independently verify at least one summary in a spreadsheet.
- Preview this README using GitHub's Markdown preview.
- Knit `Script_Documentation.Rmd` and inspect the rendered document.

## License
Created for educational use in BDA400. If reused or distributed publicly, select a suitable license and confirm it with the instructor.

## AI Assistance Disclosure
- **AI tool:** ChatGPT, GPT-6.
- **Date used:** November 7, 2026.
- **Purpose:** Project ideation, README structure, documentation wording, Markdown and R Markdown formatting suggestions, and clarity review.
- **Main prompts:** See `Appendix.md` for seed, refinement, and critique prompts.
- **Changes and validation:** Review and edit generated files, preview the README, knit the R Markdown document, run the R script, and independently verify calculations before submission.
- **Responsibility:** The student is responsible for final content, code, and results.
