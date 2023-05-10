# FIAP - 2° Checkpoint - Conding for Security - DataShield

## **Introduction**

**Checkpoint carried out with the aim of putting into practice all the knowledge of manipulation of lists structures and repetition acquired in the subject of Conding for Security, taught by Professor Fábio Cabrini.**

## **Participants**

- Eduardo dos Santos
- Jorge Gabriel
- Matheus Rosa
- Pedro Augusto

## Challenge

The challenge is to create a program capable of reading a password file and generating a list of 1000 pieces of data. From this list, we will organize them in ascending order using market algorithms, such as **Selection Sort, Bubble Sort and Quick Sort.** Our ultimate goal is to evaluate the efficiency of each algorithm and identify which one has the highest response speed.

## **What are sorting algorithms?**

**Sorting algorithm, in computer science, is an algorithm that places the elements of a given sequence in a certain order. In other words, it performs its complete or partial sorting. The purpose of sorting is to make it easier to retrieve data from a list.**

### Bubble Sort

**Bubble Sort is a simple sorting algorithm that works by traversing an array multiple times. At each iteration, it compares the current element with the next element, and, if it is in an incorrect order, swaps its position with the next element.
The process continues until there are no more swaps to perform, which indicates that the list is sorted.
In our results, this algorithm proved to be the least efficient due to the amount of iteration of the elements.**

### Selection Sort

Selection Sort is a simple sorting algorithm that runs through an array of data multiple times, each pass selecting the smallest element and placing it in the correct position. It works by selecting the smallest element in a list and swapping it with the first element in the list. It then selects the second smallest element and swaps it with the second element in the list, and so on, until the list is completely sorted.

### Quick Sort

Quick Sort is a sorting algorithm that uses the concept of divide and conquer to sort a set of elements. The algorithm is known to be fast and efficient compared to other sorting algorithms, especially for large datasets.

Quick Sort works by dividing the data set into two smaller parts, according to an element chosen as a pivot. All elements smaller than the pivot are placed to the left of the pivot, and elements larger are placed to the right of the pivot. Then the algorithm is applied recursively to each of the smaller parts, until the set is completely sorted.

The choice of pivot is a critical factor for the efficiency of the algorithm. The ideal pivot is the middle element of the set, but in practice it is difficult to find it. A common strategy is to choose the first or last element of the set as the pivot, or to choose a random element.
Based on the evidence (found below) this algorithm is the most efficient

## **Step by step to run the program**

### **Step 1 - Open the terminal**

### **Step 2 - Get the project from github**

To get the files type the command:

```
git clone https://github.com/MatheusRosa800/CP2---Coding-for-Security---PT-BR.git
cd CP2---Coding-for-Security---PT-BR

```

### **Step 3 - Run the command below to open the Python program**
```
python3 escolha.py

```

### **Step 4 - Write the quantity of numbers you want to see**
[https://camo.githubusercontent.com/9727b52e65d75667eaa0308856c15469ac6c4dd31f45fd38b552def4304ff803/68747470733a2f2f692e6962622e636f2f4a437335394a332f636f642e706e67](https://camo.githubusercontent.com/9727b52e65d75667eaa0308856c15469ac6c4dd31f45fd38b552def4304ff803/68747470733a2f2f692e6962622e636f2f4a437335394a332f636f642e706e67)

## Youtube
[Link para o Youtube](https://www.youtube.com/watch?v=wFsU3rTPcH8&ab_channel=PedroAugusto)

## **Algorithm performance evaluation dashboard**
All proposed algorithms were submitted to ten exhaustive tests, with the results being recorded for later analysis of the list delivery level.

### **Environment**

Operating System: Windows 10
Processor: Intel Pentium G4560 3.5Ghz
RAM: 16GB
SSD: 128GB

### **Results**
Based on the results, the performance of the Quick Sort algorithm, which is ahead of the other two, is notorious.

The evidence follows:

Evidence 01

![Imagem do programa](https://github.com/MatheusRosa800/CP2---CodingForSecurity---PT-BR/blob/main/evidencia-1.png)

Evidence 02

![Imagem do programa](https://github.com/MatheusRosa800/CP2---CodingForSecurity---PT-BR/blob/main/evidencia-2.png)
