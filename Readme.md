# 🏡 Airbnb Clone

A full-stack Airbnb-inspired web application that allows users to explore, create, edit, and review property listings. The application includes secure user authentication, image uploads using Cloudinary, session management, and a responsive UI built with EJS templates.

---

## 🚀 Features

- 🔐 User Authentication (Sign Up / Login / Logout)
- 🏠 Create, Read, Update & Delete (CRUD) Listings
- 📸 Upload listing images using Cloudinary
- ⭐ Add and manage reviews for listings
- 👤 Authorization (Only owners can edit/delete their listings)
- 💬 Flash messages for user feedback
- 🔒 Session-based authentication using Passport.js
- 📱 Responsive UI

---

## 🛠️ Tech Stack

### Frontend
- EJS
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- Passport.js
- Passport Local
- Express Session

### Image Storage
- Cloudinary
- Multer
- Multer Storage Cloudinary

### Validation
- Joi

---

## 📂 Project Structure

```
AIRBNB/
│── controllers/
│── middleware.js
│── models/
│── public/
│── routes/
│── uploads/
│── utils/
│── views/
│── app.js
│── cloudConfig.js
│── schema.js
│── package.json
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/airbnb-clone.git
```

### 2. Navigate into the project

```bash
cd airbnb-clone
```

### 3. Install dependencies

```bash
npm install
```

### 4. Create a `.env` file

Add the following environment variables:

```env
ATLASDB_URL=your_mongodb_connection_string

SECRET=your_session_secret

CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
```

### 5. Start the server

```bash
node app.js
```

or (with Nodemon)

```bash
nodemon app.js
```

The application will run on:

```
http://localhost:8080
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Listing Details
- Create Listing
- Login Page
- Review Section

---

## 📦 Dependencies

- Express.js
- MongoDB & Mongoose
- Passport.js
- Express Session
- Cloudinary
- Multer
- Joi
- EJS
- Connect Flash

---

## 🔮 Future Improvements

- ❤️ Wishlist/Favorites
- 🔍 Search & Filters
- 📍 Interactive Maps
- 💳 Booking & Payments
- 📅 Availability Calendar
- 📧 Email Notifications
- 🌙 Dark Mode

---

## 👨‍💻 Author

**Omkar Katare**

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile

---

## 📄 License

This project is developed for learning purposes and is open for educational use.