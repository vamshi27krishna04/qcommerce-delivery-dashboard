## **Q-Commerce Tracker: Measuring Instant Delivery Market Performance**

### **Project Overview**

Interactive dashboard and exploratory data analysis for monitoring quick commerce (Q-commerce) delivery performance. This project identifies operational bottlenecks, quantifies customer expectation gaps, and provides actionable insights for logistics optimization.

### **Key Findings**

| Metric | Value |
|--------|-------|
| Customer expectation (≤30 min) | 95.4% |
| Actual performance (≤30 min) | 11.8% |
| **Expectation gap** | **83.6 percentage points** |
| Best performing period | Night (55.2 min avg) |
| Worst performing period | Evening (57.5 min avg) |
| Traffic impact | +12.8 min in high traffic |
| Weather impact | +7.4 min in fog |

### **Datasets**

- **Consumer Behavior Survey**: 109 responses on delivery expectations and platform preferences
- **Operational Delivery Data**: 1,000 delivery records with weather, traffic, and timing metrics

### **Dashboard Features**

- **Interactive filter buttons** (All, Morning, Afternoon, Evening, Night)
- **Real-time KPI cards** showing average time, fast %, expectation %, and gap
- **Three coordinated visualizations**:
  - Performance by time period (color-coded bar chart)
  - Traffic × weather heatmap (operational bottlenecks)
  - Expectation vs. actual gap analysis
- **Responsive dark-theme design** optimized for managerial presentation

### **Technologies**

- Python (Pandas, Plotly)
- HTML/JavaScript (standalone dashboard export)
- Jupyter Notebook (analysis and data preparation)

### **Files**

| File | Description |
|------|-------------|
| `dashboard.html` | Interactive standalone dashboard |
| `survey_data_cleaned.csv` | Cleaned consumer survey data |
| `delivery_data_cleaned.csv` | Cleaned operational delivery data |
| `hypothesis*.png` | Static analysis charts |


### **Usage**

Open `dashboard.html` in any modern web browser. Click time-period buttons to filter all visualizations and KPIs.

