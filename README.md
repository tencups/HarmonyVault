---

## **Frontend README** (Harmony Vault Frontend)

---

# **Harmony Vault Frontend**
### A React-based user interface for managing musician data, biographies, and audio storage for WMUC radio shows.

---

## **Overview**
Harmony Vault's frontend is a **React.js** application that provides a clean and interactive UI for users to manage musician data efficiently. This tool integrates with the Harmony Vault backend API to allow radio show hosts to upload audio files, manage biographies, and curate musician profiles.

The project was designed to **streamline workflows** for [WMUC Radio Shows](https://www.wmuc.umd.edu/show/282907).

---

## **Key Features**
- **Artist Management**: View, add, and edit artist profiles.
- **Audio Upload and Download**: Seamlessly upload audio files and download them when needed.
- **Responsive Design**: Optimized for desktops and mobile devices.
- **Integration with Backend API**: Connects to the Spring Boot RESTful API.

---

## **Project Structure**
```plaintext
src/
 ├── components/      (Reusable UI components)
 ├── pages/           (Page-level React components)
 ├── services/        (API calls to the backend)
 ├── assets/          (Static assets like images, icons)
 ├── App.js           (Main React component)
 ├── index.js         (Application entry point)
 └── package.json     (Dependencies and scripts)
```

---

## **Dependencies**
- **React.js** (Frontend framework)
- **Axios** (HTTP client for API calls)
- **React Router** (Client-side routing)
- **Bootstrap / Tailwind CSS** (UI styling)

---

## **Setup and Installation**

### **Prerequisites**
- Node.js and npm installed

### **Steps:**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/harmony-vault-frontend.git
   cd harmony-vault-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

4. Open the application in your browser:
   - `http://localhost:3000`

---

## **Connecting to Backend**
Ensure the backend server is running at `http://localhost:8080`. Update the `API_BASE_URL` in a configuration file or `services/api.js`:

```javascript
const API_BASE_URL = "http://localhost:8080";
export default API_BASE_URL;
```

---

## **Available Pages**
- **Artists Page**: View all artists and their profiles.
- **Artist Detail Page**: View biographies and audio files.
- **Upload Page**: Upload new audio files or images.
- **Edit Artist Page**: Modify artist details.

---

## **Contributing**
Contributions are welcome! Fork the repository, make changes, and submit a pull request.

---

## **License**
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
