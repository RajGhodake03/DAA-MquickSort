# DAA-MquickSort

MQuickSort - Enhanced QuickSort with Dynamic Pivot Selection

Overview

MQuickSort is an improved version of the traditional QuickSort algorithm that utilizes a dynamic pivot selection technique to optimize performance. Unlike traditional QuickSort, which may suffer from worst-case  complexity, MQuickSort ensures better balance and reduces recursive calls, often achieving  efficiency.

Features

Dynamic Pivot Selection: Automatically adjusts pivot based on array distribution.
Optimized Performance: Converts worst-case QuickSort scenarios into best-case execution.
Balanced Partitioning: Reduces execution time by minimizing unbalanced splits.

How It Works

1. Selects an Initial Pivot from the rightmost element.


2. Counts & Sums elements less than and greater than the pivot.


3. Calculates New Pivots for the next recursive calls using averages.


4. Checks if Sorted, skipping unnecessary recursive calls.



Installation

Clone this repository:

git clone https://github.com/yourusername/MQuickSort.git  
cd MQuickSort

Usage

Run the Python script to sort an array:

from mquicksort import quicksort  

data = [10, 7, 8, 9, 1, 5]  
quicksort(data, 0, len(data) - 1)  
print(data)

Example Output

[1, 5, 7, 8, 9, 10]

Reference

For more details, check out the original research paper:
Enhancing QuickSort Algorithm using a Dynamic Pivot Selection Technique



