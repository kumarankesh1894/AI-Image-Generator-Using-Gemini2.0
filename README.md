# Project Title: AI Image Generator Web Application
Project Type: Full Stack Web Application

Role: Full Stack Developer

# Project Overview
I developed a full-stack AI Image Generator Website where users can input a text prompt to generate images using Google's Gemini AI (GenAI). Users can preview the generated image, download it, and optionally publish the image with their name on the platform.

## Key Features

🔍 AI-based Image Generation
Users enter a prompt that is processed through Google GenAI (Gemini API) to generate high-quality images.

💾 Image Storage & Publishing
Images can be uploaded to Cloudinary and displayed in a public gallery with the user’s name.

📦 Download Functionality
Users can download the generated images directly using FileSaver.js.

🧠 Lazy Loading for Performance
Images are lazy-loaded using the react-lazy-load-image-component for optimized performance.

🧭 User-Friendly Interface
Developed using Material-UI and Styled Components, the interface is responsive and intuitive.
List your project features...

## Tech Stack:
🔹 Frontend (React.js):
React.js (v18.2.0)

React Router DOM (v6.22.0) – For routing

Material-UI & Icons – For UI components

Styled Components & Emotion – CSS-in-JS styling

Axios – For HTTP requests

FileSaver.js – To enable image downloads

React Lazy Load Image Component – Image optimization

🔹 Backend (Node.js + Express):
Express.js (v4.18.2) – REST API framework

Node.js (with ES Modules)

MongoDB + Mongoose (v8.1.1) – For database management

Node-fetch – For internal API calls

Google GenAI SDK (@google/genai) – For image generation

Cloudinary – For storing images in the cloud

Dotenv – Environment variable management
.env_example:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
GOOGLE_GENAI_API_KEY=your_google_genai_api_key

CORS & Nodemon – For development and API access

## Getting Started

1.Clone the repo.

2. Install dependencies: npm install
   
3.Set up your .env file with necessary API keys and configuration.

4.Run the development server:
npm start

## Folder Structure

client/ – React frontend components and styling.

server/ – Express backend routes, controllers, and database models.
## Future Improvements

Add user authentication.

Enable image sharing on social platforms.

Enhance UI/UX with animations and better accessibility.

## Author

Name: Kumar Ankesh

LinkedIn : https://www.linkedin.com/in/kumar-ankesh/

