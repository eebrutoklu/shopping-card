# Shopping Cart Application

This project contains a simple shopping cart application. Users can add various products to their cart, view their carts, and clear their carts.

## Features

- View products
- Add products to cart
- View cart
- Clear cart

## Technologies Used

- HTML
- CSS
- JavaScript

### JavaScript Description

This project includes the JavaScript part of a shopping cart application. JavaScript provides the dynamic functionality of the application. Here are the main components in the JavaScript file:

#### 1. Variable Definitions

- `cartBtn`, `clearCartBtn`, `cartItems`, `cartTotal`, `cartContent`: Used to select HTML elements.
- `productDOM`: Selects the section where products are displayed.
- `cart`: Used to store the content of the cart.
- `buttonsDOM`: Holds the buttons used to add products.

#### 2. Fetch API

- Fetch API is used to fetch data from an API asynchronously.

#### 3. `Products` Class to Retrieve Products

- The `getProducts` method fetches products from an API and returns them.

#### 4. `UI` Class to Manage User Interface

- The `displayProducts` method displays products within HTML.
- The `getBagButtons` method manages the add-to-cart buttons for each product.
- The `saveCartValues` method calculates and displays the total value and number of items in the cart.
- The `addCartItem` method displays the products added to the cart within HTML.
- The `showCart` method opens the cart.
- The `setupApp` method initializes the application and loads cart data from localStorage.
- Other methods like `populateCart`, `cartLogic`, `clearCart`, `removeItem`, and `updateButtons` manage cart functionality.

#### 5. `Storage` Class to Manage Database Interaction

- Methods like `saveProducts`, `getProduct`, `saveCart`, and `getCart` are used to store and load products and the cart in localStorage.

#### 6. Post-DOM Load Operations

- The `DOMContentLoaded` event initializes product and cart functionality after the page is loaded.

This JavaScript file provides the basic functionality of the shopping cart application and offers a dynamic user experience by interacting with HTML.

## Responsive

![Desktop](./responsive/desktop.gif)
![Tablet](./responsive/tablet.gif)
![Mobile](./responsive/mobile.gif)

## Contributions

Images for the project were created using Leonardo AI. If you have any suggestions or contributions, please open a pull request.

## License

This project is for educational purposes and is not suitable for commercial use.
