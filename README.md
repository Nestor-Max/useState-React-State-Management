# useState-React-State-Management
This project is a simple React application that demonstrates the use and learning of useState in React state management. useState is a hook that allows you to store and update a state variable in a functional component. The project consists of two components: Counter and NameList.

The Counter component uses useState to manage the state of a count variable, which represents the number of times the user clicks a button. The component renders a button that displays the count value and has an onClick handler that calls a function to increment the count by one. The function uses the previous state value as an argument to the setState function, which updates the state and triggers a re-rendering of the component.

The NameList component uses useState to manage the state of two variables: lists and name. lists is an array of strings that represents the names to be displayed in a list, and name is a string that represents the input value entered by the user. The component renders an input element that allows the user to type a name and a button that adds the name to the lists array. The component also renders a list of elements that map the lists array to JSX elements. The component uses the spread operator to create a new array with the updated values and calls the setState function with the new array. This way, React detects the change in the reference and re-renders the component.

The App component renders both the Counter and the NameList components inside a div element. The App component is the root component of the application and is exported as the default module.

This project is a good way to learn how to use useState in React state management, as it shows how to store and update simple and complex data types, how to use the previous state value to calculate the new state, how to avoid mutating the state directly, and how to render the state as UI elements. 
