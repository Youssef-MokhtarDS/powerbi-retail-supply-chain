E-Commerce Executive Dashboard & Supply Chain Optimization
A comprehensive, executive-ready Power BI reporting solution built to analyze retail sales performance, market basket cross-selling opportunities, and fulfillment shipping cost efficiency. This dashboard bridges top-line revenue velocity with bottom-line profitability, translating raw transactional data into actionable pricing, cross-selling, and fulfillment strategies.

Executive Summary & Impact
Profitability Preservation: Identified that top revenue drivers (e.g., Taste of the Wild 40lb at $270.4K) require strategic item pairing to mitigate freight and shipping cost overlays.

Cross-Sell Optimization: Evaluated product co-occurrence to isolate high-margin impulse accessories (e.g., UltraSound Barking Deterrent at 25.68% margin) while eliminating category mismatches at checkout.

Fulfillment Savings: Pinpointed fulfillment cost variances across geographic regions and unit quantities, demonstrating that volume upsells (e.g., "Buy 2") significantly reduce per-unit shipping overhead for high-volume categories like Disposables (averaging 3.17 units/order).

Dashboard Architecture & Key Pages
1. Executive Summary
KPI Header: Tracks core metrics including Total Sales, Baseline Profit, Profit Margin %, and Baseline Shipping Cost.

Interactive Breakdown: Custom Treemap displaying Profit Margin by Product Category & Description.

Dynamic Interactivity: Configured cross-filtering rules between Treemaps, geographic maps, and KPI card visuals for seamless executive slice-and-dice navigation.

2. Market Basket Analysis
Product Performance Grid: Matrix visual detailing Description, Total Sales, and Profit % across the entire catalog.

Margin Variance Sorting: Isolates product margin spread across all SKUs (-1.52% to 63.85%).

Strategic Cross-Selling: Cross-evaluates revenue anchors against high-margin accessories to optimize checkout recommendation engines.

3. Shipping Metrics & Supply Chain
Geographic Analysis: Geographic maps and structured matrix breakdowns visualizing Shipping Cost by State and Region with % of Grand Total indicators.

Volume Distribution: Bar charts displaying Average Quantity by Category to identify quantity discount thresholds.

Cost Impact Modeling: Dual-axis visualization tracking the impact of order volume on total shipping expenditure.

Technical Stack & Data Engineering
BI Platform: Microsoft Power BI Desktop
Data Architecture: Star Schema Model (Sales Fact Table, Products Dim Table, State Mapping Dim Table)
Core DAX Implementations:
