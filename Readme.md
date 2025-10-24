# Forever — E-COMMERCE-APP ✨🛍️🚀

*Transforming Shopping Into Seamless, Scalable Experiences*

[![Last Commit](https://img.shields.io/github/last-commit/Krishna200608/E-commerce-App?style=for-the-badge\&logo=git)](https://github.com/Krishna200608/E-commerce-App/commits/main)
[![Top Language](https://img.shields.io/github/languages/top/Krishna200608/E-commerce-App?style=for-the-badge)](https://github.com/Krishna200608/E-commerce-App)
[![Languages Count](https://img.shields.io/github/languages/count/Krishna200608/E-commerce-App?style=for-the-badge)](https://github.com/Krishna200608/E-commerce-App)
[![License](https://img.shields.io/badge/License-IIITA-blue?style=for-the-badge)](LICENSE)

---

## Live Demo 🌍🔗🛒

* **Frontend:** [https://e-commerce-frontend-omega-fawn.vercel.app/](https://e-commerce-frontend-omega-fawn.vercel.app/)
* **Admin Panel:** [https://e-commerce-admin-panel-brown.vercel.app/](https://e-commerce-admin-panel-brown.vercel.app/)

---

## Project Overview 🏗️📦🛠️

**Forever** is a full-featured e-commerce platform that includes a modern storefront, an admin dashboard, and a robust backend. It’s designed for real-world e-commerce needs: product management, secure authentication, payments, order tracking, and responsive design.

---

## Built with the tools and technologies

![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge\&logo=express\&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=node.js\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646cff?style=for-the-badge\&logo=vite\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge\&logo=mongodb\&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-D84B3B?style=for-the-badge\&logo=mongodb\&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge\&logo=tailwind-css\&logoColor=white)
![Nodemon](https://img.shields.io/badge/Nodemon-76D04B?style=for-the-badge\&logo=nodemon\&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge\&logo=npm\&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge\&logo=axios\&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge\&logo=stripe\&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-002F6C?style=for-the-badge\&logo=razorpay\&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-172554?style=for-the-badge\&logo=cloudinary\&logoColor=white)
![dotenv](https://img.shields.io/badge/.env-000000?style=for-the-badge\&logo=dotenv\&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge\&logo=eslint\&logoColor=white)

---

## Features 🎯🛒⚙️

* **User Registration & Authentication** (JWT)
* **Product Catalog** — listing, search, filter, categories
* **Product Detail Pages** — images, descriptions, reviews
* **Shopping Cart** — add/remove/update items, persistent cart
* **Checkout & Orders** — place orders, view order history
* **Payment Integration** — Razorpay & Stripe (configurable)
* **Admin Dashboard** — manage products, categories, users, orders
* **Image Uploads** — Cloudinary integration
* **Server-side Validation & Error Handling**
* **Responsive Design** — mobile + desktop ready
* **Environment-based configuration** (`.env`)
* **Development Experience** — Nodemon, ESLint, Vite for fast dev

---

## Tech Stack (summary) 🧰

* **Frontend**: React + Vite (+ Tailwind CSS or your chosen framework)
* **Admin Panel**: React + Vite (admin UI of your choice)
* **Backend**: Node.js + Express + MongoDB (Mongoose)
* **Payments**: Razorpay, Stripe
* **Image Storage**: Cloudinary
* **Deployment**: Vercel (frontend & admin), Vercel or other host for backend

---

## Getting Started — Local Setup 🏁💡🛠️

### Prerequisites 🔧

* Node.js v14+
* npm (or pnpm/yarn)
* MongoDB (local or Atlas)
* Razorpay & Stripe API keys (if using payments)
* Cloudinary account (for image uploads)

### Clone the repository

```bash
git clone https://github.com/Krishna200608/E-commerce-App.git
cd E-commerce-App
```

### Install dependencies (each package separately)

1. Frontend

```bash
cd frontend
npm install
```

2. Admin

```bash
cd ../admin
npm install
```

3. Backend

```bash
cd ../backend
npm install
```

---

## Environment Variables 🌍🔑📝

Create `.env` files in the folders that need them.

**Backend `.env`**

```env
MONGODB_URI="Your_MongoDB_Url"
CLOUDINARY_API_KEY="Your_Key"
CLOUDINARY_SECRET_KEY="Your_Secret_key"
CLOUDINARY_NAME="Your_cloudinary_name"
JWT_SECRET="Any_random_string"
ADMIN_EMAIL="your_admin_email"
ADMIN_PASSWORD="your_admin_password"
STRIPE_SECRET_KEY="Your_Stripe_secret_key"
RAZORPAY_KEY_ID="Your_Razorpay_id"
RAZORPAY_KEY_SECRET="Your_Razorpay_secret"
PORT=4000
```

**Frontend `.env`**

```env
VITE_BACKEND_URL=http://localhost:4000
VITE_RAZORPAY_KEY_ID="Your_Razorpay_key_id"
```

**Admin `.env`**

```env
VITE_BACKEND_URL=http://localhost:4000
```

> Replace placeholders with real credentials. Keep `.env` out of version control.

---

## Run Locally 🏃‍♂️

Open separate terminals for each part:

**Frontend**

```bash
cd frontend
npm run dev
```

**Admin**

```bash
cd admin
npm run dev
```

**Backend**

```bash
cd backend
npm run server
# or: npm run dev (if you use nodemon)
```

Default Vite ports are usually `5173` (frontend) and `5174` (admin); backend commonly runs on `4000`.

---

## Deployment 🚀📤

* Frontend & Admin: Deploy to Vercel — point each project to its subfolder and set environment variables in Vercel.
* Backend: Deploy to Vercel (serverless) or any Node host (Render, Heroku, Railway). Ensure environment variables are set on the host.

---

## Contributing 🤝

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "Add feature"`
4. Push: `git push origin feature/your-feature`
5. Open a PR

Please follow code style and open issues for large changes.

---

## License 📜

This project is available under the **IIITA License**. See the `LICENSE` file for details.

---

## Contact 📧

Have questions or suggestions? Open an issue or contact me:
**[krishnasikheriya001@gmail.com](mailto:krishnasikheriya001@gmail.com)**
