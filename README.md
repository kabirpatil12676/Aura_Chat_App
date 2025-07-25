# Aura_Chat_App
Aura Chat App
Real-time Chat Application
Aura Chat App is a modern, responsive, and real-time chat application built to provide seamless communication. It supports direct messaging, group chats, file sharing, and offers a smooth user experience across various devices. This project serves as a comprehensive full-stack development example, showcasing best practices in both frontend and backend development.

✨ Features
Real-time Messaging: Instantaneous sending and receiving of messages.

User Authentication: Secure login and sign-up flows.

Profile Management: Users can complete and edit their profiles, including UI color and profile pictures.

Direct Messaging: One-on-one private conversations with contacts.

Group Messaging: Create and manage group chats with multiple participants.

File Sharing: Send documents and images directly within chats.

Emoji Support: Express yourself with a rich collection of emojis.

Responsive Design: Optimized for a consistent experience on mobile, tablet, and desktop devices.

Toast Notifications: User-friendly feedback for various actions.

Image Viewer: Enlarge and download shared images.

🚀 Technologies Used
This project leverages a powerful stack to deliver a robust and scalable application.

Frontend
React: A declarative, component-based JavaScript library for building user interfaces.

Tailwind CSS: A utility-first CSS framework for rapidly building custom designs.

Shadcn UI: Reusable UI components built with Radix UI and Tailwind CSS.

Zustand: A small, fast, and scalable bearbones state-management solution.

React Router DOM: Declarative routing for React applications.

Axios: Promise-based HTTP client for the browser and Node.js.

Sonner: An opinionated toast component for React.

Lottie React: React component for rendering Lottie animations.

Emoji Picker React: A simple and customizable emoji picker for React.

Vite: A fast frontend build tool.

Backend
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.

Express.js: A fast, unopinionated, minimalist web framework for Node.js.

Socket.io: A library that enables real-time, bidirectional, event-based communication.

MongoDB: A NoSQL document database.

Mongoose: An elegant MongoDB object modeling for Node.js.

JSON Web Tokens (JWT): For secure user authentication.

Cookie-Parser: Middleware to parse cookie headers.

Multer: Middleware for handling multipart/form-data, primarily used for uploading files.

Bcrypt: A library to help you hash passwords.

Nodemon: A tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.

⚙️ Setup and Installation
To get a local copy up and running, follow these simple steps.

Prerequisites
Before you begin, ensure you have the following installed on your machine:

Node.js (LTS version recommended) & npm (comes with Node.js)

Download from: https://nodejs.org/

MongoDB Community Server

Download from: https://www.mongodb.com/try/download/community

Ensure you start the MongoDB server (mongod) before running the backend.

1. Clone the repository
git clone https://github.com/YourUsername/Aura_chat_app.git
cd Aura_chat_app

(Replace YourUsername with your actual GitHub username once uploaded)

2. Backend Setup
Navigate to the server directory, install dependencies, and start the server.

cd server
npm install
npm run start:dev # Or `npm start` for production

Note: Ensure your server/package.json has a script like "start:dev": "nodemon index.js" or similar for development.

3. Frontend Setup
Open a new terminal window, navigate to the client directory, install dependencies, and start the development server.

cd client
npm install
npm run dev

This will typically open your application in your browser at http://localhost:5173 (or a similar port).

📦 Deployment
The original tutorial demonstrated deployment on Hostinger VPS. For production, you would typically build the client assets and then serve them from your Node.js server or a separate static hosting service.

Building Client for Production
cd client
npm run build

This command creates a dist folder in your client directory, containing the optimized static assets. You can then configure your Node.js server to serve these files.



🤝 Contributing
Contributions are welcome! If you have suggestions for improvements or find issues, please open an issue or submit a pull request.

📄 License
This project is open-sourced under the MIT License.
