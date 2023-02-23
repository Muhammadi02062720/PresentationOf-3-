>## What is the array in js ?

 >In JavaScript, arrays aren't primitives but are instead Array objects with the following core characteristics:

 * JavaScript arrays are resizable and can contain a mix of different data types. (When those characteristics are undesirable, use typed arrays instead.)
 * JavaScript arrays are not associative arrays and so, array elements cannot be accessed using arbitrary strings as indexes, but must be accessed using nonnegative integers (or their respective string form) as indexes.
 * JavaScript arrays are zero-indexed: the first element of an array is at index 0, the second is at index 1, and so on — and the last element is at the value of the array's length property minus 1.
 * JavaScript array-copy operations create shallow copies. (All standard built-in copy operations  with    any JavaScript objects create shallow copies, rather than deep copies).

![](/images/865.jpg)

>### CHANGE ELEMENTS IN ARRAY 

 >You can also add elements or change the elements by accessing the index 
 value. 
 ![](/images/Screenshot_1.png)

>Suppose, an array has two elements. If you try to add an element at index 3 
(fourth element), the third element will be undefined. For example,
 
 ![](/images/Screenshot_2.png)



># Array methods
 
![](/images/Screenshot_3.png)


>### Add an Element to an Array

 >If we want to add new elements in array, we have to use belows methods:

  > + push();
  > + unfhift();


>##### if we want to add new element to an array we use the method (push()):

 >The method push() add element on the end of the array'
  > For example:

  ![](/images/Screenshot_4.png)