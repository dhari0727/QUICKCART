# 🛒 QuickCart

**QuickCart** is a Django-based eCommerce web application that allows users to browse, filter, and purchase products online. It features a user-friendly interface for customers and a powerful admin panel for store owners to manage products, orders, users, and gain insights.

---

## 🌟 Features

### 👤 User Panel
- Browse and search products
- Filter by price range
- Guest and logged-in cart support
- Cart merges on login
- Secure checkout and order tracking

### 🛠️ Admin Panel
- Full product, order, and user management
- Insights into geographical trends and top products
- Monitor user activity and sales performance
- Admin dashboard with analytics

---

## ⚙️ Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap/Tailwind
- **Database**: SQLite (or PostgreSQL)
- **Authentication**: Django's built-in auth system

---

## 🚀 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/dhari0727/QUICKCART.git
cd QUICKCART
python -m venv venv
venv\Scripts\activate         # For Windows
# OR
source venv/bin/activate      # For Linux/macOS

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Admin Access

```bash
 python manage.py createsuperuser
```
Then login at http://127.0.0.1:8000/admin/

👩‍💻 Author
Dharini Thakkar


