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

 >The method unshift() add element to the start of the array
>For example:

 ![](/images/Screenshot_5.png)


>### Delete an Element in Array

 >If we want to delete some elements of array we use belows methods:

  > + pop();
  > + shift();

>##### The method pop() delete an element from the end of the array:

 >For example:

  ![](/images/Screenshot_6.png)


 >##### The method shift() delete an element from the start of the array:

 >For example:

  ![](/images/Screenshot_7.png)


>## JavaScript array methods:

 >If you want to reverse an elements on array,you have to use the method reverse();

  >How reverse() method does work ?

   >Reverse() method, reverse an elements of array from the end into start:
   >For instead:

  ![](/images/Screenshot_8.png)


>#### Concat();

 >We use concat() method to join some arrays:
 >For example:

 ![](/images/Screenshot_9.png)


>#### indexOf();

 >We use indexOf() method to know elements in which index lies:
 >For example:

 ![](/images/Screenshot_10.png)


>#### includes():

 >we use the includes() method to find out if there is such an element in our array:
 >For example:

 ![](/images/Screenshot_11.png)


>#### splice():

 >The splice() method changes the contents of an array by removing or replacing existing elements and/or adding new elements in place. To access part of an array without modifying it, see slice().
 >slice() method takes three parametrs:
 >For example:    slice(start, delete, add);

  ![](/images/Screenshot_13.png)


>#### slice():

 >The slice() method returns a shallow copy of a portion of an array into a new array object selected from start to end (end not included) where start and end represent the index of items in that array. The original array will not be modified:
 >slice() mehtod takes two parametrs:
 >For example:  slice(start, end);

  ![](/images/Screenshot_12.png)


>## JavaScript array methods callbacks
 
>What is the callbacks in js ?
   
  >Callback is a function that is passed as an argument to another function and its execution is delayed until that function in which it is passed is executed.

  >Обратный вызов - это функция, которая передается в качестве аргумента другой функции, и ее выполнение откладывается до тех пор, пока не будет выполнена та функция, в которую она передана.


>## JavaScript array methods:

![](/images/Screenshot_16.png)

>#### map();
 
 >The map() method creates a new array with the results of calling a provided function on every element in the calling array.


![](/images/Screenshot_17.png)


>#### forEach();

 >The forEach() method executes a provided function once for each array element.

 ![](/images/Screenshot_18.png)
 
 >The syntaxes of forEach()
    > arr.forEach(callback(elements, index, arr) {code})