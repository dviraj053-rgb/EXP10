# EXP10
Here is the **rephrased version** of your experiment arranged in proper format (Aim, Theory, Algorithms, Conclusion) similar to the previous ones:

---

# **Aim: Study of Pandas Library in Python**

---

## **Theory**

Pandas is a powerful, open-source Python library used for data analysis and data manipulation. It provides flexible and efficient data structures designed to handle structured data easily.

The two primary data structures in Pandas are:

### **1. Series**

`pd.Series()` creates a one-dimensional labeled array that can store any data type such as integers, floats, strings, or objects. Each element in a Series has an associated index.

### **2. DataFrame**

`pd.DataFrame()` creates a two-dimensional, tabular data structure with labeled rows and columns. It is size-mutable, meaning rows and columns can be added or removed.

---

## **Important DataFrame Attributes**

* **df.shape** – Returns a tuple representing the number of rows and columns.
* **df.ndim** – Returns the number of dimensions (usually 2 for DataFrame).
* **df.columns** – Displays the column names.
* **df.dtypes** – Shows the data type of each column.

---

## **Data Selection and Indexing**

* **df.loc[row_index, "ColumnName"]** – Accesses data using row and column labels.
* **df.iloc[row_index, col_index]** – Accesses data using integer-based indexing.

---

## **Data Manipulation Functions**

* **df.drop()** – Removes specified rows or columns.

  * `axis=1` is used to remove a column.
* **df.mean()** – Calculates the average value of a column.
* **df.max()** – Returns the maximum value in a column.
* **df.min()** – Returns the minimum value in a column.

---

## **Filtering Data**

Conditional filtering is performed using:

```
df[df["Marks"] > 80]
```

This statement displays only those rows where the value in the "Marks" column is greater than 80.

Pandas simplifies data cleaning, transformation, filtering, and statistical analysis compared to traditional Python methods.

---

# **Conclusion**

Thus, the Pandas library was successfully studied and implemented in Python. Various operations such as data creation, selection, filtering, deletion, and statistical analysis were performed using Pandas functions. The library makes data handling simple, efficient, and structured for analytical tasks.
