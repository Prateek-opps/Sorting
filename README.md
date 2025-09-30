Experiment : 21

Name : Prateek Sinha

Class : ENTC(A3)

Prn : 240123077


# Sorting Algorithms in C++

This project contains simple C++ programs to demonstrate **Selection Sort** and **Merge Sort**.

---

##  Theory

**Sorting** is the process of arranging data in a particular order, usually ascending or descending. Sorting is fundamental in computer science as it improves efficiency in searching and data processing.

1. **Selection Sort**  
   - Simple comparison-based sorting algorithm.  
   - Works by repeatedly finding the minimum element from the unsorted part and moving it to the beginning.  
   - Time Complexity: **O(n²)**  
   - Space Complexity: **O(1)** (in-place)  

2. **Merge Sort**  
   - Divide-and-conquer algorithm.  
   - Recursively divides the array into halves, sorts each half, and merges them back together.  
   - Time Complexity: **O(n log n)**  
   - Space Complexity: **O(n)**  

---

##  Algorithms

### 1. Selection Sort
1. Start.  
2. Input size of the array `n`.  
3. Input `n` elements into the array.  
4. Repeat for each position `i` from 0 to n-2:  
   - Find the minimum element in the unsorted portion (from `i` to `n-1`).  
   - Swap the minimum element with `arr[i]`.  
5. End after array is sorted.  
6. Display sorted array.  

### 2. Merge Sort
1. Start.  
2. Input size of the array `n`.  
3. Input `n` elements into the array.  
4. Recursively divide the array into two halves until size = 1.  
5. Merge the two halves in sorted order.  
6. Continue merging until the entire array is sorted.  
7. Display sorted array.  
8. End.  

---

##  How to Run
1. Copy any of the programs into a C++ compiler (e.g., g++).  
2. Compile the program:  
   ```bash
   g++ program.cpp -o program
