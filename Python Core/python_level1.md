# Chafter: Python Crash Book

---
Chafter 1 : Styling Your Code
---

- PEP - Python Enhance Proposal
- 4 spaces as indetation.
- Line Length < 80 characters
- Comments < 72 charactets
- Blank lines : It impacts readability of your code

---
Chafter 2 : List
---

- Ordered indexing
- Supports Negitive Indexing

### Adding elements
1. To add element end of the list using list.append(element)
2. To insert element at specific index , using list.insert(index, element)
3. To add another iterable elements (LIST, SET etc), probably extend() method helps you to do it.

  Note: Choosing between [apppend] and [extend] depends on what you want to achive.
        if you want to add single element , use append. if you want to add mutiple elements from iterable, use extend.

### Modifying elements
1. Using indexes, you can modify.

### Removing Part of it
1. To remove specific element, use list.remove(element)
2. To remove index element, use list.pop(index)
3. To remove index element based on indexing using del list[index]

## Methods
- sort() : 
    1. list.sort() helps to sort list, possible to pass multiple parameters
    2. list sort(reverese=True) : sort in descending order

- reverse()
    1. list.reverse() used to reverse elements

- len()
    1. Used to find the lenght of the list

- for index in range(1, 5)          >>> 1,2,3,4,5
- for index in range(1, 7, 2)       >>> 1 3 5 7

- min() , max(), sum() - methods to do some operations

- list() method also used to create empty list

### List Comprehensions
    Amazing way of writing code in the single line. it combines for loop into single line.

    - Adding a Condition:
        squared_even_numbers = [num ** 2 for num in numbers if num % 2 == 0]

    - Nesting loop:
        product_list = [num1 * num2 for num1 in list1 for num2 in list2]

    - Conditional Expression:
        powered_numbers = [num ** 2 if num % 2 == 0 else num ** 3 for num in numbers]

###### Slicing a List

###### Looping Through a Slice

###### Copying a List



---
Chafter 3: Tuple
---

Once the tuple is being created, then not able to change anything inside


- Use cases:
    - Tuples are often used when the order of elements matters, and you want to ensure the data remains constant.
    - They are commonly used in situations where data should not be modified accidentally.
    - Tuples can be used as keys in dictionaries (unlike lists) due to their immutability


---
Chafter 4: Conditional Statements
---

### Conditional Statment

    if condition

    elif condition

    else
