# e-plantShopping

A simple e-commerce web application for browsing and purchasing plants online. Built with HTML, CSS, and JavaScript, this project provides a user-friendly interface for plant enthusiasts to explore a variety of plants, view details, and manage their shopping experience.

## Table of Contents

- [About](#about)
- [Working Principle](#working-principle)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About

`e-plantShopping` is a front-end web application designed to simulate an online plant store. Users can browse a catalog of plants, view details such as price and description, and add items to a cart. The application leverages JavaScript for dynamic functionality, CSS for styling, and HTML for structure.


## Working Principle

The `e-plantShopping` application operates as a client-side web application with the following core functionalities:

1. **Plant Catalog Display**: The application uses HTML and CSS to render a visually appealing catalog of plants. JavaScript dynamically populates the catalog, potentially fetching plant data from a local JSON file or static array.
2. **Interactive Features**: Users can interact with the catalog to view plant details (e.g., name, price, description) and add items to a shopping cart. JavaScript handles event listeners for user actions like clicking "Add to Cart" or filtering plants.
3. **Responsive Design**: CSS ensures the application is responsive, adapting to various screen sizes for an optimal user experience on desktops and mobile devices.
4. **Cart Management**: JavaScript manages the shopping cart, allowing users to add, remove, or view selected plants. The cart state may be stored in memory (e.g., using localStorage) for persistence during the session.
5. **Static Front-End**: As a front-end-only application, it does not include a back-end server or database, relying on client-side logic for functionality.

The application is built to be lightweight and user-friendly, focusing on a seamless browsing and shopping experience for plant enthusiasts.

## Installation

To run the `e-plantShopping` application locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/allenjose24/e-plantShopping.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd e-plantShopping
   ```

3. **Open the Application**:
   - Open `index.html` in a web browser (e.g., Chrome, Firefox) directly, or
   - Use a local development server for a better experience:
     ```bash
     npx http-server
     ```
     Then navigate to `http://localhost:8080` in your browser.

*Note*: No additional dependencies are required since the project uses vanilla HTML, CSS, and JavaScript.

## Usage

1. Open the application in a web browser.
2. Browse the plant catalog displayed on the homepage.
3. Click on a plant to view its details or add it to the cart.
4. Use the cart feature to review selected items and proceed to checkout (simulated).
5. Explore responsive design by resizing the browser or accessing it on a mobile device.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request on GitHub.

Please ensure your code follows the existing style and includes appropriate comments.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.
