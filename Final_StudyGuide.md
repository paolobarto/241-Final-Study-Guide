# Final Study Guide
---
List of things to study from recording:
1. Outer join (Symmertric difference through symmetric difference)
2. SQL Set opertaions
   1. Aggrigate handling null
   2. Nested Querry
   3. testing trusted querry
3. ERD Design Cardinality
4. JDBC
   1. Update table through jdbc with pre-written code. 
5. Writing Triggers to include some integrity constraint (PL/SQL)
6. OLAP
   1. Most likely test cube
7. Normalization decomposition algorithm
   1. BCNF
   2. 3NF 
   3. (He says Memorization is not important but practice is the most important)
8. Functional dependencies
   1. Find primary key/canidate keys
   2. 3 armstrong axioms
9. Depenedency preservation / Losslessness 
10. Storage
    1.  Formulas
        1.  Cost of accessing data
        2.  Seeking time
        3.  rotational time
        4.  buffer within memory
    2. RAID 
 11. Index types
     1.  B+ tree index
         1.  How to operate on B+ tree
     2.  Hash index
     3.  Sparse / dense index
     4.  Primary / secondary index
     5.  Advantages or disadvantages 
 12. Querry processing 
     1.  Is the right algorithm used for the right situation 
     2.  Be able to connect formuals to real life connection
11. Recovery algorithm 
12. Async properties of transactions
13. Stable storage / checkpoints 
14. Concurrency 
    1.  Two-phase locking
    2.  Granularity
    3.  Deadlock
15. Phantoms 
16. Distributed and parallel querry processing

---
## 1 Outer join 

Outer join can be used for symmetric difference between the opposing side. Natually biasing the side in the description of 

* Left outer join
* Right outer join
* Full outer join

`natural left outer join` is the correct syntax of outer natual join

With this syntax, the side of the comparison that is used in the name will exist as the full table, and each of the other comparisons will have null when not populated.

---
## 2  