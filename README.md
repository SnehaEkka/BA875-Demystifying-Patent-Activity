# Demystifying Patent Activity: The Link between Innovation and Company Performance
#### *"Exploring the influence of R&D investment and patents on business outcomes across industries"*

## About
This project investigates the relationship between a company’s internal innovation drivers—such as R&D spending and patent activity—and financial performance. Using detailed datasets from Compustat/WRDS and patent records, we quantify how different innovation strategies impact profitability, patent output, and competitive positioning.

## Data Sources

- **Financial Data:** Compustat & WRDS (revenue, profit, R&D expenses, ROA).
- **Patent Data:** Two datasets covering patent activity, types, yearly summaries, and industry classification.

## Project Goals

- Assess how R&D expenditure and patenting activity drive changes in Return on Assets (ROA).
- Quantify the effect of patent characteristics (year, type, industry) on company innovation output.
- Analyze external influences including competition, regulatory pressures, and consumer adoption.

## Analysis Overview

- **Regression Models:**  
  - Linked internal drivers (R&D spend, number of patents) and patent features to ROA and patent counts.
  - Evaluated statistical reliability of models and addressed multicollinearity.

- **Key Findings:**  
  - All modeled variables showed statistically significant but modest influence on ROA and patent output.
  - ROA model proved robust and well-specified.
  - Collinearity between functional and design patents limited their independent analysis—resulting in exclusion from final models.
  - Missing financial data reduced explanatory power in some cases.

- **Business Insights:**  
  - Innovation is a multifaceted driver: patents and R&D contribute to performance, but external factors like market adoption, competition, and regulation play substantial roles.
  - Companies should balance patent portfolio growth with investment in competitive intelligence and customer-driven innovation.

## Challenges

- **Data Quality:** Missing values in financial metrics posed analysis limitations.
- **Multicollinearity:** High correlation between functional and design patent counts required exclusion from detailed regression.
- **Computation Cost:** Large data files led to higher processing times.

## How to Reproduce / Run Analysis

1. Download project files and datasets from the repository.
2. Install necessary Python libraries (`pandas`, `statsmodels`, `numpy`, etc.) as listed in `requirements.txt`.
3. Open and run the main analysis notebook (`Demystifying_Patent_Activity.ipynb`) for step-by-step EDA, regression results, and visualization.
4. Follow comments to adapt data sources or extend analysis.

## Future Improvements

- Integrate additional financial and market metrics to boost model explanatory power.
- Test causal relationships with instrumental variables or panel data methods.
- Explore cross-industry comparisons to highlight sector-specific innovation drivers.

## Coursework
- **Coursework:** Completed for BA875 - Supply Chain Analytics course (Boston University MSBA program), with a focus on advanced regression analysis, business model interpretation, and evidence-based recommendations.
- **Contributors:**
  - Gunjan Sharma
  - Jasmine Gohil
  - Jenil Shah
  - Mahika Bhartari
  - Sneha Ekka

## Additional Resources
- 📊 [Project Presentation Deck](https://www.canva.com/design/DAGEB5LlB84/Di1UATQ8UfilIrRj47f1nA/view?utm_content=DAGEB5LlB84&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h22e9e9ffc1)
