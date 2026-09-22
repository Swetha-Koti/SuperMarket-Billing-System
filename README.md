# SuperMarket Billing System

A web-based SuperMarket Billing System developed using HTML, CSS, and JavaScript. The application allows users to browse grocery products, search for items, manage a shopping cart, complete checkout, select payment methods, and generate a printable bill.

## Features

### 1. User Registration
- Create a new customer account.
- Collects name, email, phone number, and password.
- Validates required registration fields.
- Stores registration details using browser LocalStorage.

### 2. User Login
- Login using email and password.
- Basic input validation.
- Redirects the user to the supermarket home page after login.

### 3. Product Browsing
- Products are organized into different categories.
- Users can browse grocery items and view their prices.
- Product cards display product images, names, prices, and an Add to Cart button.

### 4. Product Search
- Search products using the search bar.
- Search by product name or category.
- Matching products are displayed dynamically.

### 5. Voice-Based Search
- Supports voice-based product searching.
- Uses the Web Speech API.
- Users can speak a product or category instead of typing it.

### 6. Shopping Cart
- Add products to the shopping cart.
- View selected products through the cart popup.
- Remove products from the cart.
- Automatically calculates the subtotal.
- Adds the delivery fee to calculate the total amount.

### 7. Checkout and Billing
- Displays an order summary before placing the order.
- Collects customer delivery information.
- Validates customer details.
- Calculates the final bill automatically.

### 8. Payment Options
The checkout system provides multiple payment methods:

- Credit Card
- Debit Card
- UPI
- Cash on Delivery

Credit/Debit Card and UPI details are displayed according to the selected payment method.

### 9. Voice-Based Payment Selection
- Users can select the payment method using voice commands.
- Supports commands such as Credit Card, Debit Card, UPI, and Cash.

### 10. Bill Generation
- Generates an order receipt after placing an order.
- Displays:
  - Order ID
  - Date and time
  - Customer information
  - Ordered products
  - Quantity
  - Price
  - Subtotal
  - Delivery fee
  - Total amount
  - Payment method
- Provides an option to print the receipt.

### 11. Local Storage
- Stores cart information using browser LocalStorage.
- Preserves cart items while navigating between pages.
- Stores user registration information locally.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure of web pages |
| CSS3 | Styling and responsive user interface |
| JavaScript | Application functionality and interaction |
| LocalStorage | Client-side data storage |
| Web Speech API | Voice search and voice-based payment selection |
| Font Awesome | Icons and visual elements |

---

