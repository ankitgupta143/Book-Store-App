# 📚 Bookstore App (MERN Stack)

Welcome to the **Bookstore App**, a comprehensive MERN stack application that allows users to browse and purchase books with ease, while providing admins with a robust dashboard to manage inventory effectively.

---

## 📜 Features

### User Features
- **Browse Books**: Search and view a wide range of books.
- **Add to Cart**: Add desired books to the shopping cart.
- **Checkout**: Proceed with a seamless checkout experience using the cash-on-delivery system.
- **Order Management**: Keep track of placed orders.

### Admin Features
- **Admin Dashboard**: Secure dashboard accessible with a username and password.
- **Manage Books**: Upload new books, update existing book details, and delete books.
- **Inventory Management**: Ensure smooth operations with an efficient inventory system.

---

## 🛠️ Technologies Used

- **Frontend**: React.js, Tailwind CSS, Redux, RTK Query Toolkit
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: Redux Toolkit
- **Database Management**: Mongoose

---

## 📂 Project Structure

```plaintext
Book-Store-App/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── config/
│   └── package.json
│
├── README.md
└── .env

# 🚀 Getting Started

Follow these steps to set up and run the project locally.

---

## Prerequisites
- Node.js installed on your system.
- MongoDB set up locally or via a cloud provider.
- Firebase setup for the frontend environment.

---

## ⚙️ Frontend Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ankitgupta143/Book-Store-App.git
   cd Book-Store-App
Navigate to the frontend directory:

bash
Copy code
cd frontend
Configure Environment Variables:

Create a .env.local file at the root of the frontend directory.

Add the following Firebase credentials:

env
Copy code
VITE_API_KEY="AIzaSyCXvDIC4MPrkaMdeg_O2iij88wLpfj3qBA"
VITE_AUTH_DOMAIN="book-store-mern-app.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app"
VITE_STORAGE_BUCKET="book-store-mern-app.appspot.com"
VITE_MESSAGING_SENDERID="205632822247"
VITE_APPID="1:205632822247:web:b0db0ec66bf6de0bbb3b42"
Install dependencies:

bash
Copy code
npm install
Run the project:

bash
Copy code
npm run dev
The frontend will start running at http://localhost:3000.

⚙️ Backend Setup
Navigate to the backend directory:

bash
Copy code
cd backend
Configure Environment Variables:

Create a .env file at the root of the backend directory.

Add the following variables:

env
Copy code
DB_URL="mongodb+srv://helpyourassistant:pqam0Mwv3Vwv8Off@cluster0.qc3bq.mongodb.net/book-store?retryWrites=true&w=majority&appName=Cluster0"
JWT_SECRET_KEY='bc992a20cb6706f741433686be814e3df45e57ea1c2fc85f9dbb0ef7df12308a669bfa7c976368ff32e32f6541480ce9ec1b122242f9b1257ab669026aeaf16'
Ensure you replace the MongoDB connection string and JWT secret key with your own.

Install dependencies:

bash
Copy code
npm install
Run the backend server:

bash
Copy code
npm run start:dev
The backend server will start running at http://localhost:8000.

🌟 Key Functionalities
User Flow
Homepage: Browse a catalog of books.
Cart: Add or remove books.
Checkout: Confirm your order with the cash-on-delivery option.
Admin Flow
Login: Access the admin dashboard securely.
Manage Inventory: Add, update, or delete books as required.

🤝 Contributing
We welcome contributions! To contribute:

Fork the repository.
Create a new branch.
Make your changes.
Submit a pull request.

🐛 Known Issues & Troubleshooting
Common Errors
DB_URL Error: Ensure MongoDB is properly configured and the connection string is correct.
Frontend Not Loading: Verify that .env.local contains the correct Firebase credentials.

📜 License
This project is licensed under the MIT License.

📬 Contact
Author: Ankit Gupta
GitHub: ankitgupta143
Project Repository: Bookstore App

This code can be directly copied into your `README.md` file for a professional and well-structured 
