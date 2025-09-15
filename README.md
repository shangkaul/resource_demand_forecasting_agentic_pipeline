# resource_demand_forecasting_agentic_pipeline
Mini demo using LangGraph + LangSmith on the Kaggle Restaurant Visitor dataset. Loads CSV, cleans data, optionally normalizes with an LLM, and forecasts 7 days ahead using ARIMA. Confidence-based routing simulates human-in-loop. Shows how LangGraph adds AI orchestration vs pure ETL (Airflow/Databricks).



```
conda env create -f environment.yml
conda activate forecast-demo
```