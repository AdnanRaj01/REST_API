REST API Project

Overview

This project is a RESTful API that allows users to create, view, edit, and delete posts. The interface is designed with a simple layout for ease of navigation.

Features

Create Post: Add new posts with content.

View Post Details: See the full details of individual posts.

Edit Post: Update existing posts.

Delete Post: Remove posts from the system.

Technologies Used

Node.js

Express.js

EJS (Embedded JavaScript Templating)

HTML/CSS

Installation

Clone the repository:

git clone https://github.com/username/repo-name.git

Navigate to the project directory:

cd rest-api-project

Install dependencies:

npm install

Run the server:

node index.js

Open the browser and navigate to:

http://localhost:3000

API Endpoints

GET /

Displays the homepage with all posts.

GET /ig/:skill

Displays posts related to the specified skill.

POST /create

Creates a new post.

POST /edit/:id

Edits an existing post.

DELETE /delete/:id

Deletes a specified post.

Folder Structure

rest-api-project/
│
├── views/
│   ├── home.ejs
│   ├── new.ejs
│   ├── edit.ejs
│   ├── show.ejs
│
├── public/
│   ├── styles.css
│
├── index.js
├── package.json
└── README.md

License

MIT License

Author

Muhammad Adnan
