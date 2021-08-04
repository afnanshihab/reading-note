# Thinking in React 
![mock](https://miro.medium.com/max/1148/1*CTlLMggdjx6uLyHicPAdqg.png)



* To break a mock into a component heirarchy, we can start by drawing boxes around components and their subcomponents, this is similar to what we used to do when building or drawing a wireframe for a website, then as we do when we think about a problem that might need a special function or object, to be responsible for doing a specific task or set of tasks, in order to be able to decide what pieces of our website need to be a stand alone component.

* The single responsibility principle is a principle used to help choosing which parts of an application deserve to be a component, this is done by thinking about the functionality a component might be able to provide. And if you think about it, when you do that correctly, this will reflect on the UI itself, and you will notice that this also helps make the UI more consistent depending on the data and information the component handle.

* To build a static version of an app is similar to saying that we want to only see the UI and the data model, but the website will have no interactivity, so the components will only have the render() method at this stage, and passing data is only done using props.

* Once you have the static version of your app you will then need to add things that will handle the state, that is, to add interactivity.

-------------------
### single responsibility principle
![single responsibility principle](https://csharpcorner-mindcrackerinc.netdna-ssl.com/article/solid-single-responsibility-principle-with-c-sharp/Images/image001.png)


***What is the single responsibility principle and how does it apply to components?***
single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.


***What are the three questions you can ask to determine if something is state?***
1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.


resource [Thinking in React ](https://reactjs.org/docs/thinking-in-react.html)

***Things I want to know more about ?***

Knowing more about react and bootsrap and others libraries .