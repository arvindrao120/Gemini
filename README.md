# Gemini Clone 

This project consists of a separate frontend and backend application.

## Structure

- `/frontend`: Contains the React frontend application built with Vite.
- `/backend`: Contains the Node.js backend application using Express.

## Frontend (`/frontend`)

### Technology Stack

- **Framework:** React
- **Build Tool:** Vite
- **Styling:** (Assumed CSS/Modules - check `src/` for specifics)
- **HTTP Client:** Axios
- **Markdown:** `react-markdown`, `marked`, `highlight.js`, `prismjs`
- **Code Editor:** `react-simple-code-editor`

### Setup and Running

1.  Navigate to the frontend directory:
    ```bash
    cd frontend
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Run the development server:
    ```bash
    npm run dev
    ```
4.  Build for production:
    ```bash
    npm run build
    ```

## Backend (`/backend`)

### Technology Stack

- **Framework:** Node.js with Express
- **API:** Google Generative AI (`@google/generative-ai`)
- **Middleware:** CORS (`cors`)
- **Environment Variables:** `dotenv`
- **Development:** `nodemon` for auto-reloading

### Setup and Running

1.  Navigate to the backend directory:
    ```bash
    cd backend
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Create a `.env` file in the `backend` directory based on any required environment variables (e.g., for the Google Generative AI API key). Check `server.js` or related files for required variables.
4.  Run the server (development):
    ```bash
    nodemon server.js
    ```
    or for production (if configured):
    ```bash
    node server.js
    ```

---

_This README was partially generated based on the project structure and `package.json` files._
