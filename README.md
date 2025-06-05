# 🌍 Wanderlust

A full-stack hotel booking website inspired by Airbnb. Wanderlust offers user authentication, image uploads, interactive maps, and dynamic listings—all built with modern web technologies.

> 🚧 **Note**: Booking functionality is under development.

---

## ✨ Features

- 🔐 User Authentication & Authorization (Passport.js)
- 📍 Interactive Maps using Mapbox
- ☁️ Cloud-based Image Uploads with Cloudinary
- 🖼️ Dynamic Templating with EJS & EJS-Mate
- 📦 Full CRUD operations for hotel listings
- 🧭 Session management and flash messaging
- 🎨 Styled with Bootstrap & custom CSS

---

## 🛠 Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS, Bootstrap, JavaScript
- **Database**: MongoDB with Mongoose
- **Authentication**: Passport.js (Local Strategy)
- **File Uploads**: Multer + Cloudinary
- **Maps**: Mapbox SDK

---

## 📦 NPM Packages Used

```json
{
  "@mapbox/mapbox-sdk": "^0.16.1",
  "cloudinary": "^1.41.3",
  "connect-flash": "^0.1.1",
  "dotenv": "^16.5.0",
  "ejs": "^3.1.10",
  "ejs-mate": "^4.0.0",
  "express": "^5.1.0",
  "express-flash": "^0.0.2",
  "express-session": "^1.18.1",
  "method-override": "^3.0.0",
  "mongoose": "^8.14.1",
  "multer": "^2.0.1",
  "multer-storage-cloudinary": "^4.0.0",
  "passport": "^0.7.0",
  "passport-local": "^1.0.0",
  "passport-local-mongoose": "^8.0.0"
}
