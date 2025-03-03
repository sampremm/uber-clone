# 🚖 Uber Clone

A full-stack ride-booking application replicating Uber, featuring real-time location tracking, fare estimation, and driver allocation.

## 📌 Features

- **User & Driver Authentication** – Secure sign-up and login system.
- **Ride Booking System** – Users can request rides, set pickup/drop-off locations.
- **Real-time Location Tracking** – Integrated Google Maps API for live tracking.
- **Fare Estimation** – Dynamic fare calculation based on distance.
- **Driver Allocation** – Assigns nearest available driver using optimized queries.
- **Interactive UI** – Built with React.js and TailwindCSS for a smooth user experience.
- **MongoDB Database** – Efficient storage for users, trips, and driver data.

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **Node.js, Express.js** | Backend API & server logic |
| **React.js, TailwindCSS** | Frontend UI design |
| **MongoDB** | Database for user, trip & driver data |
| **Google Maps API** | Live tracking, distance calculation |
| **Socket.IO** | Real-time ride updates |

## 📂 Project Structure

```
uber-clone/
│── Backend/
│   ├── controllers/    # Business logic for routes
│   ├── db/             # Database connection
│   ├── middlewares/    # Middleware functions
│   ├── models/         # Database models (MongoDB schemas)
│   ├── routes/         # API endpoints
│   ├── services/       # External services (e.g., Google Maps, payment processing)
│   ├── app.js          # Initializes the backend server
│   ├── server.js       # Entry point for the backend server
│   ├── socket.js       # WebSockets for real-time updates
│   └── package.json    # Backend dependencies
│
│── Frontend/
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Pages for the application
│   │   ├── hooks/         # Custom React hooks
│   │   ├── utils/         # Helper functions
│   │   ├── App.js         # Main React component
│   │   └── index.js       # Entry point for frontend
│   ├── public/            # Static assets
│   ├── package.json       # Frontend dependencies
│   └── tailwind.config.js # TailwindCSS configuration
│
└── README.md              # Project documentation
```

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/sampremm/uber-clone.git
cd uber-clone
```

### 2️⃣ Install Dependencies
#### Backend
```sh
cd Backend
npm install
```
#### Frontend
```sh
cd ../Frontend
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the Backend and add:
```
MONGO_URI=your_mongodb_uri
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
JWT_SECRET=your_jwt_secret
```

### 4️⃣ Start the Application
#### Backend
```sh
cd Backend
npm run server
```
#### Frontend
```sh
cd ../Frontend
npm start
```

## 📜 License
This project is licensed under the MIT License.

## 📞 Contact
**Sam Prem Kumar Thalla**  
🔗 GitHub: [sampremm](https://github.com/sampremm)  
