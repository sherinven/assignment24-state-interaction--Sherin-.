# Assignment 4 - State & Interaction

This project contains 7 React components demonstrating various state management and interaction concepts.

## Components Included:

### 1. Counter (Task 1)
- Uses `useState` to manage a counter value
- Buttons to increase (+1), decrease (-1), and reset (0) the counter
- Demonstrates basic state manipulation

### 2. Toggle Message (Task 2)
- Uses boolean state to control visibility of a message
- Button toggles between "Show" and "Hide"
- Conditionally renders "Hello React!" message using `&&` operator

### 3. Simple Login Status (Task 3)
- Boolean state tracks login status
- Shows "Login" button when logged out
- Shows "Welcome back!" message and "Logout" button when logged in

### 4. Fruit List Renderer (Task 4)
- Renders a list of fruits using `.map()`
- Each list item has a unique key
- Displays total fruit count
- Demonstrates list rendering in React

### 5. Add Item to List (Task 5)
- Controlled input component with `useState`
- Adds items to a dynamic list
- Input clears after adding an item
- Demonstrates state array manipulation

### 6. Lifting State Up (Task 6)
- Parent component holds state
- Child component receives state and update function via props
- Demonstrates lifting state up pattern
- Child component does not maintain its own state

### 7. Simple Form (Task 7)
- Controlled form with name and email inputs
- Prevents default form submission
- Displays submitted data below the form
- Uses `onChange` handlers for controlled inputs

## Running the Application

To run this application, make sure you have Node.js installed, then:

1. Navigate to the project directory
2. Run `npm install` to install dependencies
3. Run `npm start` to start the development server

The application will open in your default browser at http://localhost:3000
