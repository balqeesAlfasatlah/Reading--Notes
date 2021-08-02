# React: Component Lifecycle

1. What are component lifecycle events ?

* React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. 

* These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

* Mounting, Updating, and Unmounting are the three phases of the component lifecycle.

![](https://miro.medium.com/max/1400/1*6X_7HKFdQoh9eXqWgwQuvQ.png)


### **Mounting :** 

When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

### **Updating :**

Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

### **Unmounting :**

The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

**React Lifecycle Events**

![React Lifecycle Events](https://miro.medium.com/max/1244/1*4y9V5936WdJKaIeVPFEa3w.png)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

   the render.
2. What is the very first thing to happen in the lifecycle of React?

   **static getDerivedStateFromProps()**, The static getDerivedStateFromProps is the first React lifecycle method to be invoked during the updating phase.

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates :

   constructor , render  ,componentDidMount , React Updates , componentWillUnmount


   ## Props :

---

  1. What types of things can you pass in the props?

    Its allows us to pass values from a parent component down to a child component. The values can be any data type, from strings to functions, objects, etc.


2. What is the big difference between props and state?

   state is hadeled in the component and we can updete it inside the component but the props is hadeled outside the component and we must be updete  outside the component

3. When do we re-render our application ?

   React components automatically re-render whenever there is a change in their state or props.

4. What are some examples of things that we could store in state?

   things that we want to updates like counter 