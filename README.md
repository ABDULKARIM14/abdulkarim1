# abdulkarim1
student portfolio

Student Portfolio Site
Description
The Student Portfolio Site is a platform designed for students to manage and showcase their digital portfolio. This includes adding and managing projects, blogs, and educational background information. The platform is built with Next.js for the frontend and MongoDB for the backend database.

Tech Stack
Frontend: Next.js
Backend: Node.js with Express
Database: MongoDB
Styling: CSS Modules
Authentication: NextAuth.js
Features
User authentication and authorization
CRUD operations for projects, blogs, and educational background
Responsive design
User-friendly interface
Installation and Setup
Clone the repository:



npm install
Set up environment variables:

Create a .env.local file in the root directory and add the following variables:

env

MONGODB_URI=your_mongodb_uri
NEXTAUTH_URL=http://localhost:3000
Run the development server:

npm run dev
Open http://localhost:3000 with your browser to see the result.

Build for production:

npm run build
npm start
Project Structure

.
├── components
│   ├── BlogCard.js
│   ├── Footer.js
│   ├── Header.js
│   └── ProjectCard.js
├── pages
│   ├── api
│   │   └── auth.js
│   ├── blogs.js
│   ├── index.js
│   ├── login.js
│   ├── projects.js
│   └── register.js
├── public
│   ├── favicon.ico
│   └── images
├── styles
│   ├── BlogCard.module.css
│   ├── Footer.module.css
│   ├── Header.module.css
│   └── ProjectCard.module.css
├── .env.local
├── next.config.js
├── package.json
└── README.md
Usage


