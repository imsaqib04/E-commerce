# 🛒 Django E-commerce Website

A simple and functional **e-commerce website** built with **Django**.
It allows users to browse products, manage a shopping cart, and place orders, while providing an **admin dashboard** for product and order management.

---

## ✨ Features

* **Product Catalog** – Browse all available products.
* **Search** – Quickly find products by name.
* **Product Detail Page** – View detailed product information.
* **Shopping Cart** – Add products to the cart (data stored in browser’s local storage).
* **Checkout** – Fill in shipping details and place orders.
* **Admin Panel** – Manage products and orders with Django’s built-in admin interface.

---

## 📂 Project Structure

```
ecomsite/              # Main project directory
    settings.py        # Project settings and configurations
    urls.py            # Main URL routes

shop/                  # E-commerce app
    models.py          # Database models (Product, Order)
    views.py           # Logic for product list, details, checkout
    templates/         # HTML templates
    static/            # CSS, JavaScript, images

manage.py              # Django management script
```

---

## 🚀 Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/imsaqib04/e-commerce.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd e-commerce/E-commerce-5b03ec5e39aa0815cc273971c31b709f3a8e95b5
   ```

3. **Install dependencies**

   ```bash
   pip install Django
   ```

4. **Apply database migrations**

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (for admin panel)**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**

   ```bash
   python manage.py runserver
   ```

---

## 🌐 Access

* **Website:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
* **Admin Panel:** [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) (login with superuser credentials)

---

## 📸 Screenshots
<img width="1881" height="946" alt="image" src="https://github.com/user-attachments/assets/2dd1caa5-1316-49eb-a614-08c0207b24db" />

<img width="1919" height="926" alt="image" src="https://github.com/user-attachments/assets/f82c6816-d0e0-43cd-b6f5-c688c9a8abcf" />

<img width="1888" height="934" alt="image" src="https://github.com/user-attachments/assets/b45a6deb-152c-4cf5-a8c1-5adb35d3cd2f" />

<img width="1891" height="947" alt="image" src="https://github.com/user-attachments/assets/978070a2-04d5-41c8-8d90-c894ffd06425" />


---

## 📜 License

This project is licensed under the **MIT License** – you’re free to use, modify, and distribute it.

---

## 👨‍💻 Author

**Mohd Saqib** – [GitHub Profile](https://github.com/imsaqib04)

---
