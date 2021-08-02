## JavaScript Array map() :
***The Definition of The map()***

* method creates a new array with the results of calling a function for every array element.

* method calls the provided function once for each element in an array, in order.

### What does .map() return?
map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.) ... fun : It is a function to which map passes each element of given iterable.

![ map() ]( https://miro.medium.com/max/1400/1*UtOOGoaqm-L51gY15aJKzg.png)

### If I want to loop through an array and display each value in JSX, how do I do that in React?
Use the .map() method to render data.
Parse and display data in an array of objects

Each list item needs a unique ____.
“key” 
A “key” is a special string attribute you need to include when creating lists of elements. 

### What is the purpose of a key?
 Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words, we can say that keys are used to give an identity to the elements in the lists.

***Example : ***

![map](https://www.itboy.in/wp-content/uploads/2021/01/map.png)


  ## The Spread Operator
### What is the spread operator?
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

### List 4 things that the spread operator can do?

1. Copying an array
2. Concatenating or combining arrays
3. Using Math functions
4. Using an array as arguments






# Passing Functions Between Components


### In the video, what is the first step that the developer does to pass functions between components?

creat the function wherever the state is we're going to change 

### In your own words, what does the increment function do?

change the value of state 

### How can you pass a method from a parent component into a child component?
by pass it as a props
### How does the child component invoke a method that was passed to it from a parent component? 
call the methot that was pass as props.
will invoke the state method and pass the data.

***Example : ***
 
![props](https://tech4grasp.com/wp-content/uploads/2019/08/parent-componet-calling.png)

-------------


***Things I want to know more about***

I want to learn more about map method


---------------------

referenses 


[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)


