# Project Setup and Run Instructions (XceloreAssesment)

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)
- MongoDB (You can use MongoDB Atlas or a local instance)

## Steps to Setup and Run the Project

1. **Download the Repository:**
   - Download the zip file of the current repository provided to you.
   - Unzip the folder.

2. **Frontend Setup:**
   - Change directory to the frontend:
     ```bash
     cd frontend
     ```
   - Install the necessary packages:
     ```bash
     npm install
     ```

3. **Environment Setup:**
   - Create a `.env` file in the root directory and add the following lines:
     ```
     PORT=5000
     MONGO_URI="your_connection_string"
     JWT_SECRET=your_jwt_secret
     ```
   - Replace `your_connection_string` with the connection string from your MongoDB instance.


4. **MongoDB Setup:**
   - Go to MongoDB Compass (or your MongoDB Atlas dashboard).
   - Create a new database and collection.
   - Copy the connection string and paste it into the `.env` file under `MONGO_URI`.

5. **Backend Setup:**
   - Change directory to the backend:
     ```bash
     cd backend
     ```
   - Install the necessary packages:
     ```bash
     npm install
     ```

6. **Running the Project:**
   - Start the frontend:
     ```bash
     cd frontend
     npm start
     ```
   - Start the backend:
     ```bash
     cd backend
     npm start
     ```

## Additional Notes

- Ensure your MongoDB server is running before starting the backend.
- The frontend will run on the web (usually `http://localhost:3000`), and the backend will run on the server (usually `http://localhost:5000`).
- Make sure to keep your `.env` file secure and do not share it publicly.

Feel free to reach out if you encounter any issues during setup or run.
