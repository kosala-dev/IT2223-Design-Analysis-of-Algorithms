# Search Algorithms in MATLAB

This repository contains MATLAB implementations of two fundamental search algorithms:

- **Linear Search**
- **Binary Search**

These algorithms are useful for understanding basic searching techniques used in computer science and are implemented in a way that's easy to understand and run in MATLAB.

---

## 📁 Files Included

- `linearSearch.m` - MATLAB function for Linear Search
- `BinarySearch.m` - MATLAB function for Binary Search

---

## 🔍 Linear Search

**Linear Search** checks each element in the array one by one until it finds the target value or reaches the end of the array.

### Example

```matlab
arr = [5, 2, 9, 1, 7];
target = 9;
idx = linear_search(arr, target);  % Output: 3
```

---

## ⚡ Binary Search

**Binary Search** works on sorted arrays and repeatedly divides the search interval in half to find the target value.

### Example

```matlab
arr = [1, 2, 3, 4, 5, 6, 7];
target = 5;
idx = binary_search(arr, target);  % Output: 5
```

> ⚠️ Make sure the input array is sorted before using `binary_search`.

---

## ✅ Requirements

- MATLAB R2016b or later (any version supporting basic array operations)

---