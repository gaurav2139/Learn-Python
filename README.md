# Learn-Python

Contents of the Learn-Python are taken from different sources online and boiled down to crisp topics. You may refer learnpython.com and tutorialspoint.com for more information.

Data types:

Int, float, strings
String can be written under single quotation or double quotation, it's better to use single quotes for strings as print statement has double indentation.

**Lists:**

Lists are all similar to array but they can contain different data type inside the lists.

Creating a list is as simple as putting different comma-separated values between square brackets. For example −
list1 = ['physics', 'chemistry', 1997, 2000];
list2 = [1, 2, 3, 4, 5 ];
list3 = ["a", "b", "c", "d"]

Lists indexing starts with zero and there can different operations on the lists like concatenation, addition

Because lists are sequences, indexing and slicing work the same way for lists as they do for strings.
Assuming following input −
L = ['spam', 'Spam', 'SPAM!']

**Built-in List Functions & Methods**

Python includes the following list functions −Function with Description 
1. cmp(list1, list2) : Compares elements of both lists.
2. len(list) : Gives the total length of the list.
3. max(list) : Returns item from the list with max value.
4. min(list) : Returns item from the list with min value.
5. list(seq) : Converts a tuple into list.


**Python includes following list methods--Methods with Description** 

1. list.append(obj) : Appends object obj to list
2. list.count(obj) : Returns count of how many times obj occurs in list
3. list.extend(seq) : Appends the contents of seq to list
4. list.index(obj) : Returns the lowest index in list that obj appears
5. list.insert(index, obj) : Inserts object obj into list at offset index
6. list.pop(obj=list[-1]) : Removes and returns last object or obj from list
7. list.remove(obj) : Removes object obj from list
8. list.reverse() : Reverses objects of list in place
9. list.sort([func]) : Sorts objects of list, use compare func if given
