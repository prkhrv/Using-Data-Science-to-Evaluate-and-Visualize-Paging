# Using-Data-Science-to-Evaluate-and-Visualize-Paging


## 1. First In First Out (FIFO) – 

This is the simplest page replacement algorithm. In this algorithm, the operating system keeps track of all pages in the memory in a queue, the oldest page is in the front of the queue. When a page needs to be replaced page in the front of the queue is selected for removal. 

***Belady’s anomaly – Belady’s anomaly proves that it is possible to have more page faults when increasing the number of page frames while using the First in First Out (FIFO) page replacement algorithm.  For example, if we consider reference string 3, 2, 1, 0, 3, 2, 4, 3, 2, 1, 0, 4 and 3 slots, we get 9 total page faults, but if we increase slots to 4, we get 10 page faults***

## 2. Optimal Page replacement – 
In this algorithm, pages are replaced which would not be used for the longest duration of time in the future.

## 3. Least Recently Used – 
In this algorithm page will be replaced which is least recently used. 
