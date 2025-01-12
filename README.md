Django eCommerce Website
This project is a full-fledged eCommerce website built using Django, a high-level Python web framework. It includes essential features such as user authentication, product browsing, cart management, checkout process, payment integration, and more. The website is designed to be robust, scalable, and user-friendly, providing a seamless shopping experience for customers.

Table of Contents
Features
Screenshots
Technologies Used
Setup Instructions
Usage
Contributing
License
Features
User Authentication: Secure user registration, login, reset password, and profile management.
Product Catalog: Browse and search products with detailed descriptions and images.
Shopping Cart: Add, update, and remove items from the cart seamlessly.
Checkout Process: Smooth checkout flow with order summary and address management.
Payment Integration: Integrated with Razorpay for secure online payments.
Order Management: View order history and status updates.
Responsive Design: Mobile-friendly UI ensuring a consistent experience across devices.
Admin Panel: Manage products, orders, and users efficiently through Django's admin interface.
Features
A few of the things you can do with this app:

Admin can create/update/delete Product Category
Admin can create/update/delete Product Detail
Authenticated Users can make POST requests to Product Category & Product Detail
Unauthenticated Users can only make GET requests to Product Category & Product Detail
Users can SignUp to be authorized
Authorized Users can make Payment & Order Products
Screenshots
Home Page
Homepage Screenshot

Wishlist Page
Homepage Screenshot

Order History Page
Homepage Screenshot

Order Details Page
Homepage Screenshot

Contact-Us Page
Contact-Us Screenshot

About-Us Page
About-Us Screenshot

Product Page
Product Page Screenshot

Shopping Cart Page
Cart Page Screenshot

Login Page
Login Page Screenshot

Register Page
Register Page Screenshot

Forgot Password Page
Forgot Page Screenshot

Profile Page
Forgot Page Screenshot

Address Page
Forgot Page Screenshot

Change Password View
Forgot Page Screenshot

Technologies Used
Django: Python-based web framework for backend development.
HTML/CSS/JavaScript: Frontend development for a responsive and interactive UI.
Razorpay API: Payment gateway integration for secure transactions.
Bootstrap: Frontend framework for responsive design and UI components.
Setup Instructions
To run this project locally, follow these steps:

Clone the repository:

git clone git
cd Django-eCommerce-Website
Create a virtual environment:

python -m venv venv
Activate the virtual environment:

On Windows:
.\venv\Scripts\activate
On macOS/Linux:
source venv/bin/activate
Install dependencies:

pip install -r requirements.txt
Apply database migrations:

python manage.py migrate
Create a superuser (admin):

python manage.py createsuperuser
Start the development server:

python manage.py runserver
Open your web browser and navigate to:


