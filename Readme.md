# Forever - E-commerce Project ✨🛍️🚀

Welcome to **Forever**, a full-featured e-commerce platform designed to provide a seamless shopping experience. This repository contains the source code for the frontend, admin panel, and backend server. 🎯🔧💻

## Live Demo 🌍🔗🛒

- **Frontend:** [https://e-commerce-frontend-omega-fawn.vercel.app/](https://e-commerce-frontend-omega-fawn.vercel.app/)
- **Admin Panel:** [https://e-commerce-admin-panel-brown.vercel.app/](https://e-commerce-admin-panel-brown.vercel.app/)

## Project Overview 🏗️📦🛠️

**Forever** is built to offer:

- A user-friendly shopping interface for browsing and purchasing products.
- An intuitive admin dashboard to manage products, orders, and users.
- A robust backend server for handling business logic, authentication, and database operations.

## Tech Stack 🏗️💻📜

- **Frontend:** React, Vite, Tailwind CSS (or your chosen styling framework)
- **Admin Panel:** React, Vite, [Admin UI library of your choice]
- **Backend:** Node.js, Express, MongoDB
- **Payment Integration:** Razorpay, Stripe (if applicable)
- **Deployment:** Vercel (for frontend and admin), [Your choice for backend hosting]

## Features 🎯🛒⚙️

- **User Registration & Authentication:** Secure user login and registration.
- **Product Catalog:** Browse, search, and filter through a variety of products.
- **Shopping Cart:** Add, remove, and update products in your cart.
- **Order Management:** Place orders and track order status.
- **Admin Dashboard:** Manage products, categories, orders, and users.
- **Payment Gateway Integration:** Seamless payment processing with Razorpay and Stripe.
- **Responsive Design:** Fully responsive UI that works across devices.

## Getting Started 🏁💡🛠️

Follow these instructions to set up and run the project locally.

### Prerequisites 🔧🖥️📂

- [Node.js](https://nodejs.org/en/download/) (v14 or later)
- [npm](https://www.npmjs.com/get-npm) (comes with Node.js)
- A MongoDB instance (local or hosted, e.g., MongoDB Atlas)
- Razorpay API keys and Stripe API keys

### Clone the Repository 📥💾🔗

```bash
git clone https://github.com/Krishna200608/E-commerce-App.git
cd E-commerce-App
```

### Installation 🏗️📦💡

Each part of the project (frontend, admin, backend) has its own dependencies. Follow the steps below:

1. **Frontend:**

   ```bash
   cd frontend
   npm install
   ```

2. **Admin Panel:**

   Open a new terminal, then run:

   ```bash
   cd admin
   npm install
   ```

3. **Backend:**

   In another terminal, run:

   ```bash
   cd backend
   npm install
   ```

### Environment Variables 🌍🔑📝

Create a `.env` file in each respective folder (frontend, admin, backend) as needed. For example, in the **backend** folder, your `.env` file might include:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
RAZORPAY_KEY=your_razorpay_key
RAZORPAY_SECRET=your_razorpay_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

Make sure to replace placeholder values with your actual credentials. 🔒📜✅

### Running the Project Locally 🏃💻🛠️

1. **Frontend:**

   ```bash
   cd frontend
   npm run dev
   ```

2. **Admin Panel:**

   ```bash
   cd admin
   npm run dev
   ```

3. **Backend:**

   ```bash
   cd backend
   npm run server
   ```

The frontend and admin panels should now be running on their respective local ports (usually `http://localhost:3000` for Vite projects), and your backend will be available as specified in your configuration. 🌐🚀⚙️

## Deployment 🚀📤🌍

For deployment:

- **Frontend & Admin:** Deployed on Vercel. The root directories are set accordingly in your Vercel project settings.
- **Backend:** Deploy on your preferred hosting platform (e.g., Heroku, DigitalOcean, AWS).

Ensure that your environment variables are correctly set on the hosting platform as well. ✅📡🔧

## Contributing 🤝💡📌

Contributions are welcome! If you’d like to contribute:

1. Fork this repository.
2. Create a feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a pull request.

## License 📜🔓✅

This project is open source and available under the [IIITA License](LICENSE). 📃⚖️💡

## Contact 📧📞📌

For any questions or suggestions, please open an issue or contact [krishnasikheriya001.com](mailto:your-email@example.com). 💬📬🤝

