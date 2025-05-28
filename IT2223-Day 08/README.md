
# MATLAB Sorting Algorithms

This repository contains two simple MATLAB scripts demonstrating sorting algorithms:
1. **Bubble Sort**
2. **Insertion Sort**

---

## 🧪 Program 1: Bubble Sort with Execution Time

**Description:**  
Sorts an array using the Bubble Sort algorithm and measures the time it takes to sort.

**Code:**

```matlab
fprintf("Original array: ");
disp(arr);
arr = [64, 34, 25, 12, 22, 1, 90];

tic;
function sorted = bubbleSort(arr)
    len = length(arr);
    for i = 1 : len - 1
        for j = 1 : len - i
            if arr(j) > arr(j+1)
                temp = arr(j);
                arr(j) = arr(j + 1);
                arr(j + 1) = temp;
            end
        end
    end
    sorted = arr;
end
elapsedTime = toc;
sortedArray = bubbleSort(arr);
fprintf("\nSorted Array: ");
disp(sortedArray);
fprintf("\nTime: %f\n", elapsedTime);
```
![BubbleSort](https://github.com/user-attachments/assets/6e318a3c-727a-43e1-abcf-1132c122d518)

---

## 🧪 Program 2: Insertion Sort

**Description:**  
Sorts an array using the Insertion Sort algorithm and prints the result.

**Code:**

```matlab
fprintf("Original Array: ");
disp(arr);
arr = [74, 2, 36, 89, 5, 12];

function sorted = insertionSort(arr)
    for i = 2:length(arr)
        key = arr(i);
        j = i - 1;

        while j >= 1 && arr(j) > key
            arr(j + 1) = arr(j);
            j = j - 1;
        end
        arr(j + 1) = key;
    end
    sorted = arr;
end

sortedArr = insertionSort(arr);
fprintf("Sorted Array: ");
disp(sortedArr);
```
![InsertionSort](https://github.com/user-attachments/assets/198f7d5f-b910-4ab8-80e4-0a9dc9ff6910)

---

## 📌 Notes
- Be sure to save each script in a separate `.m` file when testing in MATLAB or Octave.
- For Bubble Sort, MATLAB may warn if `tic` and `toc` are used inside function blocks; it's placed correctly around the function call here.
