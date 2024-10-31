
### A simple meal ordering application built with React that allows users to select meals, add them to a cart, view total costs, and submit their orders. This app demonstrates basic React functionality with components, state management, and form submission.

## Features

- **Meal Selection**: Choose from a list of meals with their descriptions and prices.
- **Add to Cart**: Add selected meals to a shopping cart with dynamic updates.
- **Cart Management**: View the list of items in the cart, including quantity, individual prices, and total cost.
- **Order Submission**: Submit the order to proceed to the checkout.

## Project Structure

The project is divided into core components to maintain simplicity and reusability:

- **`App.js`**: The main component that holds the layout and structure of the app.
- **`Meals.js`**: Renders the list of available meals and provides an "Add to Cart" button.
- **`MealItem.js`**: A reusable component for each meal that displays meal details and handles quantity input.
- **`Cart.js`**: Displays cart items, total price, and an order submission button.
- **`CartItem.js`**: Manages each item in the cart, allowing users to update quantities.
- **`OrderForm.js`**: A form for submitting the order, prompting users for details like name and address.

## Technologies Used

- **React**: Component-based UI framework.
- **CSS Modules**: Scoped CSS for styling individual components.
- **React Hooks**: For managing state and side effects.
