# Context API Task

This is a simple web application for a mobile store. It allows users to manage their shopping cart. The application utilizes React's Context API to manage global state across components.

## Features

### 1. Navigation Bar

The navigation bar provides easy access to different sections of the website:
- **Cart**: Displays the total number of items in the user's shopping cart. Clicking on it redirects the user to their cart.

### 2. Product Listing

Products are displayed in a grid format, showing essential details such as product image, title, price, and available stock. Users can browse through the products and click on them to view more details.

### 3. Shopping Cart

Users can add products to their shopping cart by clicking on the "Add to Cart" button on the product detail page. The cart icon in the navigation bar shows the total number of items added to the cart. Users can also remove items from the cart or adjust the quantity of each item.


## Implementation Details

### Dynamic Price and Quantity Increase

- When the user increases the quantity of a product in the shopping cart, the price and quantity are dynamically updated.
- This functionality is implemented using the Context API to manage the state of the shopping cart across components.
- The `CartComp` component handles the logic for increasing the quantity and calculates the updated price based on the quantity and the original price of the product.

## Technologies Used

- **React**: A front-end library used for building user interfaces. React provides a component-based architecture that simplifies the development process and enhances code reusability.
- **Bootstrap**: A CSS framework that facilitates the creation of responsive and mobile-first web designs. Bootstrap offers pre-designed components and utilities for styling, layout, and interactive elements.
- **Font Awesome**: A library that provides a wide range of icons for web applications. Font Awesome icons enhance the visual appeal and usability of the application by providing scalable vector icons that can be easily customized and integrated into the UI.
