# User Activity Pattern Detection using Apache Spark

> A Big Data Analytics project that detects e-commerce user behavior patterns and anomalies using Apache Spark and Streamlit.


## 🔗 Live Dashboard
👉 [Click Here to View the Live App](https://sparkuseractivityproject-ysse8bezamytzuddn9g5nq.streamlit.app/)


## Project Overview

This project analyzes how users interact with an e-commerce platform by tracking events such as product views, cart additions, and purchases.

The data is processed using Apache Spark to identify patterns like peak activity hours, popular products, and unusual user behavior.

The results are visualized through an interactive Streamlit dashboard featuring charts, funnels, and anomaly reports.

---

## Project Structure
```
spark_user_activity_project/
│
├── user_activity_spark.py
├── streamlit_app.py
├── ecommerce_user_activity.csv
└── requirements.txt
```


## Tech Stack

| Technology | Purpose |
|------------|---------|
| Apache Spark / PySpark | Distributed data processing |
| Python 3 | Programming language |
| Pandas | Data manipulation |
| Plotly | Data visualization |
| Streamlit | Dashboard development |
| GitHub | Version control |


## How It Works

**Step 1 — Dataset Design**  
A synthetic dataset of 103 records representing 20 users was created.

**Step 2 — Spark Processing**  
- Load CSV data  
- Clean null values  
- Extract time-based features  
- Perform aggregations  

**Step 3 — Pattern Detection**  
Analyze user journey using funnel:  
View → Cart → Purchase  

**Step 4 — Anomaly Detection**  
- Rule-based: 5+ views with no purchase → High risk  
- Statistical: Mean + 2 standard deviations → Outliers  

**Step 5 — Dashboard**  
Interactive Streamlit dashboard with filters and visual insights.


## Results

- Peak activity hour: **13:00 (1 PM)**
- Most common action: View (65%)  
- Anomalous users detected: 7 out of 20 (35%)


## How to Run

```bash
# Install dependencies
pip install pyspark streamlit pandas plotly

# Run Spark processing
python user_activity_spark.py 

# Launch dashboard
streamlit run streamlit_app.py

```

## Requirements

- Python 3.10+
- Java 11 (required for Spark)


## Future Enhancements

- Real-time data processing using Spark Streaming  
- Kafka integration for live data ingestion  
- Machine learning-based anomaly detection  
- Cloud deployment (AWS/Azure)


## 🎓 Course Details
- **Course:** B.Tech Big Data Analytics  
- **Academic Year:** 2025–26  
- **GitHub:** [@likithams09](https://github.com/likithams09)
  
