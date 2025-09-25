# Mall Customer Segmentation

## Description
This project performs customer segmentation for a mall dataset using unsupervised machine learning techniques. The goal is to group customers based on their age, annual income, and spending behavior to better understand customer patterns and improve marketing strategies.

## Algorithm
The main algorithm used in this project is **KMeans Clustering**.  
KMeans divides the dataset into a specified number of clusters by minimizing the distance between data points and the cluster centers. The Elbow method and Silhouette Score are used to determine the optimal number of clusters and evaluate the quality of clustering.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/amirmohammadgholampour/Mall-customer-segmentation.git
```

2. Navigate to the project directory:
```

cd MallCustomerSegmentation
```

3. Create a virtual environment (optional but recommended):
```
python3 -m venv venv 
source venv/bin/activate # Linux/Mac
venv\Scripts\activate # Windows 
``` 

4. Install required packages:
```
pip install -r requirements.txt
```

Enjoy the coffee :D