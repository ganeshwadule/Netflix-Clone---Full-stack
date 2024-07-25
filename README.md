Netflix Clone
A fully functional Netflix Clone built using the MERN stack (MongoDB, Express.js, React, Node.js). This project replicates the core features of Netflix, including user authentication, movie browsing, and video playback.

Table of Contents

Installation
Usage
Technologies
Contributing
License
Contact
Features
User authentication (sign up, log in, log out)
Browse movies and TV shows
Search functionality
Video playback
User profile management
Responsive design



Installation
Clone the repository:

bash
Copy code
git clone https://github.com/ganeshwadule/netflix-clone.git
cd netflix-clone
Install server dependencies:

bash
Copy code
cd server
npm install
Install client dependencies:

bash
Copy code
cd ../client
npm install
Set up environment variables:

Create a .env file in the server directory and add the following:

env
Copy code
MONGO_URI=your_mongo_database_uri
JWT_SECRET=your_jwt_secret
Run the development server:

bash
Copy code
cd server
npm start
Run the client:

bash
Copy code
cd ../client
npm start
Usage
Open your browser and go to http://localhost:3000.
Sign up for a new account or log in with an existing account.
Browse through the list of movies and TV shows.
Search for specific titles.
Click on a title to view its details and start playback.
Technologies
Frontend: React, Redux, CSS
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT)
Video Playback: HTML5 Video


Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
Ganesh Bandu Wadule - LinkedIn - ganesh.wadule@example.com

Project Link: https://github.com/ganeshwadule/netflix-clone
