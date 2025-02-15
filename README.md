# React Assignments

Welcome to your first set of React assignments! These exercises are designed to help you understand the basics of React, such as components, props, and event handling. **Do not use hooks** in these assignments.

---

## Assignment 1: Create a Simple React Component

### Task:
- Create a React application with a functional component named `Greeting`.
- This component should display a heading with the text: `"Hello, welcome to React!"`.
- Render this component inside `App.js`.

### Expected Output:
```
Hello, welcome to React!
```

---

## Assignment 2: Using Props in a Component

### Task:
- Create a component named `UserInfo` that accepts **name** and **age** as props.
- Display the name and age inside a paragraph.
- Pass different values for name and age from `App.js`.

### Example Output:
```
User Name: John Doe
Age: 25
```

---

## Assignment 3: Create a Simple Button with Event Handling

### Task:
- Create a `ButtonComponent` that renders a button with the text **Click Me**.
- When the button is clicked, show an alert with the message **"Button Clicked!"**.
- Use a function inside the component to handle the click event.

---

## Assignment 4: Display a List of Items

### Task:
- Create a component named `ItemList`.
- It should receive an array of items as props and display them as a list (`<ul>` and `<li>`).
- Pass an array like `['Apple', 'Banana', 'Cherry']` from `App.js`.

### Example Output:
```
- Apple
- Banana
- Cherry
```

---

## Assignment 5: Conditional Rendering

### Task:
- Create a component named `StatusMessage` that accepts a prop `isLoggedIn` (Boolean).
- If `isLoggedIn` is `true`, display "Welcome, User!".
- If `false`, display "Please log in".
- Pass both `true` and `false` values from `App.js` to test the output.

### Example Outputs:
1. If `isLoggedIn` is `true`: 
   ```
   Welcome, User!
   ```
2. If `isLoggedIn` is `false`: 
   ```
   Please log in
   ```

---

### Submission Instructions:
1. Complete each assignment in a separate component file (e.g., `Greeting.js`, `UserInfo.js`, etc.).
2. Import and use these components in `App.js`.
3. Run your application and verify the outputs.
4. Submit your code as a GitHub repository.
