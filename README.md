# 🛒 Shopping Cart Web App

A full-stack **Shopping Cart** web application built using **React.js** for the frontend and **Golang (Gin)** for the backend. It allows users to view products, add/remove them from the cart, and checkout securely.

---

## 🔧 Tech Stack

### Frontend

* React.js (with Vite or Create React App)
* Axios (for API calls)
* React Router (for routing)
* Tailwind CSS / CSS Modules (for styling)

### Backend

* Golang with Gin framework
* GORM for ORM
* PostgreSQL / SQLite (based on your DB)
* JWT for authentication
* Ginkgo (testing)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ShivamGupta-16/shopping-cart.git
cd shopping-cart
```

---

### 2. Start Backend (Go)

```bash
cd server
go mod tidy
go run main.go
```

This starts the backend API at `http://localhost:5000`.

---

### 3. Start Frontend (React)

```bash
cd client
npm install
npm start
```

This starts the React app at `http://localhost:3000`.

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint        | Description              |
| ------ | --------------- | ------------------------ |
| GET    | `/api/products` | Get all products         |
| POST   | `/api/cart`     | Add product to cart      |
| DELETE | `/api/cart/:id` | Remove product from cart |

---

## ✅ Features

* User-friendly product catalog
* Add to cart & quantity management
* RESTful API backend
* JWT-based user authentication
* Responsive UI
* Clean folder structure

---

## 🔪 Testing

```bash
go test ./...    # For backend tests
npm test         # For frontend tests
```

---

## 📦 Deployment

You can deploy:

* Frontend on **Vercel** or **Netlify**
* Backend on **Render**, **Railway**, or **Heroku**

---

## 🙌 Credits

Built by Shivam GUpta using modern web technologies to demonstrate a full-stack application.

---

## 📜 License

This project is licensed under the MIT License.
