House-hunt Demo video link:

https://drive.google.com/file/d/1DUlgPD0aLXaSC-LhORPqBJC_gg6QQKmI/view?usp=drivesdk

🏡 House Hunt – Your Perfect Rental Home Finder

House Hunt is a full-stack web application designed to simplify the process of finding rental homes based on location, budget, amenities, and preferences. With a user-centric interface and powerful search/filtering features, this application enables users to browse, compare, and shortlist rental properties seamlessly.


🔍 Project Overview

Objective:
To develop a smart, responsive, and efficient platform that connects home seekers with rental listings in real-time using advanced filters and data-driven insights.

Key Features:

🔎 Advanced property search by location, budget, property type, and amenities

🗺️ Interactive map integration for spatial browsing

💬 Contact landlord or property manager directly via chat or call

📝 User authentication for managing favorites and listings

📊 Admin dashboard to manage property data and analytics

📱 Fully responsive UI for both mobile and desktop


🧑‍💻 Tech Stack

Frontend	Backend	Database	Others

React.js	Node.js	MongoDB	Express.js, Tailwind CSS
Axios	REST API	Mongoose	Map API (e.g., Leaflet.js)
React Router	JWT Auth		Git, GitHub, Postman


📁 Project Structure

HouseHunt/
│
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│
├── server/                  # Node + Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│
├── .env                     # Environment variables
├── README.md                # Project documentation
└── package.json


🚀 Installation & Setup

1. Clone the Repository

git clone https://github.com/your-username/house-hunt.git
cd house-hunt

2. Install Dependencies

Frontend

cd client
npm install

Backend

cd server
npm install

3. Configure Environment Variables

Create a .env file in the server/ directory:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

4. Run the Application

Start Backend

cd server
npm start

Start Frontend

cd client
npm start


✅ Functional Highlights

User Authentication: Register/Login using JWT-based sessions.

Dynamic Filters: Filter listings based on price range, number of rooms, availability, etc.

Favorites System: Logged-in users can save favorite listings.

Admin Panel: Manage listings, users, and analytics securely.

Responsive Design: Optimized for all screen sizes and devices.

Real-time Search: Results update dynamically without page reload.


📊 Future Enhancements

🧠 AI-powered recommendation engine based on user history

📍 Real-time geolocation-based suggestions

📅 Property visit scheduling and calendar sync

💬 Integrated chat support with landlords


🙋‍♂️ Who Can Use This Project?

Final-year CS/IT students for academic submission

Entry-level developers showcasing full-stack skills

Real-estate startups looking for a base prototype

Data Analytics integration for trend-based decisions


🧾 License

This project is licensed under the MIT License. See the LICENSE file for details.

✍️ Author

👤 Geethika Karra
📧 Email: karrageethika716@gmail.com
