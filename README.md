# 🛒 FreshCart

FreshCart is a modern **MERN Stack** grocery store application built with **Vite**, **React**, **Express**, **MongoDB**, and **Tailwind CSS**.  
It includes a powerful **Admin Panel** for managing products, categories, orders, and users — making it easy for store owners to keep their business running smoothly.

## 🚀 Features

### 🛍 Customer Side
- Browse and search for grocery products.
- Add products to cart and checkout.
- Responsive UI for mobile and desktop.
- User authentication & profile management.

### 🛠 Admin Panel
- Secure admin login.
- Add, edit, and delete products.
- Manage product categories.
- View and manage customer orders.
- Track inventory.

## 🏗 Tech Stack

**Frontend**
- [Vite](https://vitejs.dev/) — Lightning-fast frontend build tool.
- [React](https://react.dev/) — Component-based UI.
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework.

**Backend**
- [Node.js](https://nodejs.org/) — JavaScript runtime.
- [Express.js](https://expressjs.com/) — Backend framework.
- [MongoDB](https://www.mongodb.com/) — NoSQL database.

**Other**
- JWT Authentication
- REST API architecture
- Cloud image storage (optional, e.g., Cloudinary)

## 📸 Screenshots

### 🏠 Home Page
![Home Page](./screenshots/home.png)

### 🛠 Admin Dashboard
![Admin Dashboard](./screenshots/admin.png)

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/freshcart.git
cd freshcart
````

### 2️⃣ Install dependencies

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd backend
npm install
```

### 3️⃣ Environment variables

Create `.env` files in both `frontend` and `backend` directories.

#### Backend `.env` example

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

#### Frontend `.env` example

```
VITE_API_URL=http://localhost:5000
```

### 4️⃣ Run the app

#### Backend

```bash
cd backend
npm run dev
```

#### Frontend

```bash
cd frontend
npm run dev
```

## 📜 API Endpoints

| Method | Endpoint           | Description              |
| ------ | ------------------ | ------------------------ |
| POST   | /api/auth/register | Register a new user      |
| POST   | /api/auth/login    | Login user               |
| GET    | /api/products      | Get all products         |
| POST   | /api/products      | Add product (Admin only) |
| PUT    | /api/products/\:id | Update product           |
| DELETE | /api/products/\:id | Delete product           |

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License.


### 💡 Author

Developed by **Akshat Choukse**
📧 [your-choukseakshat.com](mailto:choukseakshat@example.com)
🌐 [akshat-protfolio.vercel.app](https://akshat-protfolio.vercel.app/)

