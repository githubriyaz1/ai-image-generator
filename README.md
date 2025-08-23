# 🎨 AI Image Generation Showcase 🤖

Welcome to the AI Image Generation App\! A full-stack web application that brings your imagination to life. Turn any text prompt into a unique, AI-generated image and share it with a vibrant community of creators.

-----

### ✨ **[View the Live Demo Here\!](https://www.google.com/search?q=https://ai-image-generator-delta-one.vercel.app/)** ✨

-----

## 🚀 Core Features

  - **🧠 AI-Powered Creation:** Type any idea and watch as the AI generates a stunning image based on your prompt.
  - **🖼️ Community Gallery:** Explore a beautiful, responsive gallery of images created by other users.
  - **🔍 Smart Search:** Instantly find images in the gallery by searching for names or prompts.
  - **💡 Surprise Me Button:** Feeling uninspired? Get a random, creative prompt to kickstart your next masterpiece\!
  - **📲 Fully Responsive:** Enjoy a seamless experience on both desktop and mobile devices.

-----

## 🛠️ Technology Stack

This project is built with a modern and powerful MERN stack:

  - **Frontend:** ⚛️ React.js | ⚡ Vite | 💅 Tailwind CSS
  - **Backend:** 🟩 Node.js | 🚂 Express.js
  - **Database:** 🍃 MongoDB (with Mongoose)
  - **AI Model:** 🤗 Hugging Face (Stable Diffusion)
  - **Deployment:** 🚀 Vercel (Frontend) | ☁️ Render (Backend)

-----

## ⚙️ Getting Started: Local Setup

Want to run this project on your own machine? Follow these simple steps.

### Prerequisites

  - Node.js (v16+)
  - A free [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account
  - A free [Hugging Face](https://huggingface.co/join) account

### 1\. Clone the Repository

```bash
git clone https://github.com/githubriyaz1/ai-image-generator.git
cd ai-image-generator
```

### 2\. Backend Setup 서버

```bash
# 1. Navigate to the server directory
cd server

# 2. Install all required packages
npm install

# 3. Create a .env file and add your secret keys (see below)
touch .env

# 4. Start the server!
npm start
```

### 3\. Frontend Setup 💻

```bash
# 1. Open a new terminal and navigate to the client directory
cd client

# 2. Install all required packages
npm install

# 3. Create a .env file and add the backend URL (see below)
touch .env

# 4. Start the client!
npm run dev
```

-----

## 🔑 Environment Variables

You'll need to create a `.env` file in both the `server` and `client` folders.

#### `server/.env`

```
MONGODB_URL=YOUR_MONGODB_ATLAS_CONNECTION_STRING
HUGGINGFACE_API_KEY=YOUR_HUGGINGFACE_API_KEY_HERE (must start with hf_)
```

#### `client/.env`

```
VITE_API_URL=http://localhost:8080
```

-----

## 🙏 Acknowledgements

This project was built based on the excellent MERN stack by **MOHAMED RIYAZ** from fxec. This version has been adapted to use the free and powerful Hugging Face Inference API for image generation.
