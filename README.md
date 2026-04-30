# Cyber Data Science Hunt Prototype
A cyber security Jupyter Notebook project demonstrating hypothesis testing, anomaly detection modeling, and customer-facing insights.

This notebook uses simulated Air Force LAN dataset to show how to quickly analyze new data feeds, find hidden patterns, and turn them into automated detections.

The notebook utilizes:
- pandas, numpy, seaborn, and scikit libraries
- independent T-Test with 0.05 p-value
- violin plot for large dataset to show packet duration separation between Normal and Attack Traffic
- correlation heatmap to show hotspots of privesc activity
- isolation forest modeling to determine potential anomalies
- PCA projection plot to show enough distinct network traffic is malicious to create actionable queries

## Screenshots
<img width="895" height="552" alt="Screenshot from 2026-04-29 23-55-08" src="https://github.com/user-attachments/assets/41b815fd-1a50-47b8-9629-99bd1bb04dc8" />
<img width="895" height="552" alt="Screenshot from 2026-04-30 01-34-40" src="https://github.com/user-attachments/assets/6fe9ebfb-0b52-4477-af47-cf9d63cb0e7e" />
<img width="1074" height="845" alt="Screenshot from 2026-04-30 01-44-11" src="https://github.com/user-attachments/assets/48860b76-c63f-4987-af3f-2f9b201c43c2" />
