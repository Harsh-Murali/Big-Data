**Anomaly Detection in Sensor Data using Hadoop for Scalable Pattern Analysis**

- **Extracted and transformed** sensor data from multiple stations for uniform structure and loaded it into Hadoop for large-scale anomaly detection.
- Detected **100+ humidity anomalies** across sensor data from multiple stations, leveraging **MRJob** and Hadoop for real-time pattern detection.
- Calculated daily and overall humidity averages for each sensor, **flagging gaps exceeding threshold (τ)** to identify unusual readings.
- Achieved sorted results with 3 key optimisation techniques (**combiner, order inversion, secondary sorting**) for faster, accurate processing.

**E-Commerce Frequent Item Set Mining with Spark**

- **Extracted, cleaned, and transformed** e-commerce log for efficient mining in Spark.
- Mined top-k frequent 3-item sets from e-commerce logs using **Spark RDD and DataFrame APIs** for large-scale analysis.
- Calculated support, identifying frequently bought item sets for insights into customer behaviour. Optimised Spark code for efficient **top-k computation**

**Cross-Year Similarity Match in E-Commerce Transactions with Spark**

- Identified **200+ cross-year** similar transaction pairs with **Jaccard similarity**, using a threshold (τ) to highlight key purchasing patterns after extracting and transforming data.
- Processed logs in Spark, calculating similarity scores and filtering for **τ ≥ 0.5** to ensure meaningful results.
- Sorted output by InvoiceNo and similarity for clear reporting.
- Achieved scalability and accuracy with Spark’s **memory-efficient join techniques**.
