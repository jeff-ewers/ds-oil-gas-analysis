# Oil & Gas Service Price Analysis

## Overview
This project analyzes price dynamics and operational relationships in the oil and gas service sector, focusing on the interplay between commodity prices, service costs, and operational metrics. The analysis spans 33 quarters of data (excluding COVID-19 impact period) to provide insights into market responses and cost relationships across the drilling and completion value chain.

## Business Context
The analysis addresses critical business questions about price elasticity, operational cascades, and cost relationships in oil and gas operations, with particular emphasis on:
- Service segment price responses to commodity prices
- Activity level elasticity and operational timing
- Cost relationships within drilling and completion phases
- Impact of efficiency improvements on traditional pricing relationships

## Technical Architecture

### Development Environment
- Python 3.x
- Jupyter Notebook
- Google Cloud Platform for data storage and access

### Core Dependencies
```
python
pandas==2.0.0
numpy==1.24.0
scipy==1.10.0
seaborn==0.12.0
matplotlib==3.7.0
google-cloud-bigquery==3.11.0
db_dtypes==1.1.1
```

### Data Pipeline
1. Data extraction from BigQuery
2. Preprocessing and validation
3. Moving average calculations
4. Lag structure implementation
5. Statistical analysis and visualization

## Key Features

### Data Validation and Preprocessing
- Timestamp consistency checking
- Missing value detection
- Quarterly continuity validation
- Data type verification

### Analysis Components
- Price elasticity calculations using bootstrap methodology
- Correlation analysis with significance testing
- Activity cascade analysis
- Completion intensity metrics
- COVID-19 period sensitivity analysis

### Visualization
- Operational cascade relationships
- Completion intensity trends
- Price elasticity heatmaps
- Phase correlation matrices
- Methodology comparison plots




## Methodology Highlights

### Statistical Framework
- Bootstrap-based elasticity calculations for robust error estimation
- Industry-informed lag structure implementation
- Significance testing aligned with business materiality thresholds
- Moving average smoothing for trend analysis

### Analysis Hierarchy
1. Basic correlation analysis on full timeline
2. COVID-19 period sensitivity testing
3. Lag-adjusted correlation analysis on normal operations
4. Elasticity calculations with bootstrap confidence intervals
5. Activity cascade and efficiency trend analysis

## Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Configuration
1. Set up Google Cloud credentials
2. Configure BigQuery access
3. Update query parameters in notebook

### Running the Analysis
```
The full analysis is displayed in the Jupyter notebook with output

```

## Key Findings
The analysis reveals several important insights:
- Strong correlations between WTI and service costs after accounting for operational lags
- Distinct price elasticity patterns across service segments
- Clear operational cascade effects from price signals to activity levels
- Significant efficiency improvements in completion intensity metrics


## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Continental Resources for project sponsorship
- Industry subject matter experts for lag structure validation
- BigQuery team for data infrastructure support
