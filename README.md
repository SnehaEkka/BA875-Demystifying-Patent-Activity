**Project Summary: Patents, Innovation, and Company Performance**
This project investigates the relationship between a company's internal drivers, patents, and its overall performance.

**Data Sources:**
Financial data (Compustat & WRDS) including revenue, profit, R&D expenses, and return on assets (ROA)
Patent data (2 datasets) containing information on patent activity and yearly summaries

**Key Internal Drivers:**
R&D Expenditure: Investment in research and development
Number of Patents: Overall patenting activity

**Patent Characteristics:**
Type: Functional vs. Design patents (removed due to collinearity)
Year Applied For
Industry of the company

**External Pressures:**
Competitors: Drive for innovation and benchmarking
Regulations: Compliance with patent standards and environmental regulations
Consumer Adoption: Importance of novel products for market share and loyalty

**Analysis:**
Regression models examined how internal drivers and patent characteristics affect:
Return on Assets (ROA): A profitability measure
Patent counts: Functional and Design (later removed)

**Findings:**
All variables showed a statistically significant influence on the dependent variables (ROA, patent counts). However, the effect size was relatively small.
The model for ROA was considered reliable (no multicollinearity).
Models for functional and design innovation patents suffered from multicollinearity (correlation between independent variables) and were excluded from further analysis.

**Challenges:**
Missing data in financial ratios limited the ability to explain variations in performance.
High computational costs were encountered during analysis.
High collinearity between functional and design patent counts prevented their independent analysis.

Overall, the project highlights the complex relationship between internal drivers, patents, and company performance. While patents and R&D influence performance, other factors likely play a significant role.
