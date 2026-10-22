# Website Traffic Analysis
Analysis of website traffic data to explore user behaviour, traffic patterns, website performance, and data-driven insights.

# Website Traffic & User Journey Analytics

# Project Overview
An end-to-end exploratory analysis of e-commerce website traffic and user behavior using event-level customer journey data.

# Dataset
- Events: 12,719
- Sessions: 5,000
- Users: 1,872
- Time period: 2025-01-01 to 2025-08-31
- Page types: home, product_page, cart, checkout, confirmation
- Devices: Desktop, Tablet, Mobile
- Referral sources: Social Media, Email, Direct, Google

# Key Metrics
- Bounce rate (single-event session definition): 20.26%
- Conversion rate (purchased sessions / sessions): 20.20%
- Average pages per session: 2.54
- Average session duration: 150.05 seconds
- Cart abandonment: 36.84%
- Checkout abandonment: 10.06%

# Key Findings
1. `home` is the most frequently observed page type.
2. `Google` generates the highest session volume.
3. `Google` has the highest conversion rate among referral sources.
4. `Desktop` has the highest device-level conversion rate.
5. `Desktop` has the highest device-level bounce rate.
6. `product_page` is the most common exit page.
7. The most common reconstructed journey is `home → product_page` with 2,388 sessions.

# Project Structure
- `data/processed/` - cleaned event data and session-level features
- `notebooks/` - reproducible analysis notebook
- `dashboards/` - visual outputs
- `docs/` - methodology and data dictionary

# Tools
Python, Pandas, NumPy, Matplotlib, Jupyter Notebook.

