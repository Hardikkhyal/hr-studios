# HR STUDIOS - Discover Your Sound 🎵

A premium, responsive, and modern E-Commerce Web Application built with Django, customized for musical instrument sales. Featuring a modern dark glassmorphism user interface with responsive layout grids, smooth hover animations, and intuitive cart management.

---

## ✨ Features

- 🎹 **Modern Dark Aesthetic:** Sleek and visual interface using deep dark hues, vibrant amber/orange gradients, and premium glassmorphic overlays.
- 📱 **Fully Responsive Layout:** Crafted with modern CSS Flexbox and Grid to look stunning on desktops, tablets, and mobile devices.
- 🛍️ **Interactive Product Showcase:** Browse featured categories (Violin, Drums, Keyboard, Saxophone, Guitar) with zoom hover animations and direct quick-view navigation.
- 🛒 **Dynamic Cart & Checkout:** Seamlessly add items, adjust quantities, view popover cart summaries, and checkout.
- 🔒 **User Authentication:** Fully styled SignUp, Login, and Password Reset modals.
- 📈 **Order Tracker:** Track the status of orders in real-time.
- 💬 **Musician Testimonials & Newsletter:** Engaging reviews and newsletter subscription forms.

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML5, CSS3, Javascript, Bootstrap 4, AOS (Animate on Scroll)
- **Database:** SQLite3

---

## 🚀 Installation & Setup

### Prerequisites
Make sure you have Python installed on your system.

### 1. Clone the repository
```bash
git clone <your-repository-link>
cd "hr studios"
```

### 2. Set up Virtual Environment
Create and activate a virtual environment to manage dependencies:
```bash
# Create venv
python -m venv venv

# Activate venv (Windows PowerShell)
.\venv\Scripts\Activate.ps1

# Activate venv (Windows CMD)
.\venv\Scripts\activate.bat
```

### 3. Install Requirements
```bash
pip install -r requirements.txt
```

### 4. Database Migrations
Create and apply database migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Start the Server
Run the local development server:
```bash
python manage.py runserver
```
Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) (or the designated port) in your web browser.
---

## 📄 License
This project is created for diploma evaluation. All rights reserved.
