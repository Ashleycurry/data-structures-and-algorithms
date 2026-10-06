# Data Structures and Algorithms Notes

[中文说明](README.md)

This repository organizes course materials about data structures and algorithms. The content is based primarily on the PDF materials in `docs/` and covers data structure fundamentals, linear structures, algorithm complexity, searching algorithms, and sorting algorithms.

- [Data Structures and Algorithms PDF](docs/数据结构与算法.pdf)
- [Data Structures and Algorithms DOCX Source](docs/数据结构与算法.docx)

> This README provides a learning index. Refer to the PDF for complete definitions, diagrams, and examples.

## Learning Roadmap

```text
Data structure fundamentals
    ├── Logical and storage structures
    ├── Data operations and memory
    └── Relationship between data structures and algorithms
            ↓
Linear structures
    ├── Arrays
    ├── Linked lists
    ├── Stacks
    └── Queues
            ↓
Algorithm fundamentals
    ├── Time complexity
    └── Space complexity
            ↓
Algorithm applications
    ├── Searching: sequential search and binary search
    └── Sorting: bubble sort, quick sort, and other common algorithms
```

## Contents

### Chapter 1: Data Structures

 - Data structure fundamentals: logical structures, storage structures, data operations, memory, and the relationship between data structures and algorithms.
 - Arrays: contiguous storage, random access, dynamic resizing, insertion, deletion, and traversal.
 - Linked lists: nodes, data fields, pointer fields, singly linked-list organization, insertion, deletion, and release.
 - Stacks: the last-in, first-out (LIFO) principle, push, pop, peek, and array-based or linked storage.
 - Queues: the first-in, first-out (FIFO) principle, enqueue, dequeue, and sequential, circular, or linked storage.

### Chapter 2: Algorithms

 - Algorithm fundamentals: definitions, inputs, outputs, termination, time complexity, and space complexity.
 - Searching algorithms: sequential search, binary search, preconditions, and complexity.
 - Sorting algorithms: common ideas, bubble sort, quick sort, complexity, stability, and use cases.

## Complexity Reference

| Structure or algorithm | Typical operation | Time complexity | Notes |
| --- | --- | --- | --- |
| Array | Index access | `O(1)` | Contiguous storage supports random access |
| Array | Middle insertion or deletion | `O(n)` | Later elements usually need to be shifted |
| Linked list | Lookup by position | `O(n)` | Nodes must be traversed from the head |
| Linked list | Insert or delete after locating the node | `O(1)` | Excludes the cost of locating the node |
| Stack | Push, pop, peek | `O(1)` | Operations are performed at the top |
| Queue | Enqueue, dequeue | `O(1)` | Depends on the implementation |
| Sequential search | Find an element | `O(n)` | Works with unsorted data |
| Binary search | Find an element | `O(log n)` | Requires ordered data and positional access |
| Bubble sort | Sort data | `O(n²)` | Useful for understanding sorting mechanics |
| Quick sort | Sort data | Average `O(n log n)` | The worst case is usually `O(n²)` |

## Suggested Study Process

1. Read the data structure fundamentals first to build an overall model of logical structures, storage structures, and memory.
2. Draw storage diagrams for arrays, linked lists, stacks, and queues before studying their operations.
3. Record preconditions, data changes, boundary cases, and complexity for each operation.
4. Trace searching and sorting algorithms manually with small data sets.
5. After reading the materials, add independent implementations and tests for key operations.

## Directory Structure

```text
data-structures-and-algorithms/
├── README.md
├── README-English.md
└── docs/
    ├── 数据结构与算法.pdf
    └── 数据结构与算法.docx
```

## Possible Extensions

The current repository focuses on course materials and a study index. Future practice can add implementations of arrays, linked lists, stacks, queues, searching algorithms, and sorting algorithms, together with boundary tests and complexity experiments.

## Keywords

`Data Structures` `Algorithms` `Array` `Linked List` `Stack` `Queue` `Searching` `Sorting` `Time Complexity` `Space Complexity`
