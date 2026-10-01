# India Analytics Hub

Build and deploy a professional, interactive Digital India Progress Analytics SaaS-style analytics web application on Hatchable.

1. PROJECT OBJECTIVE

Create an academic and portfolio-grade analytics platform using the uploaded Digital India dataset as the single source of truth.

The application should analyze:

Government scheme funding

Fund utilization

Beneficiary reach

Digital transactions

State-level observations

District-level observations

Scheme-level performance

Regional comparisons

Funding allocation vs observed outcomes

Do NOT invent, randomly assign, estimate, or fabricate any state, district, city, funding, beneficiary, transaction, historical, or performance data.

Display clearly:

Academic / Portfolio Analytics Project — Not an Official Government of India Website

2. DATA UPLOAD & VALIDATION

Create a prominent Upload Dataset feature supporting:

.xlsx

.xls

.csv

Primary dataset:

DigitalIndia_PowerBI_DataModel(2).xlsx

After upload:

Read the workbook.

Automatically detect the relevant worksheet.

Detect available columns.

Validate the dataset.

Show row count.

Show available fields.

Dynamically calculate all KPIs.

Never hard-code analytical results.

Potential fields:

Scheme

Ministry

State

District

Region

Quarter

Year

Fund Released

Fund Utilized

Utilization %

Beneficiaries

Transaction Count

Transaction Value

Status

If a field does not exist, hide the related visualization instead of creating fake data.

3. PROFESSIONAL UI DESIGN

Create a polished enterprise/government-data analytics command center.

Visual style

Deep navy

White

Professional blue

Subtle saffron accent

Subtle green accent

Clean KPI cards

Thin borders

Minimal shadows

Rounded corners

Professional typography

Responsive layout

Desktop-first but mobile responsive

Avoid:

Excessive gradients

Cartoon graphics

Excessive animations

Fake government branding

Unverified government logos

Overcrowded layouts

Header

Digital India Progress Analytics

Subtitle:

Funding • Utilization • Beneficiary • Transaction Intelligence

Badge:

Academic Analytics Project

Footer:

Academic / Portfolio Project • Data-driven analysis • Not an Official Government Website

Use a clean left sidebar navigation.

4. ONLY 5 MAIN PAGES

Do NOT create 10 separate pages.

Create exactly these 5 main navigation pages:

01 — Overview

02 — Geography

03 — Schemes & Funding

04 — Impact & Transactions

05 — AI Insights

Use icon + short title in the sidebar.

All detailed analysis must be organized inside these five pages using sections, tabs, drilldowns, expandable panels, and interactive charts.

5. GLOBAL FILTER BAR

Place a professional filter bar below the main header.

Available filters:

Year

Quarter

Ministry

Scheme

Region

State

District

Status

Also provide a global search supporting:

State

District

Scheme

Ministry

Add:

Reset Filters

All KPIs, maps, charts, tables, and AI insights must respond dynamically to the selected filters.

6. PAGE 01 — OVERVIEW

Create a highly polished executive dashboard.

KPI Cards

Display:

Total Beneficiaries

Funds Released

Funds Utilized

Utilization %

Transaction Count

Transaction Value

States Covered

Schemes Covered

Each KPI card should contain:

Icon

Main value

Short label

Optional comparison only when valid historical data exists

If only one year exists, do not display fake YoY values.

Overview Visuals

Include:

Funding Overview

Compare:

Funds Released vs Funds Utilized

Beneficiary Overview

Show observed beneficiary reach.

Transaction Overview

Show:

Transaction Count

Transaction Value

Regional Overview

Show regional distribution when Region exists.

Key Observations

Show 3–4 dynamically generated neutral observations.

Use language such as:

Highest observed

Lowest observed

Above selected average

Below selected average

Do not use political or subjective labels.

7. PAGE 02 — GEOGRAPHY

This page combines:

India Map + State Analytics + District Analytics

Do NOT create separate State or District pages.

India Map

Create a professional India state-level choropleth map.

Allow metric switching:

Funding Released

Funding Utilized

Utilization %

Beneficiaries

Transaction Count

Transaction Value

Use a professional blue intensity scale.

Map Interaction

Click State → filter the page/dashboard

After selecting a state, dynamically update:

KPIs

Funding

Utilization

Beneficiaries

Transactions

Schemes

Districts

State Analysis

Below the map, provide an interactive state analysis section.

Show:

Funding

Funds Released

Funds Utilized

Utilization

Utilization % = Funds Utilized / Funds Released × 100

Beneficiary Reach

Show beneficiary totals by state.

Transaction Activity

Show:

Transaction Count

Transaction Value

Allow sorting by each metric.

Use neutral terminology.

Do not label states as:

Best

Worst

Most developed

Least developed

District Drilldown

Implement:

India → State → District

When a state is selected, display its districts.

Show:

District

Fund Released

Fund Utilized

Utilization %

Beneficiaries

Transaction Count

Transaction Value

Status

Create an interactive table with:

Search

Sorting

Filtering

Pagination

If City does not exist in the dataset, do not create city data.

8. PAGE 03 — SCHEMES & FUNDING

This page combines:

Scheme Analytics + Funding Intelligence

Do NOT create separate Scheme or Funding pages.

Scheme Analysis

Show:

Scheme Funding

Funds released by scheme.

Scheme Utilization

Funds utilized and utilization percentage.

Scheme Beneficiary Reach

Beneficiaries by scheme.

Scheme Transaction Activity

Transaction Count

Transaction Value

Use:

Horizontal bar charts

Compact tables

KPI cards

Donut charts only where useful

Avoid excessive vertical bar charts.

Funding Allocation

Analyze Fund Released by:

State

Scheme

Region

District

Analyze Fund Utilized by:

State

Scheme

Region

District

Utilization Efficiency

Calculate:

Utilization % = Fund Utilized / Fund Released × 100

Use clear visual indicators but avoid subjective performance ratings.

Funding vs Beneficiary Reach

Create an interactive scatter plot.

X-axis:

Funds Utilized

Y-axis:

Beneficiaries

Bubble size:

Transaction Value

Use this only as an observed association.

Display:

Correlation or association does not establish causation.

Do not claim that funding causes development.

9. PAGE 04 — IMPACT & TRANSACTIONS

This page combines:

Beneficiary Impact + Transaction Analytics + Funding & Observed Outcomes

Beneficiary Analysis

Show:

Total Beneficiaries

Beneficiaries by State

Beneficiaries by Scheme

Beneficiaries by District

Beneficiary reach vs funding

Create an interactive table:

| State | Scheme | Funds Utilized | Beneficiaries | Transactions |

Allow sorting and filtering.

Transaction Analysis

Show:

Transaction Count

Total observed transactions.

Transaction Value

Total transaction value.

Average Transaction Value

Calculate only when valid transaction fields exist.

Transaction Value by State

Transaction Value by Scheme

Transaction Trend

Use Quarter/Year only if these fields actually exist.

Never manufacture historical trends.

Funding & Observed Outcomes

Create a section:

Funding → Utilization → Observed Reach

Analyze relationships between:

Funding

Utilization

Beneficiaries

Transactions

Do NOT automatically interpret this as:

Funding → Development

unless a legitimate development outcome variable exists.

Add:

Funding and observed beneficiary/transaction metrics should not be interpreted as proof of causation.

10. PAGE 05 — AI INSIGHTS

Create an interactive AI-powered insights page.

The AI must analyze only the currently filtered dataset.

Generate 4–6 concise insights.

Each insight should follow:

Fact → Observation → Possible Interpretation

Example:

Fact: The selected records show a higher utilization percentage in certain states.
Observation: These states account for a larger share of utilized funds within the selected data.
Interpretation: This may indicate differences in observed fund utilization patterns.

Do not make unsupported claims.

Never generate statements such as:

“This funding caused development.”

“This is the best state.”

“This is the worst state.”

“This state is underdeveloped.”

“The government succeeded because of this scheme.”

Display:

AI-generated insights are analytical observations and should not be treated as official government conclusions.

11. DATA NOTES INSIDE AI INSIGHTS PAGE

Do NOT create a separate Data Notes page.

Place a Data Quality & Methodology section at the bottom of Page 05.

Display:

Dataset row count

Number of states

Number of districts

Number of schemes

Available years

Missing-value summary

Available fields

Also display:

Limitations

Dataset coverage depends on the uploaded source.

Funding does not automatically represent development.

Correlation does not establish causation.

Missing geographic fields must not be inferred.

City-level analysis requires legitimate city-level data.

Historical trends require multiple years.

This is an academic/portfolio analytics project.

12. CITY-LEVEL RESTRICTION

Do NOT randomly assign cities such as:

Mumbai

Pune

Nashik

Nagpur

Delhi

Bengaluru

Only show city-level analysis if a legitimate City field exists in the uploaded dataset or a verified additional dataset is provided.

If no City field exists, display:

City-level analysis is unavailable because the supplied dataset does not contain verified city-level observations.

13. URBAN VS RURAL

Do not create Urban/Rural categories unless a legitimate field exists.

If unavailable, display:

Urban/Rural comparison is not available in the current dataset.

14. HISTORICAL / YOY ANALYSIS

If multiple years exist, calculate:

YoY Growth % = (Current Year − Previous Year) / Previous Year × 100

Show where applicable:

Funding YoY

Utilization YoY

Beneficiary YoY

Transaction YoY

If only one year exists, hide YoY charts and show:

Historical comparison requires multiple years in the source dataset.

15. INTERACTIVE UX

Implement:

Interactive India map

State → District drilldown

Cross-filtering

Tooltips

Hover states

Search

Sorting

Pagination

Reset Filters

Dynamic KPI updates

Dynamic charts

Responsive design

Export table data where technically possible

Keep animations subtle and professional.

16. DATA ACCURACY RULES

This is mandatory.

Never:

Invent values

Randomly assign states

Randomly assign districts

Randomly assign cities

Create fake funding

Create fake beneficiaries

Create fake transactions

Create fake historical years

Create fake government statistics

Present assumptions as official data

Every metric must trace back to the uploaded dataset.

If information is unavailable:

Hide the visualization or clearly state that the metric is unavailable.

17. TECHNICAL REQUIREMENTS

Use:

React

TypeScript

Tailwind CSS or clean modern CSS

D3.js or another suitable chart/map library

Client-side Excel/CSV parsing

Hatchable AI integration

Keep the code modular.

Separate:

Data ingestion

Data transformation

KPI calculations

Filters

Charts

Map

AI insights

UI components

18. FINAL DESIGN REQUIREMENT

The final application should feel like a professional analytics command center, not a basic student dashboard.

Prioritize:

Clean → Professional → Interactive → Data-driven → Portfolio-ready

The sidebar should contain only:

01 Overview
02 Geography
03 Schemes & Funding
04 Impact & Transactions
05 AI Insights

Do not add unnecessary pages.

The final title:

Digital India Progress Analytics

Subtitle:

Data-Driven Analysis of Funding, Utilization, Beneficiary Reach & Digital Transactions

Footer:

Academic / Portfolio Project • Data-driven analysis • Not an Official Government Website

Finally:

Test Excel/CSV upload.

Test all filters.

Test India map interaction.

Test State → District drilldown.

Verify all KPIs dynamically update.

Verify charts use uploaded data.

Verify AI insights respect filters.

Check for console errors.

Check desktop and mobile responsiveness.

Remove broken components and unused pages.

Deploy the finished application on Hatchable.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/79bbf03b-3084-4fc0-bdd2-ff77ecd8096c).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
