## component lifecycle events


 
**The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states. **

![component lifecycle events ](https://hackernoon.com/hn-images/1*sn-ftowp0_VVRbeUAFECMA.png)
 

**Mounting**

 When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting

**Updating**

Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.


**Unmounting**

The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.




***What is a Linked List? ***

A linked list is a linear data structure where each element is a separate object usually called a node.

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**


the render will happen first

**2-What is the very first thing to happen in the lifecycle of React?**
 mounting

**3- put the following things in the order that they happen ?**

 1.  constructor()

 2. render()

 3. componentDidMount()

 4. React Updates()

 5. componentWillUnmount()




**What types of things can you pass in the props?** 

we can pass any data type even function

**What is the big difference between props and state?**

props are variables __passed__ to a react component by its parent and it a read only variables and we can use it to initialize state

state also variables but it declare and manage by the component itself in otherwise state inside the component

**When do we re-render our application?**

whenever there is a change in their state or props

**What are some examples of things that we could store in state?**

counter ,likes ,name ,location ,etc.

---------
## Things I want to know more about

i just hope to be familiar with react it self and using the stats and props..



---------------------

recourses :
   [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)