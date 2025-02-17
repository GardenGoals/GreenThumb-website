# GreenThumb-website
GreenThumb website
This `README.md` file follows a structured format and includes sections for installation, usage, and deployment, making it easier for developers to set up and work with this project.

🌱 GreenThumb API 
Welcome to the GreenThumb API! This API powers a user-friendly platform designed to help people create more enjoyable and productive green spaces in their environments. From managing plant details and gardening tips to tracking weather conditions and connecting with fellow gardening enthusiasts, GreenThumb provides everything you need to make your gardening journey a success!

🌟 Features
1. Manage plants with detailed information like sunlight, watering, and soil requirements.
2. Keep track of user gardens and their activities.
3. Log gardening activities like planting, watering, or harvesting.
4. Access gardening tips and schedules for a productive garden.
5. Engage in community forums to share knowledge and experiences.
6. Get weather insights to make better gardening decisions.

📄 Table of Contents
- [Getting-Started]
- [Prerequisites]
- [API-Endpoints]
- [Environment-Variables]
- [Testing]
- [Deployment]
- [Contributing]
- [License]

---

### 🚀 Getting-Started 

This Node.js API provides a backend solution for managing gardens, plants, weather, and user activities related to gardening. Follow the guide below to set up, run, and deploy the API.

### 📖 Prerequisites
Before you begin, make sure you have the following installed:
- **Node.js** v22.0 or higher
- **npm** v6.0 or higher
- **Database**: MySQL


### 📚 API-Endpoints
Here’s a quick look at the main API routes:

1. User Route
POST /users/user/login: Logs in a user.
POST /users/user/register: Registers a new user.

2. Plant Route
GET /plants/plant: Retrieve all plants.
GET /plants/plant/:plant_id: Retrieve a specific plant by ID.

3. Garden Route
POST /gardens/garden: Add a new garden.
GET /gardens/garden/:garden_id: Retrieve garden details.

4. Tip Route
POST /tips/tip: Add a gardening tip.
GET /tips/tip/:tip_id: Get a specific gardening tip.

5. Community Forum Route
GET /communityforums/communityforum: Get all community forum posts.
POST /communityforums/communityforum: Add a new community forum post.

(Refer to the full documentation for more endpoints!)

### 🌱 Environment-Variables
Create a .env file in the root directory and include the following:

Variable:      Description:                Example:
PORT	      Port the server runs on      3001
DB_HOST 	  Database host	               localhost
DB_USER 	  Database username            root
DB_PASSWORD	  Database password	           password
DB_NAME 	  Name of the MySQL database   greenthumb_db


### 🛠 Testing
To test the API:
Use tools like Postman or Insomnia to test API requests.

Run the test suite (if included):
npm test

(For manual testing, use tools like Postman or cURL)

### 🌍 Deployment
To test the API:
1. Use Postman or Insomnia.
2. Send requests to the routes mentioned above.
3. Ensure your database is seeded with sample data.

### 🤝 Contributing
We’d love your help in making GreenThumb even better! If you’d like to contribute:
1. Fork the repository.
2. Create a feature branch:
git checkout -b my-new-feature  
3. Commit your changes and submit a pull request.

### 📜 License
This project is licensed under the MIT License.

🌱 Let’s Grow Together!
We hope you enjoy using GreenThumb and that it helps you create the green spaces of your dreams. If you have any questions, feedback, or ideas, feel free to open an issue or reach out to us. Happy gardening! 🌼

