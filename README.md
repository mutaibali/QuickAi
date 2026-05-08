# QuickAI

QuickAI is a full-stack AI-powered web application that enables users to generate images in real time using advanced AI models. The platform is designed with a modern responsive frontend, secure authentication system, scalable backend APIs, and cloud-based image storage for efficient performance and deployment.

---

## Features

- Real-time AI image generation
- Secure user authentication and authorization
- Cloud image upload and storage using Cloudinary
- Responsive and modern UI
- RESTful API architecture
- Scalable backend integration
- Fast and optimized deployment
- Modular full-stack architecture

---

## Tech Stack

### Frontend
- React.js
- Vite
- HTML5
- CSS3
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Cloud & Deployment
- Cloudinary
- Vercel

### Authentication
- JWT (JSON Web Tokens)

---

## Project Structure

```bash
QuickAI/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── package.json
│
└── README.md

## Installation

### Clone the Repository

```bash
git clone https://github.com/mutaibali/QuickAi.git
```

### Navigate to Project Directory

```bash
cd QuickAi
```

---

## Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

## Backend Setup

```bash
cd server
npm install
npm start
```

---

## Environment Variables

Create a `.env` file in the server directory and add:

```env
MONGODB_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
```

---

## Future Improvements

- AI chat integration
- Image history management
- User dashboard
- Payment integration
- AI prompt enhancement
- Image editing capabilities
- Dark mode support
