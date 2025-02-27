# Wardrobe Management System

This is a full-stack application developed using **Laravel** for the backend and **Vue.js** for the frontend. The Wardrobe Management System allows users to manage their clothing items, categorize them, and maintain an organized digital wardrobe.

---

## 🚀 Features
- **User Authentication:** Secure login and registration system.
- **CRUD Operations:** Add, edit, delete, and view clothing items.
- **Categorization:** Organize items by category (e.g., Tops, Bottoms, Shoes).
- **Search & Filter:** Easily find items through search and filter functionality.
- **Responsive UI:** Mobile-friendly and easy-to-use interface.

---

## 🛠️ Tech Stack
**Frontend:** Vue.js, Tailwind CSS

**Backend:** Laravel, MySQL

**API Communication:** Axios

---

## 📂 Project Setup

### 1. Clone the repository
```sh
git clone https://github.com/yourusername/wardrobe-management.git
cd wardrobe-management
```

### 2. Backend Setup (Laravel)
```sh
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### 3. Frontend Setup (Vue.js)
```sh
cd frontend
npm install
npm run dev
```

### 4. Access the Application
- **Backend:** http://127.0.0.1:8000
- **Frontend:** http://localhost:5173

---

## 🤖 API Endpoints
- `GET /api/products` - Fetch all products
- `POST /api/products` - Add a new product
- `GET /api/products/{id}` - View a specific product
- `PUT /api/products/{id}` - Update a product
- `DELETE /api/products/{id}` - Delete a product

---

## 📸 Screenshots
(Include screenshots of the app to give a visual preview)

---

## 📝 License
This project is licensed under the MIT License.
