# Food Delivery Big Data Analytics

## Project Overview

This project analyzes food delivery data using Apache Spark to identify patterns in delivery performance, customer behavior, order values, and popular food items.

The analysis helps understand how delivery methods, traffic conditions, weather conditions, locations, and food preferences influence food delivery operations.

## Objectives

* Analyze delivery delays by delivery method.
* Study the impact of traffic conditions on delivery time.
* Analyze delivery delays under different weather conditions.
* Compare average order values across delivery methods.
* Compare customer ratings across delivery methods.
* Identify the most popular delivery locations.
* Find food items with the highest average order value.
* Visualize important findings using bar charts.

## Technologies Used

* **Python**
* **Apache Spark (PySpark)**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook**
* **VS Code**

## Project Structure

```text
food-delivery-big-data-analytics/
│
├── data/
│   └── food_delivery_dataset.csv
│
├── notebooks/
│   └── food_delivery_analysis.ipynb
│
├── src/
│
└── README.md
```

## Analysis Performed

### 1. Average Delivery Delay by Delivery Method

Compared the average delivery delay for different delivery methods, including Car, Bike, and Walk.

### 2. Average Delivery Delay by Traffic Condition

Analyzed delivery delays under Low, Medium, and High traffic conditions.

### 3. Average Delivery Delay by Weather Condition

Compared delivery delays during Sunny, Snowy, and Rainy weather.

### 4. Average Order Value by Delivery Method

Calculated the average order value for each delivery method.

### 5. Average Customer Rating by Delivery Method

Compared customer ratings across different delivery methods.

### 6. Most Popular Locations

Identified the locations with the highest number of food delivery orders.

### 7. Average Order Value by Food Item

Calculated the average order value and total orders for different food items.

### 8. Data Visualization

Created bar charts to visualize:

* Top 10 most popular food items
* Total orders by delivery method
* Average delivery delay by traffic condition
* Average delivery delay by weather condition

## Key Findings

Based on the analysis:

* **Car** had the highest average delivery delay among the delivery methods analyzed.
* **Low traffic** showed the highest average delivery delay in this dataset, followed by High and Medium traffic.
* **Sunny weather** had the highest average delivery delay among the weather conditions analyzed.
* **Car** had the highest average order value among the delivery methods.
* **Car** also had the highest average customer rating among the delivery methods.
* **Ahmedabad** had the highest number of orders among the locations displayed.
* **Pasta** was the most popular food item by total orders in the visualization.
* **Fried chicken** had the highest average order value among the food items displayed.

> **Note:** These findings are based on the provided dataset and do not necessarily represent real-world food delivery trends.

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Usha-Thota/food-delivery-big-data-analytics.git
```

2. Open the project folder in VS Code.

3. Install the required Python libraries:

```bash
pip install pyspark pandas matplotlib jupyter
```

4. Open the notebook:

```text
notebooks/food_delivery_analysis.ipynb
```

5. Run the notebook cells to reproduce the analysis and visualizations.

## Conclusion

This project demonstrates how PySpark can be used to process and analyze food delivery data efficiently. The results provide insights into delivery performance, customer preferences, order values, and popular locations.

## Author

**Usha Sree Thota**
