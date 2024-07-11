## Flask Application Design for Indian Snack Shop

### HTML Files

- **index.html**: This serves as the landing page of the snack shop. It displays a list of all the available snacks, along with their prices and descriptions.
- **menu.html**: This page allows users to browse the snack menu, filter by categories, and search for specific snacks.
- **order.html**: This page handles the ordering process, allowing users to select snacks, specify quantities, and provide their details.
- **confirmation.html**: After the order is placed, this page confirms the order summary and provides a unique order ID for tracking.

### Routes

- **@app.route('/')**: The root route that displays the landing page (index.html).
- **@app.route('/menu')**: This route displays the snack menu page (menu.html).
- **@app.route('/order')**: This route renders the order page (order.html), where users can select snacks and place an order.
- **@app.route('/place_order')**: This route handles the order submission, processes the order details, and redirects to the confirmation page.
- **@app.route('/confirmation')**: This route displays the order confirmation page (confirmation.html) with the order summary.

### Implementation Details

- The HTML files should be created using Bootstrap for a responsive and modern user interface.
- The routes in the Flask application should handle requests, process data, and render the appropriate HTML pages.
- The application should use a database to store the snack inventory and order history.
- Consider implementing user authentication and order tracking features for a more complete solution.