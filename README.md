# Express-Rest-API-CRUD
A RESTful CRUD application built with Node.js, Express, and EJS for managing posts.

REST APIs Project (CRUD App)
🚀 Project Overview

This project is a simple RESTful web application built using Node.js, Express, and EJS. It allows users to create, read, update, and delete posts.

It demonstrates the core concepts of:

REST APIs

CRUD operations

Server-side rendering with EJS

Routing in Express

✨ Features

📝 Create new posts

📖 View all posts

🔍 View a single post

✏️ Edit existing posts

❌ Delete posts

🆔 Unique ID generation using UUID

🔁 Method override for PATCH & DELETE

🛠️ Tech Stack

Backend: Node.js, Express.js

Frontend: EJS (Embedded JavaScript Templates)

Utilities: UUID, Method-Override

Styling: CSS (public folder)

📂 Project Structure
REST_APIs/
│── views/          # EJS templates (index, new, edit, show)
│── public/         # Static files (CSS, images)
│── node_modules/
│── index.js        # Main server file
│── package.json
⚙️ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/your-repo-name.git

2️⃣ Navigate to the project folder

cd REST_APIs

3️⃣ Install dependencies

npm install

4️⃣ Run the server

node index.js

5️⃣ Open in browser

http://localhost:3000/posts
🔗 API Routes
Method	Route	Description
GET	/posts	Show all posts
GET	/posts/new	Create post form
POST	/posts	Add new post
GET	/posts/:id	View single post
GET	/posts/:id/edit	Edit post form
PATCH	/posts/:id	Update post
DELETE	/posts/:id	Delete post
📸 Screenshots

(Add your project screenshots here for better presentation)

🎯 Learning Outcomes

Understanding REST architecture

Handling dynamic routes in Express

Using EJS for templating

Implementing CRUD functionality

Managing in-memory data

⚠️ Known Issues

Duplicate route for /posts/:id (needs fixing)

Data is not persistent (stored in memory only)

🔮 Future Improvements

Connect to MongoDB database

Add user authentication

Improve UI/UX design

Add validation and error handling

👨‍💻 Author

Kamaljeet Sharma

⭐ Support

If you like this project, give it a ⭐ on GitHub!
