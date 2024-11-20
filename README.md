# **Netflix Clone Application**

## **Project Overview**  
The Netflix Clone is a full-stack web application that replicates the core features of Netflix. It enables users to browse movies and TV shows, watch trailers, search for content, view search history, and manage user authentication. Built with modern technologies like React, Node.js, and MongoDB, this application emphasizes responsiveness, user experience, and scalability.

---

## **Live Demo**  
Live Demo Link : netflix-clone-21g.pages.dev 

---

## **Features**  
- **Authentication:** User signup, login, and logout with JWT-based authentication.  
- **Content Fetching:** Displays movies and TV shows fetched from external APIs.  
- **Search:** Search for movies, TV shows, and actors.  
- **Trailers:** Watch movie and TV show trailers.  
- **Search History:** View previously searched items.  
- **Similar Content:** Explore similar movies/TV shows based on selections.  
- **Responsive Design:** Fully optimized for desktops, tablets, and mobile devices.  
- **Custom Pages:** Includes a custom 404 error page for invalid routes.  
- **Deployment:** Deployed for global accessibility.  

---

## **Installation Instructions**

### **Prerequisites**  
- Node.js (v14.0.0 or above)  
- npm or yarn  
- MongoDB instance (local or cloud-based, such as MongoDB Atlas)  

### **Steps to Run the Project Locally**  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-repo/netflix-clone.git
   cd netflix-clone
   ```

2. **Set up the Backend**  
   ```bash
   cd backend
   npm install
   npm run dev
   ```

3. **Set up the Frontend**  
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

4. **Run the Application**  
   - Access the backend on `http://localhost:5000` (default port).
   - Access the frontend on `http://localhost:5173` (default port).

---

## **Technology Stack**  
### **Frontend**  
- **React.js:** Core framework for building the UI.  
- **React Router DOM:** Handles routing in the application.  
- **Tailwind CSS:** Provides styling and responsive design.  
- **Axios:** Simplifies HTTP requests for API integration.  
- **React Player:** Embeds video players for trailers.  
- **Zustand:** Manages state in the application.  

### **Backend**  
- **Node.js:** Server-side JavaScript runtime.  
- **Express.js:** Backend framework for creating APIs.  
- **MongoDB:** NoSQL database for storing user data and search history.  
- **JWT:** Ensures secure user authentication and authorization.  
- **Bcrypt:** Encrypts user passwords for secure storage.  

### **Dependencies List**

#### Frontend Dependencies  
```json
"dependencies": {
  "axios": "^1.7.2",
  "lucide-react": "^0.408.0",
  "react": "^18.3.1",
  "react-dom": "^18.3.1",
  "react-hot-toast": "^2.4.1",
  "react-player": "^2.16.0",
  "react-router-dom": "^6.25.0",
  "tailwind-scrollbar-hide": "^1.1.7",
  "zustand": "^4.5.4"
}
```

#### Backend Dependencies  
```json
"dependencies": {
  "axios": "^1.7.2",
  "bcryptjs": "^2.4.3",
  "cookie-parser": "^1.4.6",
  "dotenv": "^16.4.5",
  "express": "^4.19.2",
  "jsonwebtoken": "^9.0.2",
  "mongoose": "^8.5.1"
}
```

---

## **Architecture**  
- **Frontend:** Built using React with reusable components and Tailwind for CSS styling.  
- **Backend:** RESTful API using Express.js for routing, with MongoDB as the database for storing user data and search history.  
- **Database:** MongoDB is used for data persistence.  
- **Authentication:** JWT ensures secure token-based user sessions.  

---

## **Deployment**  
- **Frontend:** Deployed using Cloudflare Page.  
- **Backend:** Deployed using platforms like Render.  
- **Database:** MongoDB Atlas for a cloud-hosted database solution.  

---

