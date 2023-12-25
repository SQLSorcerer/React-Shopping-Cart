# Shopping Cart Built in React JS with Context API and useReducer

## React Shopping Cart

This project is a simple shopping cart application built using React JS, Context API, and useReducer. It provides a straightforward example of managing state in a React application with the help of Context and useReducer to handle the shopping cart functionality.

### Features

- **Add Products**: Easily add products to the shopping cart.
- **Remove Products**: Remove items from the cart with a simple click.
- **Quantity Control**: Adjust the quantity of each product in the cart.
- **Total Calculation**: Real-time calculation of the total price based on the items in the cart.

### Technologies Used

- **React JS**: A JavaScript library for building user interfaces.
- **Context API**: A React feature that enables the sharing of state between components without the need for prop drilling.
- **useReducer**: A React hook for managing complex state logic in a more organized manner.
- **CSS**: Styling is done using CSS for a clean and responsive design.

### How to Run

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/your-username/react-shopping-cart.git
   ```

2. Navigate to the project directory.
   ```
   cd react-shopping-cart
   ```

3. Install dependencies.
   ```
   npm install
   ```

4. Run the application.
   ```
   npm start
   ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000).

### Project Structure

```
react-shopping-cart/
│
├── src/
│   ├── components/
│   │   ├── Cart.js
│   │   ├── Product.js
│   │   ├── ProductList.js
│   │   └── ShoppingCart.js
│   │
│   ├── context/
│   │   └── CartContext.js
│   │
│   ├── reducers/
│   │   └── cartReducer.js
│   │
│   ├── App.js
│   ├── index.js
│   └── styles.css
│
├── .gitignore
├── package.json
├── README.md
└── LICENSE
```

### Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy coding!