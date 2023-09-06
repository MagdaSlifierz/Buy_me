# Buy Me Shop - Django E-commerce Website

Welcome to the Buy Me Shop Django E-commerce Website! This project is a web application built using Django, a Python web framework. It enables users to browse and purchase products, manage their shopping carts, apply coupons, and make payments. This README provides an overview of the project's structure and functionality.

## Project Structure

The project's main functionality is divided into several Django apps:

- **cart**: Handles shopping cart management.
- **orders**: Manages customer orders and order creation.
- **payment**: Integrates payment processing using Stripe.
- **coupons**: Allows users to apply coupons for discounts.
- **shop**: Manages product listings and product detail pages.
- **admin**: Provides administrative features for managing orders.

The project's URL routing and configuration are defined in the `urls.py` file in the project's root directory. This file maps URLs to their respective views and namespaces for each app.

## Usage

Once the project is set up, you can use it as an e-commerce website. Here are some key features:

- **Browse Products**: Visit the homepage to browse and view products.

- **Add to Cart**: Add products to your shopping cart with desired quantities.

- **Manage Cart**: Go to the cart page to view and manage the items in your cart. You can update quantities or remove items.

- **Apply Coupons**: On the cart page, you can apply coupons for discounts.

- **Checkout**: Proceed to checkout to enter your order details and make a payment using Stripe integration.

- **View Orders**: Logged-in users can view their order history.

- **Admin Interface**: Access the admin interface at `/admin/` to manage products, orders, and coupons.

## Features

- User-friendly e-commerce website built with Django.
- Shopping cart management with quantity updates and removal.
- Coupon code application for discounts.
- Secure payment processing using Stripe.
- Product recommendations based on user cart contents.
- Administrative interface for managing products and orders.

## Technologies Used

This project is built with the following technologies:

Django: A high-level Python web framework for building web applications.
Stripe: A popular payment processing platform for handling payments securely.
HTML/CSS: For structuring and styling web pages.
JavaScript: For client-side interactivity.
Bootstrap: A front-end framework for responsive web design.
Python: The programming language used for the backend logic.
SQLite: The default database used for data storage.
  
## Installation

Before running the project, you need to set up a Python environment and install the required dependencies. Here are the steps to get started:

1. Create a Python virtual environment (recommended):
   ```bash
   python -m venv myenv
   ```

2. Activate the virtual environment:
   - On Windows:
     ```bash
     myenv\Scripts\activate
     ```
   - On macOS and Linux:
     ```bash
     source myenv/bin/activate
     ```

3. Navigate to the project directory and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser account to access the Django admin interface:
   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:
   ```bash
   python manage.py runserver
   ```

The project should now be accessible at `http://localhost:8000/`.


## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them with descriptive messages.
4. Push your branch to your fork: `git push origin feature/your-feature-name`.
5. Create a pull request from your fork's branch to the main repository.
