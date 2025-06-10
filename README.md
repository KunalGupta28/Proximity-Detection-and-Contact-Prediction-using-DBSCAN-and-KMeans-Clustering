# Proximity-Detection-and-Contact-Prediction-using-DBSCAN-and-KMeans-Clustering

# GPS-Based Clustering and Contact Tracing using DBSCAN and KMeans

## Project Overview
This project uses DBSCAN and KMeans clustering algorithms to find people who came into close contact based on their GPS data. It simulates a real-world contact tracing system (e.g., COVID-19 scenario).

## Technologies Used
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset
- File: livedata.json
- Contains synthetic GPS data points with person ID, timestamp, latitude, and longitude.

## Features
1. Clustering with DBSCAN (density-based)
2. Clustering with KMeans (centroid-based)
3. Visualization of both clusterings
4. KMeans prediction for new GPS points
5. Silhouette Score evaluation for KMeans
6. Contact tracing function to find possible contacts from DBSCAN clusters

## Example Output
Possible contacts near 'Erin': ['Alice', 'Bob', 'Grace']

KMeans Prediction for New Point: Cluster-2

Note: DBSCAN cannot predict new points after training.

## Limitations
- DBSCAN does not support prediction for new data points.
- Data is synthetic for learning/demo purposes.

## Future Work
- Real-time clustering
- Comparison with other clustering methods (e.g., HDBSCAN)
- Interactive visualizations

## Author
Kunal Gupta
LinkedIn: [Add your link here]
GitHub: [Add your link here]
