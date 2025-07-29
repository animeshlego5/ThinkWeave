# ThinkWeave.ai

**Live demo:** [ThinkWeave.ai](https://think-weave.vercel.app/)

ThinkWeave is an AI-powered SaaS platform for content and image generation, built using the PERN stack (PostgreSQL, Express.js, React.js, Node.js) with modern authentication, serverless API, and cloud integration. Users can generate AI articles, images, get resume feedback, and more, all within a collaborative web app.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Deployment](#deployment)
- [License](#license)


---

## Features

- **AI Article & Blog Title Generation**  
  Generate high-quality articles and SEO blog headlines using advanced AI models.

- **AI Image Generation**  
  Create custom images from prompts with support for diverse styles.

- **Resume Review**  
  Upload your PDF resume and receive AI-powered, actionable feedback.

- **Image Manipulation**  
  Remove backgrounds or objects from images with a single click.

- **User Authentication**  
  Secure sign-in/up via Clerk.

- **Premium & Free Usage**  
  Quota system for free users, with premium upgrades for unlimited usage.

- **Community Gallery**  
  Browse, like, and engage with published creations from other users.

---

## Tech Stack

**Frontend:**

- React.js (Vite)
- Tailwind CSS
- Clerk for authentication

**Backend:**

- Node.js + Express.js (serverless, deployed to Vercel)
- Neon Serverless PostgreSQL (database)
- Multer (for file uploads, in-memory storage)
- Cloudinary (image hosting & manipulation)
- AI APIs: Google Gemini, ClipDrop, and others

---

## Deployment

- **Frontend:** Deployed to Vercel for fast, serverless global delivery.

- **Backend:** Deployed as serverless functions to Vercel, connected to Neon’s serverless PostgreSQL.

- **Database:** Neon for scalable and persistent Postgres database-as-a-service.

## License
This project is licensed under the MIT License.
