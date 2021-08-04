## React Docs - Forms
### 1. What is a ‘Controlled Component’?
![](https://daveceddia.com/images/react-forms.png)


A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange . A parent component “controls” it by handling the callback and managing its own state and passing the new values as props to the controlled component

### 2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
In HTML, form elements such as , 

### 3. How do we target what the user is entering if we have an event handler on an input field?
When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.




## The Conditional (Ternary) Operator Explained
 

 ![](https://scotch-res.cloudinary.com/image/upload/w_auto,q_auto:good,f_auto/v1562952581/jqctyinrganjts991d3w.jpg)

 
***condition ? value if true : value if false***

The condition is what you’re actually testing. The result of your condition should be true or false .

A ***?*** separates our conditional from our true value. Anything between the ? and the ***:*** is what is executed if the condition evaluates to true.
Finally a ***: colon***. If your condition evaluates to false, any code after the colon is executed.


###  Rewrite the following statement using a ternary statemen:

***x === y ? console.log(yes) : console.log(false)***