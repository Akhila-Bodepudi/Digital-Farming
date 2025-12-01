# AgroNity – Digital Farming Platform 🌱

AgroNity is a web-based **digital farming platform** that connects farmers and customers,
helps farmers make better crop decisions using data, and provides a learning hub for
modern farming practices.

The goal is to **empower farmers** with technology instead of just building another
grocery app.

---

## 🌟 Key Features

- **Farmer Registration & Login**
  - Farmers can create accounts, manage their profiles, and list crops for sale.

- **Customer Registration & Ordering**
  - Customers can browse available crops and place orders directly from farmers.

- **Soil-Based Crop Recommendation**
  - Suggests suitable crops based on soil / environmental data (and can be extended
    with larger datasets and ML models).

- **Learning Hub (Farming Tutorials)**
  - Embedded video tutorials and guides to help farmers learn best practices.

- **Basic Marketplace**
  - Farmers list crops, quantities, and prices.
  - Customers view crop details and order.

- **Admin Panel**
  - Manage users (farmers/customers), crops, and overall platform data.

---

## 🏗️ Tech Stack
- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap
- **Templates:** Django template engine (`base.html`, etc.)
- **Database:** SQLite (development) / any SQL database
- **Version Control:** Git & GitHub

---
##User Roles**
**Farmer**
- Register/Login
- Manage profile
- Add/update/delete crops
- View orders from customers
**Customer**
- Register/Login
- Browse crops
- Place orders
**Admin**
- Manage farmers, customers, and crops
- Oversee the platform data from admin panel
---
**Future Work**
- Expand crop dataset (more regions, soil types, and weather integration)
- Add map integration to show nearby fertilizer shops and soil testing centers
- Improve UI/UX and add local language support
- Integrate leaf disease detection using image-based ML models
- Add fertilizer recommendation based on crop and soil data
- Develop Android/iOS mobile app versions
---
**References & Inspiration**
- Government of India agriculture portals (mKisan, Kisan Suvidha, AgriStack, etc.)
- Digital farming platforms like OneSoil, Climate FieldView, CropX, Agricolus
- Research on soil-based crop recommendation using machine learning
- YouTube channels & tutorials on organic farming and modern agricultural practices
## 📂 Project Structure (High-Level)
---
Example structure (your exact folders may differ):

```text
digital-farming/
├── manage.py
├── requirements.txt
├── README.md
├── .gitignore
├── app_name/              # main Django app (rename accordingly)
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── learning_hub.html
│   │   ├── farmer_dashboard.html
│   │   ├── customer_home.html
│   │   └── ...
│   └── static/
│       ├── css/
│       ├── js/
│       └── images/
└── ... ```

