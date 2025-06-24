<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=header"/>
</p>

# 🏡 Dream Dwelling

Dream Dwelling is a full-stack web application for booking and listing vacation rentals, similar to Airbnb. Users can register, log in, create property listings, book stays, manage wish lists, and more.

## ✨ Features

- 🔐 User registration & login (with profile photo uploads)
- 🔍 Browse/search listings by **category, type**, or **keyword**
- 🏘️ Create, edit & manage your own **property listings** (with images)
- 📅 Book stays with **date selection** and **auto price calculation**
- 🧳 View your **trip history** and **reservation records**
- 💖 Add/remove properties from your **wish list**
- 💻 Fully responsive **UI using React + SCSS**

## 🧰 Tech Stack

### 🔧 Frontend  
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white" />
  <img src="https://img.shields.io/badge/ReduxPersist-purple?style=flat" />
  <img src="https://img.shields.io/badge/ReactRouter-DD0031?style=flat&logo=react-router&logoColor=white" />
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white" />
  <img src="https://img.shields.io/badge/Material UI-007FFF?style=flat&logo=mui&logoColor=white" />
  <img src="https://img.shields.io/badge/ReactIcons-lightblue?style=flat" />
</p>

### ⚙️ Backend  
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Mongoose-880000?style=flat" />
  <img src="https://img.shields.io/badge/Multer-FFCA28?style=flat" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white" />
</p>

### 🔄 Others  
<p>
  <img src="https://img.shields.io/badge/dotenv-ECD53F?style=flat&logo=dotenv&logoColor=black" />
  <img src="https://img.shields.io/badge/CORS-003366?style=flat" />
</p>


## 🚀 Getting Started

### ✅ Prerequisites

- Node.js and npm installed
- MongoDB running locally (or update `.env` for remote DB)

### 📦 Installation

#### 1. Clone the repository

```sh
git clone <your-repo-url>
cd Dream-Dwelling
```

#### 2. Install server dependencies

```sh
cd server
npm install
```

#### 3. Install client dependencies

```sh
cd ../client
npm install
```

### 🔐 Environment Variables

Create a `.env` file in the `server/` directory:

```
MONGO_URL='mongodb://localhost:27017'
JWT_SECRET='YOUR_SECRET_KEY'
```

### ▶️ Running the App

#### 1. Start the backend server

```sh
cd server
npm start
```

The backend will run on [http://localhost:3001](http://localhost:3001).

#### 2. Start the frontend

```sh
cd ../client
npm start
```

The frontend will run on [http://localhost:3000](http://localhost:3000).

### 📱 Usage

- Register a new account and log in.
- Browse listings, search, or filter by category.
- Create your own property listings as a host.
- Book properties and manage your trips and reservations.
- Add properties to your wish list for later.

### 🧩 Folder Structure

- `client/` - React frontend
- `server/` - Express backend
- `server/models/` - Mongoose models for User, Listing, Booking
- `server/routes/` - Express route handlers

## 👥 Contributors

<!-- Example Contributor -->
<a href="https://github.com/dhrumil1508">
  <img src="https://avatars.githubusercontent.com/dhrumil1508" width="100px;" alt="dhrumil1508"/>
  <br />

### 📄 License

Licensed under the MIT license.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</p>
