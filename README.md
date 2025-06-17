# FAD Algorithm Implementation

This code implements the **FAD algorithm** proposed in the paper:  
**"Anchored Maximum Communities over Large Directed Graphs"**.

## 1. Compilation
Compile the source code using the following command (requires `g++`):
```bash
g++ -O3 fad.cpp -o fad
```

## 2. Execution
Run the compiled executable with the dataset file as a parameter:
```bash
./fad [dataset.txt]
```
Replace `[dataset.txt]` with your input graph file (e.g., `web-Google.txt`).

## 3. Input Format
The dataset file should be a **directed graph** in plain text format, where each line represents an edge:
```
source_node_id target_node_id
```
Example:
```
0 1
1 2
2 0
```

## 4. Output
The program will output the detected anchored maximum communities.  

## 5. Dependencies
- C++11 or later

---
