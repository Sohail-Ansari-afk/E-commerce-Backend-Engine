# 🛒 E-commerce Backend Engine

A full-featured backend and admin panel for an e-commerce system built using **Python**, **Streamlit**, and **SQLAlchemy**. It supports admin and user roles, product management, cart, and order handling — all with a clean UI! 🎨

---

## 🚀 Features

✅ User Authentication (Login/Register)  
✅ Role-based Access (Admin/User)  
✅ Product Management 🛍️  
✅ Shopping Cart 🛒  
✅ Order Placement & Tracking 📦  
✅ Admin Dashboard & User Control Panel 🛠️  
✅ SQLite Database Backend 🗃️

---

## 📦 Installation

1. ✅ **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ecommerce-backend-engine.git
   cd ecommerce-backend-engine
````

2. 🐍 **Create and Activate a Virtual Environment (Recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate     # On Windows: venv\Scripts\activate
   ```

3. 📥 **Install Dependencies**

   ```bash
   pip install streamlit sqlalchemy bcrypt
   ```

---

## ⚙️ File Structure

```bash
📁 ecommerce-backend-engine
│
├── E-commerce Backend Engine.py   # 🧠 Main Streamlit App
├── ecommerce.db                   # 🗄️ Auto-created SQLite DB
└── README.md                      # 📘 This file
```

---

## ▶️ Running the App

Just execute this in your terminal:

```bash
streamlit run "E-commerce Backend Engine.py"
```

Then open the displayed localhost URL in your browser. 🌐

---

## 🧑‍💻 Admin vs User Roles

* **Admin:**

  * Add/Update products
  * View and change order statuses
  * Manage users (activate/deactivate)

* **User:**

  * Browse products
  * Add to cart and place orders
  * View their past orders

You can create admin users manually by modifying the `register_user()` call in code:

```python
register_user("adminuser", "adminpass", role="admin")
```

---

## 🗃️ Database Info

* SQLite is used as the backend.
* File: `ecommerce.db`
* Automatically created when the app starts.

---

## 📸 Screenshots

*(You can add screenshots here)*
![screenshot-placeholder](https://via.placeholder.com/800x400?text=Add+your+screenshots)

---

#🛠️ Future Improvements

* 🧾 Add product image support
* 📬 Email notification system
* 📊 Sales analytics for admin
* 🔒 JWT/Session-based login auth


---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

``
