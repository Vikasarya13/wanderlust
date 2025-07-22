# 🏡 Wanderlust – Property Listing Website

A full-stack MERN (MongoDB, Express, React, Node.js) application designed for discovering, listing, and managing travel destinations or rental properties. Wanderlust empowers users to explore places, post listings, leave reviews, and manage their own travel experiences with ease.



---

## 📌 Project Overview

Wanderlust is a travel/property listing web application where users can register, create new listings, upload images, add reviews, and search for locations with integrated maps. It provides a seamless user experience with role-based access and form validation.

---

## ✨ Features

- 🔐 **User Authentication** using Passport.js (Register, Login, Logout)
- 🏠 **Create/Edit/Delete Listings**
- 📸 **Image Uploads with Cloudinary**
- 🗺️ **Geolocation using Mapbox API**
- 💬 **Add & Delete Reviews on Listings**
- ⚠️ **Robust Validation** using Joi (server-side)
- 🧑‍💻 **Authorization Middleware** for secure route access
- ✨ **Flash Messages** for interactive user feedback
- 📱 **Responsive UI** with Bootstrap 5 and EJS Templates

---
## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap 5, EJS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: Passport.js (Local Strategy)
- **Image Storage**: Cloudinary
- **Validation**: Joi
- **Templating Engine**: EJS

---
## 🎥 Demo

🎬 *[Add your demo video link or GIF here]*

---

## 👨‍💻 Developer

**Vikas Arya**  
📧 Email: [vikasarya7068@gmail.com](mailto:vikasarya7068@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/vikas-arya-263a99269](https://linkedin.com/in/vikas-arya-263a99269)

---
## 📁 Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/Vikasarya13/wanderlust.git
cd wanderlust
npm install
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET=your_cloudinary_secret
MAPBOX_TOKEN=your_mapbox_token
DB_URL=mongodb://localhost:27017/wanderlust
SECRET=your_session_secret
npm start
Open http://localhost:3000 in your browser to use

---
