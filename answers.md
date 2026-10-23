# CMPS 2200 Recitation 06
## Answers

**Name:**Srikanya Balaji Garuda
**Name:**_________________________


Place all written answers from `recitation-06.md` here for easier grading.



- **1)** Before we implement a heap, let's consider if we just maintain
 an unordered list/sequence. 

  - **1a) (1 pt)** What is the work/span of *deleteMin*?
  Work = O(n)
  Span O(log n), finding minimum using parallelization

  - **1b) (1 pt)** What is the work/span ofand *insert(x)*?
  Work = O(1)
  Span = O(1)

- **2a) (1 pt)** For a heap with $n$ elements, what does this imply about the depth of the associated almost-complete binary tree? 
Depth is $\log n$

- **2b) (1 pt)** By maintaining the heap property, where is the minimum element of
  the heap? Can we say anything about the maximum element?
  The minimum element of the heap is the root, and the maxium is one of the leaf nodes

- **4a) (1 pt)** What is the work/span of *reheapUp*($x$)?
Work: O(log n)
Span: O(log n)

- **4b) (1 pt)** What is the work/span of *reheapDown*($x$)? 
Work: O(log n)
Span: O(log n)

- **6) (1 pt)** What is the work and span of `heapsort`?
Work: O(nlog n)
Span: O(nlog n)