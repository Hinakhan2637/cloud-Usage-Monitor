Project Description:
The AWS Cloud Usage Monitor is a comprehensive cloud monitoring web application designed to provide real-time insights, historical analysis, and regional breakdowns of cloud resource consumption. This project simulates how organizations can monitor and optimize their cloud infrastructure—particularly across Agent-Based, Resource-Based, and Polling-Based monitoring systems.

🎯 Objectives:
Visualize and track CPU, memory, and bandwidth usage in real time.

Identify performance trends over time with historical charting.

Understand geographical distribution of cloud workloads.

Demonstrate different types of monitoring methods with interactive 3D visuals.

Provide IT administrators and decision-makers with actionable insights to improve performance and reduce cloud costs.

🧰 Key Features:
✅ Dashboard (index.html):
Tab-based system for switching between monitoring types:

Agent-Based: Tracks background agents and sync operations.

Resource-Based: Monitors CPU, memory, I/O resource utilization.

Polling-Based: Periodically fetches system data for tracking.

Animated 3D cloud icon changes color/style depending on monitoring type.

Live mini chart to show recent performance (CPU %).

Central panel shows detailed graphs (bar, line, radar, pie, bubble).

Right panel shows alerts, machine count, and monitoring role descriptions.

Chart type selector to customize visualizations.

Dynamic alerts for usage spikes.

✅ Historical Trends Page (history.html):
Date-range picker using a calendar (customizable).

Multiple dataset line chart displaying CPU, Memory, and Storage usage.

Export chart feature to download performance reports.

Country-wise usage map using Leaflet.js to simulate regional cloud workload analysis.

📊 Technology Stack:
HTML5, CSS3, JavaScript

Chart.js – Dynamic charts and graphs

Leaflet.js – Interactive map for geographical usage

Mock Data Simulation – Randomly generated metrics to simulate usage trends

🚀 Use Case & Practical Relevance:
This project can be used in:

Educational demos to explain cloud monitoring mechanisms.

Corporate training sessions on cloud cost control.

Startup or DevOps teams prototyping internal cloud dashboards.

