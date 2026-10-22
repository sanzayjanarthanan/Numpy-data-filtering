# NumPy Data Filtering

Use NumPy conditions to find values that are above, below, or equal to a threshold. Built as part of the AI & ML Internship at Veda Technology.

## Problem
Identify values in a numerical array that are above, below, or equal to a specified threshold.

## Objective
Practice Boolean indexing and numerical filtering using NumPy.

## Approach
1. Created a NumPy array of numerical values.
2. Applied conditions like `data > 50` to generate a Boolean array.
3. Used Boolean indexing (`data[data > 50]`) to return only the matching values.
4. Tried different operators: `>`, `<`, `==`, `>=`.
5. Tested multiple thresholds (30, 50, 70) using a loop.
6. Combined conditions using `&` to filter values in a range.
7. Counted matching values using `np.sum()`.

## Sample Output
```
Original data : [45 78 23 90 56 12 67 50 89 34]
Boolean array (data > 50): [False  True False  True  True False  True False  True False]

Above 50      : [78 90 56 67 89]
Below 50      : [45 23 12 34]
Equal to 50   : [50]
50 or more    : [78 90 56 67 50 89]

Greater than 30: [45 78 90 56 67 50 89 34]
Greater than 50: [78 90 56 67 89]
Greater than 70: [78 90 89]

Between 40 and 80: [45 78 56 67 50]
Count above 50: 5
```

## Files
- `NumPy_Data_Filtering.ipynb`: notebook with the complete solution
- `README.md`: project explanation

## How to Run
1. Open the notebook in Jupyter Notebook or Google Colab.
2. Run all cells from top to bottom.

## Tools Used
Python, NumPy, Jupyter Notebook

## Key Learnings
- A condition on a NumPy array returns a Boolean array
- Boolean indexing selects only the values where the condition is `True`
- Multiple conditions are combined with `&` (and) and `|` (or), each inside brackets

## Author
J Sanjay, AI & Data Science student
