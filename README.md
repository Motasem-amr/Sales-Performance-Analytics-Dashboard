# Creo Technologies Sales & Performance Dashboard

A comprehensive Power BI analytics solution transforming 3 years of sales data into actionable business intelligence for strategic decision-making.

## 📊 Project Overview

This capstone project was developed as part of the Route Data Analysis Diploma. The dashboard provides Creo Technologies stakeholders with real-time visibility into sales performance, revenue trends, and market opportunities through interactive visualizations and automated insights.

### Business Objectives
- Track and monitor 10 core business KPIs with automated performance indicators
- Analyze year-over-year growth patterns and seasonal trends
- Identify regional performance drivers and market expansion opportunities
- Forecast order volumes to support capacity planning and resource allocation

## 🎯 Key Features

### 1. KPI Performance Engine
- **Automated Metrics Tracking**: 10 core business indicators with real-time calculations
- **Conditional Status Logic**: Dynamic thresholds identifying "Achieving" vs "Under-achieving" performance
- **Alert System**: Visual indicators highlighting metrics requiring immediate attention

### 2. Time-Series Analytics
- **YoY Growth Analysis**: Comparative performance across 3-year period
- **Profit Margin Tracking**: Trend identification and margin compression analysis
- **Seasonal Pattern Recognition**: Sales cycle behaviors and promotional lift measurement
- **Promotional Impact Assessment**: Quantifying campaign effectiveness

### 3. Geospatial Intelligence
- **Hierarchical Filtering**: Continent → Country → Region drill-down capability
- **Sales Distribution Mapping**: Visual representation of revenue by geography
- **Market Performance Comparison**: Identifying high-performing and underperforming regions
- **Expansion Opportunity Identification**: Data-driven market entry recommendations

### 4. Predictive Forecasting
- **Order Volume Predictions**: Statistical forecasting for medium-term planning
- **Trend Projection**: Future performance expectations based on historical patterns
- **Capacity Planning Support**: Resource allocation insights

## 🛠️ Technical Stack

- **Primary Tool**: Microsoft Power BI Desktop
- **Data Preparation**: SQL queries, Power Query (M language)
- **Calculations**: DAX (Data Analysis Expressions)
- **Data Modeling**: Star schema, relationship optimization
- **Forecasting Methods**: Time-series statistical models
- **Version Control**: Git/GitHub

## 📁 Repository Structure

```
creo-technologies-dashboard/
│
├── data/
│   ├── raw/                    # Original datasets
│   ├── processed/              # Cleaned and transformed data
│   └── data-dictionary.md      # Field descriptions and metadata
│
├── scripts/
│   ├── data-cleaning.sql       # SQL data preparation queries
│   └── power-query-steps.txt   # Power Query transformation steps
│
├── dashboard/
│   ├── creo-dashboard.pbix     # Main Power BI file
│   └── dax-measures.txt        # Key DAX formulas and calculations
│
├── documentation/
│   ├── technical-specs.md      # Technical specifications
│   ├── user-guide.md           # Dashboard navigation guide
│   └── insights-summary.md     # Key findings and recommendations
│
├── assets/
│   └── screenshots/            # Dashboard visualizations
│
└── README.md
```

## 📈 Dashboard Components

### Page 1: Executive Summary
- High-level KPI cards with trend indicators
- Revenue and profit overview
- Performance status at-a-glance

### Page 2: Sales Performance
- Detailed sales trends over time
- Product category breakdown
- Customer segment analysis

### Page 3: Geographic Analysis
- Interactive map visualization
- Regional performance comparison
- Market penetration metrics

### Page 4: Forecasting & Insights
- Order volume predictions
- Growth projections
- Strategic recommendations

## 🔍 Key Insights Delivered

1. **Revenue Growth**: Identified 23% YoY growth in Q3-Q4 driven by promotional campaigns
2. **Regional Opportunities**: European market showing 15% higher profit margins compared to other regions
3. **Product Performance**: Top 3 product categories generating 67% of total revenue
4. **Seasonal Patterns**: Clear Q4 spike indicating strong holiday season performance
5. **Forecast Accuracy**: Predictive model achieving 92% accuracy for 3-month order projections

## 🚀 Getting Started

### Prerequisites
- Microsoft Power BI Desktop (latest version recommended)
- Basic understanding of Power BI interface
- Familiarity with business intelligence concepts

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/creo-technologies-dashboard.git
```

2. Navigate to the dashboard folder:
```bash
cd creo-technologies-dashboard/dashboard
```

3. Open the `.pbix` file in Power BI Desktop

4. Refresh data connections if needed

### Usage

1. **Navigation**: Use the page tabs at the bottom to switch between dashboard views
2. **Filtering**: Apply slicers to filter data by date, region, product, or category
3. **Drill-Down**: Click on visual elements to drill down into detailed data
4. **Export**: Use Power BI's export features to share insights as PDF or PowerPoint

## 📊 Data Sources

*Note: This project uses simulated/anonymized data for educational purposes*

- **Sales Transactions**: 3 years of order history (2011-2013)
- **Product Catalog**: Product hierarchy, categories, and pricing
- **Geographic Data**: Regional and country-level information
- **Customer Records**: Anonymized customer segments and demographics
- **Promotional Calendar**: Campaign dates and performance metrics

## 🎓 Learning Outcomes

This project enhanced my capabilities in:
- Advanced DAX formula creation and optimization
- Complex data modeling and relationship management
- Interactive visualization design principles
- Business storytelling through data
- Performance optimization for large datasets
- User-centric dashboard design
- Statistical forecasting techniques

## 🙏 Acknowledgments

- **Route Academy**: For the comprehensive Data Analysis Diploma program
- **Eng. Hamdy Saied**: Technical mentorship and DAX guidance
- **Eng. Nouran Elslisly**: Dashboard design and visualization best practices
- **Project Team**: Philopater Maher , Mazen tamer , Ahmed Walid - collaborative development and peer review


---

⭐ If you found this project helpful, please consider giving it a star!

**Project Status**: Completed (January 2026)
