# Figures

This folder contains the visual outputs generated during the Marketing Measurement Model analysis.

The figures are organized according to the major stages of the analytical workflow.

## Figure Categories

### 1. Exploratory Data Analysis

Figures related to the initial exploration of the marketing dataset.

Examples:

- Weekly conversion trends
- Channel-level marketing spend
- Channel spend distributions
- Correlation analysis
- Marketing channel comparisons

### 2. Model Fit

Figures used to evaluate the performance of the Bayesian Marketing Mix Model.

Examples:

- Actual vs predicted KPI
- Model fit over time
- Baseline vs expected KPI
- Credible intervals

### 3. Channel Contribution

Figures showing the modeled incremental contribution of each marketing channel.

Examples:

- Channel contribution comparison
- Incremental KPI by channel
- Contribution share

### 4. ROI and Marginal ROI

Figures presenting channel-level efficiency measures.

Examples:

- ROI comparison
- Marginal ROI comparison
- ROI uncertainty intervals

### 5. Response Curves

Figures showing the relationship between marketing spend and modeled incremental KPI.

These visualizations demonstrate:

- Media response
- Diminishing marginal returns
- Channel-specific response behavior
- Incremental KPI as spending changes

### 6. Budget Optimization

Figures generated from the constrained budget optimization analysis.

Examples:

- Historical vs optimized allocation
- Channel budget changes
- Optimized KPI comparison
- Budget allocation comparison

### 7. Sensitivity Analysis

Figures showing how optimization results change under different budget constraints.

The project evaluates:

- ±20% constraints
- ±30% constraints
- ±50% constraints

## Recommended Structure

```text
figures/
│
├── README.md
│
├── eda/
│   ├── weekly_conversions.png
│   ├── channel_spend.png
│   └── correlation_heatmap.png
│
├── model_fit/
│   └── meridian_model_fit.png
│
├── contribution/
│   └── channel_contribution.png
│
├── roi/
│   └── roi_mroi.png
│
├── response_curves/
│   └── response_curves.png
│
└── budget_optimization/
    ├── budget_allocation.png
    └── sensitivity_analysis.png
