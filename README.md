# Network Routing using Binary Search Tree

## Scenario 
A network engineer Chinmay manages routers in a large communication network.Each router has a unique Router ID
To avoid scanning all routers, he uses a Binary Search Tree (BST)

## Features
- Fast insertion
- Sorted routing table display
- Input validation

## Concepts Used
- Binary Search Tree
- Recursion
- Inorder Traversal
## Algorithm
step 1: start    
step 2: Insert Router (BST Insert)   
step 3: If root is NULL → create node   
step 4: If value < root → go left  
step 5: If value > root → go right  
step 6: Repeat recursively  
step 7: Display Routing Table (Inorder Traversal)  
step 8: LEFT → ROOT → RIGHT  
step 9: Stop  
## Time complexity
| Operation | Complexity                |
| --------- | ------------------------- |
| Insert    | O(log n) avg / O(n) worst |
| Traversal | O(n)                      |
| Search    | O(log n) avg              |
### Vaild Output:
<img width="1456" height="753" alt="Screenshot 2026-04-21 121505" src="https://github.com/user-attachments/assets/d49b9260-6376-4d98-ada5-b918dca53484" />

### Invaild Output:
<img width="1484" height="774" alt="Screenshot 2026-04-21 121632" src="https://github.com/user-attachments/assets/3ccd703c-6b30-4aca-bb77-839937c1e62c" />
