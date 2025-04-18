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

## First Time Setup (Running the Full Project)

To run the entire project for the first time, you'll need Node.js installed on your system.

1.  **Install Node.js:**

    - Download and install Node.js (which includes npm) from [nodejs.org](https://nodejs.org/). Choose the LTS version for stability.

2.  **Clone the Repository (if you haven't already):**

    ```bash
    git clone https://github.com/arvindrao120/Gemini.git
    cd <repository-folder-name>
    ```

3.  **Setup Backend:**

    - Navigate to the backend directory:
      ```bash
      cd backend
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Create a `.env` file and add the necessary environment variables (e.g., `API_KEY` for Google Generative AI). Refer to the code or documentation for required variables. Example `.env` content:
      ```
      API_KEY=YOUR_GOOGLE_API_KEY
      PORT=8000
      ```
      _(Note: Adjust `PORT` if needed)_
    - Go back to the root directory:
      ```bash
      cd ..
      ```

4.  **Setup Frontend:**

    - Navigate to the frontend directory:
      ```bash
      cd frontend
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Go back to the root directory:
      ```bash
      cd ..
      ```

5.  **Run the Application:**

    - **Open two separate terminal windows.**
    - **In Terminal 1 (Backend):**
      ```bash
      cd backend
      npm run start # Assuming you add a start script like "start": "nodemon server.js" to backend/package.json
      # OR directly use nodemon if no start script:
      # nodemon server.js
      ```
    - **In Terminal 2 (Frontend):**
      ```bash
      cd frontend
      npm run dev
      ```

6.  **Access the Application:**
    - Open your web browser and navigate to the address provided by the Vite development server (usually `http://localhost:5173` or similar).
