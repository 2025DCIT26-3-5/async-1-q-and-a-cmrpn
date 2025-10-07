# Destructuring Assignment

## Q: In a functional React component, you receive props as an object { name, age, city }. How would you use JavaScript destructuring to extract those values, and why is it useful?

## A: You can destructure directly in the function signature or inside the function body. 





# Arrow Functions

## Q: What is the difference between using a regular function and an arrow function in event handlers or callback props in React?

## A: Arrow functions do not have their own this, arguments, or prototype. In React components (especially class components), arrow functions help preserve the this context without needing to .bind(this).




# Spread & Rest Operators

## Q: Explain how the spread operator is used to update state immutably in React. Also, contrast with how you might use the rest operator in function parameters.

## A: Spread: When updating an object or array in React state, you shouldn’t mutate the existing state. Instead, use the spread operator to create a new copy. Rest: In function parameters, rest syntax groups the remaining arguments.



# Array Methods

## Q: Which array methods are especially useful when working in React, and can you show an example where you map over an array of objects to render a list?
## A: Common array methods include .map(), .filter(), .reduce(), .find(), and .forEach() (though forEach is less often directly used in JSX).




# Template Literals
## Q: How do template literals (backticks) help when writing JSX or JavaScript that concatenates strings and variables? Provide an example.
## A: Template literals (`…`) allow embedding expressions using ${…} and support multiline strings. They’re cleaner than concatenation with +.



# Conditional (Ternary) Operator
## Q: In JSX, how would you render one element if a condition is true and another element otherwise, using the ternary operator? Provide a code snippet.
## A: You can inline a ternary inside JSX.


## MODIFIED BY JOHN CARLO CATIBOG