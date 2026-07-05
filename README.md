# Technical Analysis Portfolio

## Overview
This repository contains a technical data science framework built in R to monitor stock market performance and evaluate personal investment holdings. By downloading historical equity and index data, the project surfaces trends and quantitative signals to analyze portfolio assets, such as S&P 500 index ETFs.

## Project Structure
* `data/` : Local directory for storage of equity asset metadata.
* `scripts/` : Core R processing assets.
  * `utils.R` : Utility functions to read stock symbols from a portfolio file.
  * `technical_analysis.R` : Scripts managing automated data downloads and technical indicators.
* `docs/` : R Markdown project validation documentation.

## Installation & Dependencies
To replicate this analysis workflow locally or in Posit Cloud, ensure you have R and RStudio installed. 

1. Clone this repository to your local machine using Git Bash:
git clone [https://github.com/nchelem/markdown-buddy-nchelem-ichegbo.git](https://github.com/nchelem/markdown-buddy-nchelem-ichegbo.git)

2. Install the required data science and financial modeling packages in R:
install.packages("tidyverse")
install.packages("quantmod")

## Example Usage
To initialize the workflow and download historical stock data using utility configurations, run the following commands in R:

library(quantmod)
source("scripts/utils.R")
getSymbols("SPY", src = "yahoo", from = "2026-01-01")

## Dataset Information
* **Data Sources:** Synthetic configuration tables mapped against historical equity data streamed programmatically via open financial APIs.
* **Scope:** Financial data points restricted to academic performance tracking.

## License
This project is licensed under the MIT License.

---

## AI Assistance Disclosure
* **AI Tool Used:** Gemini (July 2026)
* **Main Prompts Provided:** "Here’s a summary of my R project: [Technical analysis and portfolio tracking repository using quantmod]. Generate a professional README.md file using Markdown." and "Add sections for Installation, Example Code, and License. Keep tone concise and professional."
* **Human Modifications:** Standardized repository names to reflect `markdown-buddy-nchelem-ichegbo`, defined specific functional requirements for `utils.R`, and added explicit configuration dependencies for the `quantmod` framework.
