<h1> Analyzing AWS SaaS Company Transactions </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus is to optimizing profit.

Key Objectives:
- Objective 1: Analyzing profit based on sales
- Objective 2: Analyzing purchase habits of customers from certain industries

## 2. Data Sources
- [Dataset 1] (https://ee-assets-prod-us-east-1.s3.amazonaws.com/modules/337d5d05acc64a6fa37bcba6b921071c/v1/SaaS-Sales.csv) - This dataset contains transaction data from a fictitious SaaS company selling sales and marketing software to other companies (B2B), from January 4th, 2020 to December 31st, 2023.

## 3. Technologies Used
- Programming Language: Python
- Visualization: Matplotlib, Seaborn
- Interactive Dashboard: Tableau
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-mdl-initial-data-exploration`.
│
├── reports            <- Generated analysis as PDF 
│   └── slide          <- Generated PDF
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight
1. Alchemy, Site Analytics, and Data Smasher were the most profitable products for the company, generating substantial profits. The most sought out product, ContactMatcher, had comparably lower profits compared to those three products. Meanwhile, Marketing Suite's sales performed the worst, incurring negative profits (losses) over the years, which might need further investigation into its cost structure, sales strategy, or market demand.
2. Profit is potentially negatively affected by discount. Discounting products might not be an effective strategy to increase profit.
3. The highest amount of demand for all softwares came from Small- to Medium-Sized Finance Industries, with the software they demanded the most being ContactMatcher. However, despite generating the most profits over the years, Alchemy was the least sought out software by this customer group.
### 5.2 Actionable Recommendation
1. Apply strategies that can expose ContactMatcher and Marketing Suite to more customers, for example by providing free trial versions of the software or introducing those softwares
2. Try to find other marketing strategies besides discounting prices. For example, bundle MarketingSuite with another product, ContactMatcher, in particular, into a single package. This strategy helps increase sales, improve customer retention, and enhance overall customer satisfaction.
3. SMBs tend to be less reserved in spending as their aim is to grow, and more likely to see spending on business process improvement, like lead generation, as an investment. Explain plainly and directly to these customers the immediate benefits of using Alchemy, such as increased sales, improved customer satisfaction, and enhanced customer retention.

## 6. Contact
- Name: Muhammad Dhany Latief
- Email: m.dhany.latief@gmail.com
- Linkedin: https://www.linkedin.com/in/dhany-latief-22a674241/
- Tableau Public: https://public.tableau.com/app/profile/dhan.l/vizzes