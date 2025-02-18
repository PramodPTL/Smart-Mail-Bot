# Smart Email Assistant Project

This project is a **Smart Email Assistant** that integrates AI functionality into your email client. It includes the following components:

1. **Back-End**: A Spring Boot application that utilizes the Gemini API to generate AI-powered email replies.
2. **Front-End**: A React-based web interface to facilitate interaction with the back-end.
3. **Browser Extension**: An extension that adds an "AI Reply" button to the email compose box, enabling one-click AI-generated replies.

## Prerequisites

- **Java** 11 or higher (for the back-end)
- **Node.js** and **npm** (for the front-end)
- A browser supporting extension installation (e.g., Chrome, Edge)
- Gemini API key

---

## Project Setup

### 1. Clone the Repository
```bash
git clone <repository-url>
```

---

### 2. Set up the Back-End (Spring Boot)

1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Make sure you have Java 11 or higher installed.

3. Use Maven or Gradle to build the project. For Maven:
   ```bash
   mvn clean install
   ```

4. Set up the Gemini API key in the `application.properties` file or relevant configuration file:
   ```properties
   gemini.api.key=your-gemini-api-key
   ```

5. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```

---

### 3. Set up the Front-End (React)

1. Navigate to the `frontend` directory:
   ```bash
   cd ../frontend
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Run the React app:
   ```bash
   npm run dev
   ```

---

### 4. Set up the Extension

1. Navigate to the `extension` folder:
   ```bash
   cd ../extension
   ```

2. Load the extension in your browser (for Chrome or similar browsers):
   
   - Open the Extensions page: `chrome://extensions`
   - Enable **"Developer Mode"**.
   - Click **"Load unpacked"** and select the `extension` folder.

---

### 5. Accessing the Application

- The back-end will be available at the configured port (default: `http://localhost:8080`).
- The front-end will run at `http://localhost:5173`.
- Use the browser extension to access the AI reply feature.

---

## Usage

1. Open the email compose box in your email client.
2. Click the **"AI Reply"** button added by the extension.
3. The system will generate a reply automatically using the Gemini API and populate the reply in the compose box.

---

## Screenshots

### Front-End
![WhatsApp Image 2025-01-28 at 19 53 06_f392c4ee](https://github.com/user-attachments/assets/9cb605bb-3f38-4f7c-8dba-91e6fde42b1d)


### Extension
![WhatsApp Image 2025-01-28 at 19 58 38_7f1169b3](https://github.com/user-attachments/assets/93dc2485-13c3-48f2-a9ba-c99c2cb64cc3)

---



