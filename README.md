# Analyzing-KPI-Degradation-Report
 Project Objective: To analyze Key Performance Indicator (KPI) degradation in a telecom Radio Access Network (RAN) dataset. By visualizing the relationships between various KPIs, alarms, and cell health, the goal was to pinpoint specific parameters and regions contributing to network instability and poor performance. 

 
 Key Findings & Insights: 
• Identified specific Site IDs with consistently unhealthy cells, often correlated with high ERAB Drop Rates and low RRC Success Rates, ENDC drop etc. 
• Discovered regional disparities in cell health and alarm counts, with certain regions exhibiting higher concentrations of critical alarms (e.g., NewYork had the highest total alarm count). 
• Visualized the interplay between multiple KPIs (ERAB Drop Rate, RRC Success Rate, DL Throughput) and Cell Health, revealing that degraded throughput often accompanies poor cell health and higher drop rates. 
• Categorized alarm types by region, providing granular insights into prevalent issues (e.g., Transmission Alarms were a significant contributor across several regions).


Technologies & Libraries Used: 
• Python 
• Pandas (for data manipulation and analysis) 
• Matplotlib (for comprehensive data visualization) 
• Seaborn (for enhanced statistical plots) 
• Google Colab (for development and execution environment)
