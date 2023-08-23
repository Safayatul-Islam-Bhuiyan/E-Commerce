# E-Commerce Website

Welcome to the E-Commerce Website project repository. This dynamic Django-based e-commerce website offers a seamless shopping experience for buyers, secure payment gateway integration, and comprehensive product management for admins.

## Features

- **User Registration and Authentication:** Buyers can register and log in to the website to access personalized features.

- **Shopping Cart Functionality:** Users can add products to their cart, review items, and proceed to checkout.

- **Secure Payment Gateway Integration:** The website integrates a secure payment gateway for safe and reliable transactions.

- **Efficient Product Management (Admin):** Admins can manage items, categories, and stock levels through a user-friendly admin panel.

- **Product Review System:** Users can leave product reviews and ratings, enhancing user engagement.

## Technology Stack

- Django: The web framework used to develop the project.
- HTML: Markup language for creating web pages.
- Bootstrap: Front-end framework for responsive and attractive UI.

## Getting Started

Follow these instructions to get started with using the E-Commerce Website.

### Prerequisites

- Python 3.x
- Git

### Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Safayatul-Islam-Bhuiyan/e-commerce.git
    cd e-commerce
    ```

2. **Create and Activate Virtual Environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install Dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Configure Database:**

    Open `ecommerce/settings.py` and configure your database settings, such as using SQLite for development:

    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.sqlite3',
            'NAME': os.path.join(BASE_DIR, 'db.sqlite3'),
        }
    }
    ```

5. **Apply Migrations:**

    ```bash
    python manage.py migrate
    ```

6. **Create Superuser:**

    ```bash
    python manage.py createsuperuser
    ```

7. **Run the Development Server:**

    ```bash
    python manage.py runserver
    ```

8. **Access the Application:**

    Open a web browser and go to `http://localhost:8000/` to access the website.

## Usage

1. **User Registration and Login:**

    - Register as a new user on the website.
    - Use your credentials to log in.

2. **Browsing and Shopping:**

    - Browse the product catalog.
    - Add items to your cart.
    - Review your cart and proceed to checkout.

3. **Admin Product Management:**

    - Log in as an admin user.
    - Access the admin panel at `http://localhost:8000/admin`.
    - Manage items, categories, and stock levels.

4. **Product Review:**

    - Logged-in users can leave product reviews and ratings.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.


## Acknowledgments

- [Django Documentation](https://docs.djangoproject.com/): For comprehensive information on using Django.
- [Bootstrap Documentation](https://getbootstrap.com/docs/): For guidance on using Bootstrap for front-end design.
