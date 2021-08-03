
# Forms

### 1. What is a ‘Controlled Component’?

 is a component that renders form elements and controls them by keeping the form data in the component's state. In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state.

 ### 2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

 we should update the state with users responses as soon as they enter them because since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.


 ### 3. How do we target what the user is entering if we have an event handler on an input field?

 the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React 

 ---

 # The Conditional (Ternary) Operator

 1. Why would we use a ternary operator?

 because we  could do the same as if statement do in just one line of code.

 2. Rewrite the following statement using a ternary statemen:

    x === y  ? 'Yes' : 'No';

