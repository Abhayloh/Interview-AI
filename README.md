# Interview AI

AI-powered interview preparation platform built with Node.js, Express, React, and Google Gemini API.

## Project Structure

- **`Backend/`**: Express.js server, MongoDB database connection, JWT authentication, Google Gemini AI integration (`@google/genai`), and PDF generation using Puppeteer.
- **`Frontend/`**: React 19 (Vite) application with SCSS styling, React Router, and Axios.

---

## Getting Started

### 1. Backend Setup

1. Navigate to the Backend directory:
   ```bash
   cd Backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file from `.env.example`:
   ```env
   PORT=3000
   MONGO_URI=mongodb://localhost:27017/interview-ai
   JWT_SECRET=your_secret_key
   GOOGLE_GENAI_API_KEY=your_gemini_api_key
   ```
4. Start the backend development server:
   ```bash
   npm run dev
   ```

### 2. Frontend Setup

1. Navigate to the Frontend directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) in your browser.
