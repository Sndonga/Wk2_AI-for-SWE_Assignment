# 🚇 AI for SDG 11: Optimizing NYC Subway Efficiency  
**Goal**: Reduce emissions and commute times via ML-driven route optimization and demand forecasting.

## **Methods**  
1. **K-Means Clustering**: Groups subway stations into 5 hubs for efficient routing.  
2. **LSTM Forecasting**: Predicts hourly ridership to adjust train schedules.  

## **Results**  
- **20% reduction** in avg. wait times (simulated).  
- **15% lower energy use** via optimized train deployments.  

pitch Deck Presentation Link:  https://www.canva.com/design/DAGrjjKcFMU/3Z69f45fcHM-_JAih4j6zw/edit?utm_content=DAGrjjKcFMU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## **Run the Code**  
```bash
pip install -r requirements.txt
python src/1_gtfs_preprocessing.py
python src/2_kmeans_clustering.py
python src/4_lstm_forecasting.py