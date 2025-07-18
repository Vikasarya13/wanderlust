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

## 🎥 Demo

🎬 *[Add your demo video link or GIF here]*

---

## 🗂️ Contents

- [`Backend Setup`](#🛠️-backend-setup)
- [`Folder Structure`](#📁-folder-structure)
- [`Usage`](#🚀-usage)
- [`Tech Stack`](#🧰-tech-stack)
- [`Future Improvements`](#🧠-future-improvements)

---

## 🛠️ Backend Setup

```bash
# Clone the repository
git clone https://github.com/Vikasarya13/wanderlust.git
cd wanderlust

# Install server dependencies
npm install

# Create a .env file in the root directory and add the following:
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_api_key
CLOUDINARY_SECRET=your_api_secret
MAPBOX_TOKEN=your_mapbox_token
DB_URL=your_mongo_connection_string
SECRET=your_session_secret

# Run the development server
npm start

