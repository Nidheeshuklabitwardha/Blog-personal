Personal Blog Platform
This is a simple blog platform built with React (frontend) and Express (backend). It allows users to create, view, and manage blog posts. The application includes deployment instructions for hosting on services like Netlify (frontend) and Railway.app (backend).

Features:
###Frontend
Homepage displaying blog posts.
Form to create new blog posts.
Detailed view of individual blog posts.
Responsive and clean UI.

###Backend
REST API with the following endpoints:
GET /api/posts: Fetch all blog posts.
GET /api/posts/:id: Fetch a single blog post by ID.
POST /api/posts: Create a new blog post.
In-memory data storage.
CORS enabled for frontend-backend communication.


###Technologies Used
Frontend: React (with Vite), React Router, Axios.
Backend: Node.js, Express.js.
Deployment: Netlify (frontend), Railway.app (backend).

Getting Started
Prerequisites
Node.js installed on your machine.
Basic knowledge of React and Node.js.

####Setup Instructions
###Frontend (React)
Clone the repository:
bash
git clone <repository-url>
cd my-blog

Install dependencies:
bash
npm install

Run the development server:
bash
npm run dev

Build for production:
bash
npm run build

###Backend (Express)
Navigate to the backend directory:
bash
cd blog-backend

Install dependencies:
bash
npm install

Run the backend server:
bash
node server.js

###Deployment
##Frontend Deployment (Netlify)
Build the frontend:
bash
cd my-blog
npm run build

Drag and drop the dist/ folder into Netlify's dashboard or use the Netlify CLI:
bash
netlify deploy
Configure the site settings to ensure it points to the dist/ folder.

##Backend Deployment (Railway.app)
Push the backend code to a GitHub repository.
Link your repository to Railway.app.
Railway will automatically deploy the backend and provide a live URL.
