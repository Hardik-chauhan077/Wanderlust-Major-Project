# 🌍 Wanderlust - Major Project

Wanderlust is a full-stack travel accommodation web application inspired by Airbnb. It allows users to explore, book, and review listings while offering hosts the ability to list their own properties. This project was developed using the **MERN stack (MongoDB, Express, React, Node.js)** with **EJS** as the templating engine.

---

## 🚀 Features

- 🏠 Create, Read, Update, Delete (CRUD) Listings
- 🔐 User Authentication (Login, Register)
- 📸 Image Upload via Cloudinary
- 📍 Geocoding & Map Integration via Mapbox
- ✍️ Reviews & Ratings
- 💡 Flash Messages & Error Handling
- ⚙️ Responsive UI with EJS & Bootstrap

---

## 🛠️ Tech Stack

| Frontend | Backend | Database | Cloud |
|----------|---------|----------|-------|
| HTML, CSS, Bootstrap, EJS | Node.js, Express.js | MongoDB (Atlas) | Cloudinary (Images), Mapbox (Maps) |

---

## 📦 Installation

# 1. Clone the repository
     ``bash
    git clone https://github.com/Hardik-chauhan077/Wanderlust-Major-Project.git
    cd Wanderlust-Major-Project

# 2. Create the .env file with environment variables
      ``bash
     echo "ATLASDB_URL=your_mongoDB_connection_string
    CLOUD_NAME=your_cloudinary_name
    CLOUD_API_KEY=your_cloudinary_api_key
    CLOUD_API_SECRET=your_cloudinary_api_secret
    MAPBOX_TOKEN=your_mapbox_token" > .env

# 3. Install dependencies
    ``bash     
    npm install

# 4. Run the app
     `` bash
    nodemon app.js

# 5. Open the App in Your Browser
    ``bash
    http://localhost:3000

---

##  📁 Project Structure
    ``bash
    Wanderlust-Major-Project/
    │
    ├── models/           # Mongoose Models
    ├── routes/           # Express Routes
    ├── public/           # Static Files (CSS, JS, Images)
    ├── views/            # EJS Templates
    ├── utils/            # Utility Functions
    ├── middleware/       # Custom Middleware
    ├── app.js            # Entry Point
    └── .env              # Environment Variables

---

#  🌐 Demo

  🔗 https://wanderlust-major-project-44yy.onrender.com/listings

  ---

#  🧠 Future Enhancements

💬 Real-time chat between users and hosts

 🗺️ Interactive filters and search

📲 Progressive Web App (PWA) support

🧾 Booking & payment system

---

#🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

# 🙋‍♂️ Author

Hardik Chauhan
GitHub    
