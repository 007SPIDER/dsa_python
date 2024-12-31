***
---
1. list is built-in data type in python .
2. how to create array in python?
   -> collection of similar elements
   -> group of variables
   -> elements are indexed contigeous memory allocation
   -> fixed size not growable
   -> fixed size array is not provided as built-in in python
   -> elemantary data structure
   -> if we have to store 100 elements then it is not easy to define 100 variables and manage it
   -> if all values belong to same domain like 100 values defining all persons should not be stored in the array
   -> marks of a class should be stored in array because all belongs to same domain and specifying single properties of different object
   -> collection of data defining the same property of the similar objects should be stored in array
   -> python has builtin modules(int,float,bool,str,dict,list,tuple,exception, object,warnning etc), it can be accessed via help--> builtins
   -> several classes defined in builtins module
   -> array is not built-in data structures and therefore need to be imported
   -> there is array named class but not in the builtins . there is another module named as array which comes as standard library
   -> array is a module defines an object type which can represent array of basic values (int,float,str)
   -> array are sequence type and behaves like list and arrays can have elements of limited type
   -> list can have any type value , while array has limited types which it accepts
   -> user defined data types or class objects are not allowed to store in array
   -> array accepts homogeneous values only
   -> import array
      while initializing we give _typecode and elements which can be list/tuple/set
   --> _typecode is :-> QBHIL(for singed/unsigned integers), udf(unicocde,double,float)
       ‘b’ – signed char
       ‘B’ – unsigned char
       ‘d’ – double
       ‘f’ – float
       ‘i’ – signed int
       ‘I’ – unsigned int
       ‘h’ – signed short
       ‘H’ – unsigned short
       ‘l’ – signed long
       ‘L’ – unsigned long
   --> signed typecode is in lowercase and it accepts all +,-,0.
   --> unsigned means non-negative number and ut gets represented by uppercase typecode
   --> elements of array can be accessed via for and indexing (it supports postive and negative value) ,slicing also allowed
   --> create empty index :-> millions = cr7.array('i') #creates an empty array of integer
   --> array menthods
      0. mutable data type is array , elements can be assinged via arr[0] = 1(data type should be same)
      1. millions = cr7.array('i', [2, 4, 6])
      2. millions.append(8) #includes 8 as the last element to the array
      3. millions.extend([10, 12, 14, 16, 18]) #array(‘i’, [2, 4, 6, 8, 10, 12, 14, 16, 18])
      4. append() – Adds an element at the end of the array list
         reverse() – Reverses the order of an array list
         clear() – Eliminates all elements from the array list
         pop() – Removes an element from the specified position
         count() – Returns the elements along with their total number
         insert() – Adds an element to the specified position in the array list
         copy() – Returns a copy of the array list
         extend() – Add the elements of an array list to the end of the current list
         remove() – Eliminates the first element with the specified value
         index() – Returns the index of the first element in an array list with the specified value
         sort() – Sorts the array list
         count()
         extended()
         fromlist()
         index()
         tolist()
   --> drawback :-> only limited data type is allowed for array module in python so we use numpy array
   ---
   list is builtin class in python
   it is mutable , sequence , iterable , indexed,list can grow till any size , can contain different object types
   ---
   differance between array and dynamic array ?
    ** array is collection of same object type with fixed size & it cannot grow & index is allowed with sequence and contigueous memeory locations
    ** list is collection of hetrogeneous type with growable size , indexing is allowed and it ia based on dynamic array
    ** dynamic array :->collection of same type with not fixed size , it can grow , index is allowed.
    ** in python list is implemented by using dynamic array and since it is dynamic language so list allows hetrogeneous elements in list .\
    ** in python , array and list both are growable
    ** there is only one diff between array and list is type of elements .(array does not allow anything which is user defined types)
    ** len() , sum(), macx(),min() , sorted() (always output new list no changes in the input list) also applicable for array
    ** to perform mathematical calcualtions use numpy array
    ** for numpy array size is fixed
    *****numpy*****
    1. np.array([1,2,3,4])
    2. np.array([[1,2,3],[4,5,6])
    3. if for 2-d array size is different then it will create 1-d array treating each array for each elements   
---
***
