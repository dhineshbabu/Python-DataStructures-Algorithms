# Python-DataStructures-Algorithms
Repo For DataStructure and Algorithms Learning in Java

<hr />

### Module 02 - Lists
* Dynamic Size
* Allows Items of Different Types
* Can be accessed via index (starts from 0), last element index -1
* Advantages
  * Random Access
  * Cache friendly
  * Underlying data structure is array
* Disadvantages
  * Insertion and Deletion are slow
  * Search is also slow for unsorted list
* How Does Dynamic Size work?
  * Preallocate some extra space
  * If it becomes full, do the following
    * Allocate a new space fo larger size(multiply by x)
    * Copy old space to new
    * Free old space
* Slicing
  * list slicing return a list
  * slicing will return a new list object 
* List Comprehension
  * 