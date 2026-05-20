# Image Uploader

A full-stack Image Uploader web application built using the MERN stack (MongoDB, Express, React, Node.js) that allows users to upload images to the cloud via Cloudinary, store metadata in MongoDB, and view uploaded images in a responsive gallery.

---

## 🚀 Features

- Upload images from the local device
- Store images in Cloudinary (cloud storage)
- Save image metadata (URL, public_id, upload time) in MongoDB
- Display uploaded images in a dynamic gallery
- Drag-and-drop or file picker interface
- Responsive design for desktop and mobile

---

## 🛠️ Tech Stack

### Frontend
- React
- Axios
- Bootstrap / Tailwind CSS
- Custom CSS

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- Cloudinary SDK
- Multer

---

## 📌 API Overview

### POST `/api/upload`
Upload an image to Cloudinary.

Returns:
- Image URL
- Metadata

### GET `/api/images`
Fetch all uploaded image data from MongoDB.

---

## ⚙️ How It Works

1. User selects or drags an image into the uploader UI.
2. Image is sent to the backend using Axios.
3. Backend uploads image to Cloudinary and stores metadata in MongoDB.
4. Frontend fetches and displays uploaded images in a gallery.

---

## 🔮 Future Improvements

- Add user authentication
- Support multiple image uploads
- Image compression before upload
- Delete images from Cloudinary + MongoDB
- Pagination / Infinite scroll for gallery

---

## 📷 Project Setup

### Clone Repository

```bash
git clone https://github.com/0xSouravXBT/Image_Uploader.git
```

### Install Dependencies

```bash
npm install
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
npm run dev
```

---

## 👨‍💻 Author

Sourav Shaw

GitHub: https://github.com/0xSouravXBT
