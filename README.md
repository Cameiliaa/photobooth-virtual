# Virtual Photobooth Online

A web-based photobooth application that allows users to capture, edit, and download photostrips directly from the browser.

---

## Features

* Capture photos using webcam (WebRTC)
* Multiple photobooth layouts (1, 2, 3, and 4 grid)
* Photo editing with filters (grayscale, sepia, etc.)
* Add stickers and decorations
* Custom photobooth frames
* Download high-quality photostrips
* Google Authentication using Firebase
* Deployed online using Vercel

---

## Tech Stack

* Frontend: React, Vite, TypeScript
* Styling: Tailwind CSS
* Canvas Processing: Fabric.js
* Authentication: Firebase Authentication (Google Sign-In)
* Deployment: Vercel

---

## Getting Started

### 1. Clone Repository

```bash
git clone https://github.com/Cameiliaa/photobooth-virtual.git
cd photobooth-virtual
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 4. Run Development Server

```bash
npm run dev
```

---

## Deployment

This project can be deployed using Vercel:

1. Push the project to GitHub
2. Import the repository into Vercel
3. Add environment variables
4. Deploy the project

---

## Firebase Setup

1. Create a project in Firebase
2. Enable Google Authentication
3. Add your deployment domain in:
   Authentication → Settings → Authorized domains
4. Copy Firebase configuration into environment variables

---

## Author

Cameilia Dwiyanti Suwarni

---

## License

This project is intended for educational purposes.
