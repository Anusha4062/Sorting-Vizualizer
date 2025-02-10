# Sorting-Vizualizer

## **Description**  
This Python program sorts a list of product prices using the **Bubble Sort algorithm** while providing a **real-time bar chart visualization** of the sorting process. The program categorizes products as "Product 1", "Product 2", etc., based on their order of input and sorts them from lowest to highest price.  

## **Features**  
✅ Takes user input of product prices.  
✅ Assigns product names dynamically.  
✅ Uses **Bubble Sort** to sort prices.  
✅ **Visualizes** the sorting process with animated bar charts.  
✅ Displays the sorted product list at the end.  

## **Dependencies**  
Ensure you have the following Python libraries installed:  
- **matplotlib** (for visualization)  
- **IPython** (for dynamic display updates)  

Install them using:  
```bash
pip install matplotlib ipython
```

## **How It Works**  
1. The user **inputs** a list of product prices separated by spaces.  
2. The program generates product names dynamically (e.g., "Product 1", "Product 2").  
3. The **Bubble Sort algorithm** sorts the prices step by step.  
4. Each step of sorting is **visualized** with a horizontal bar chart.  
5. Finally, the sorted product list is displayed in ascending order.  

## **Usage**  
Run the script and enter prices as space-separated values:  
```bash
python bubble_sort_visualizer.py
```
Example input:  
```
Enter a list of product prices separated by spaces: 45.99 19.99 25.50 10.75
```
Example output:  
```
Products sorted from low to high price:
Product 4: $10.75
Product 2: $19.99
Product 3: $25.50
Product 1: $45.99
```

## **Visualization Example**  
During sorting, the program will generate a **bar chart** like this:  

📊 **Before sorting:**  
```
Product 1 |███████████      | $45.99
Product 2 |█████            | $19.99
Product 3 |████████         | $25.50
Product 4 |███              | $10.75
```
📊 **After sorting:**  
```
Product 4 |███              | $10.75
Product 2 |█████            | $19.99
Product 3 |████████         | $25.50
Product 1 |███████████      | $45.99
```

## **License**  
This project is open-source and free to use for educational purposes.  
