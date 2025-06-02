# Sorting Algorithms in MATLAB

This repository contains MATLAB implementations of five classic sorting algorithms:

- **Bubble Sort**
- **Insertion Sort**
- **Merge Sort**
- **Quick Sort**
- **Selection Sort**

---

## 📁 Files Included

- `BubbleSort.m` - Bubble Sort
- `InsertionSort.m` - Insertion Sort
- `Merge_Sort.m` - Merge Sort
- `Quick_Sort.m` - Quick Sort
- `SelectionSort.m` - Selection Sort

---

## 📊 Sorting Algorithm Descriptions

### 🔵 Bubble Sort

Compares adjacent elements and swaps them if they are in the wrong order. Repeats this process until the list is sorted.

```matlab
sorted_array = bubble_sort(array);
```

---

### 🟠 Insertion Sort

Builds the sorted list one item at a time by inserting elements into their correct position.

```matlab
sorted_array = insertion_sort(array);
```

---

### 🟢 Merge Sort

A divide-and-conquer algorithm that recursively divides the array and merges the sorted halves.

```matlab
sorted_array = merge_sort(array);
```

---

### 🔴 Quick Sort

Another divide-and-conquer algorithm that picks a pivot and partitions the array around it.

```matlab
sorted_array = quick_sort(array);
```

---

### 🟣 Selection Sort

Repeatedly selects the smallest (or largest) element and places it at the beginning of the array.

```matlab
sorted_array = selection_sort(array);
```

---

## ✅ Requirements

- MATLAB R2016b or later (any version supporting basic array operations)

---