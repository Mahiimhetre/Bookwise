# BookWise

Welcome to **BookWise**, a college project designed to be your ultimate destination for literary exploration! BookWise is an online bookstore platform where users can discover, browse, and purchase books from a diverse collection, spanning every genre and interest.

---

## 🎓 Project Context

**BookWise** is developed as a part of a college project to demonstrate full-stack web development, database integration, and user experience design.

---

## 🌟 Why Choose BookWise?

- **Extensive Collection:** Find bestsellers, classics, and hidden gems curated for every reader's appetite.
- **Personalized Recommendations:** Discover your next favorite read with suggestions tailored to your interests.
- **Seamless Shopping Experience:** Enjoy a user-friendly interface, secure transactions, and fast home delivery.
- **Dedicated Customer Support:** Our team is always ready to help you with recommendations or service inquiries.
- **Community:** Join a vibrant community of book lovers and embark on your literary journey.

---

## ✨ Features

- Browse and search books by genre, author, or title
- Add books to your shopping cart and place orders securely
- User authentication (login/register)
- Customer reviews and ratings
- Admin dashboard for managing products, orders, users, and messages
- Responsive design for all devices
- Contact form for customer support and queries

---

## 🚀 Getting Started

### Prerequisites

- PHP (with MySQLi extension)
- MySQL Database
- Web server (Apache, Nginx, or XAMPP/WAMP/LAMP stack)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/Mahiimhetre/Bookwise.git
   cd Bookwise
   ```

2. **Set up the Database**

   - Create a new MySQL database (e.g., `bookwise_db`).
   - Import the provided SQL schema (if available) or set up tables/fields as per the `config.php` usage.

3. **Configure Database Connection**

   - Edit the `config.php` file with your database credentials:

     ```php
     $conn = mysqli_connect('localhost', 'your_username', 'your_password', 'bookwise_db');
     ```

4. **Run the App**

   - Place the project files in your web server's root directory.
   - Access the site via `http://localhost/Bookwise/home.php`.

---

## 📂 Project Structure

- `home.php` - Main landing page
- `about.php` - About us and customer reviews
- `shop.php` - Book browsing and purchasing
- `cart.php` - Shopping cart page
- `orders.php` - User's orders
- `contact.php` - Contact and support
- `admin_*` files - Admin panel for managing the store
- `css/` - Stylesheets
- `images/` - Image assets
- `js/` - JavaScript files

---

## 🛠️ Technologies Used

- PHP
- MySQL
- HTML5 & CSS3
- JavaScript
- Font Awesome

---

## 📢 Customer Testimonials

> "This website is a book lover's paradise! From classic literature to the latest bestsellers, they have it all. Plus, their user-friendly interface makes browsing and purchasing a breeze."
> — Happy Customer

> "I love supporting independent bookstores, and this one quickly became my favorite. Highly recommended!"
> — Book Enthusiast

---

## 💁‍♂️ Support

For any questions or issues, feel free to open an issue on this repository or contact our support team through the website.

---

**Experience the joy of reading like never before – start exploring BookWise today!**
