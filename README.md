Sure! Here's a more thoroughly paraphrased version with simpler wording and varied sentence structure:

---

### ICE Task 1 — INSY7314 Backend Setup Documentation

**Introduction**
This document presents the backend setup for ICE Task 1 in the INSY7314 module. It explains how a Node.js server was configured, connected to MongoDB Atlas, and how a Mongoose model was created. Functionality was verified through testing, following best practices for modular design, reproducibility, and academic integrity.

**Project Structure**
The backend files are organized as follows:

* **server.mjs** – the main server script
* **package.json** – contains project information and dependencies
* **README.md** – provides documentation for ICE Task 1

Each component is designed to keep the backend modular, well-structured, and easy to maintain.

**Environment Setup**
The project uses Node.js as the runtime environment. The setup steps included:

* Initializing the project with npm
* Installing dependencies:

  * **Express** for routing requests
  * **Mongoose** to interact with MongoDB
  * **dotenv** for managing environment variables
  * **CORS** to allow cross-origin requests
* Creating a **.env** file to securely store the MongoDB Atlas connection string
* Adding **.env** to **.gitignore** to protect sensitive information

This configuration ensures a secure, reliable, and scalable backend environment.

**Express Server Configuration**
The **server.mjs** file handles:

* Connecting to MongoDB Atlas via Mongoose
* Parsing incoming JSON requests
* Enabling CORS for frontend communication
* Implementing a **POST** endpoint to save notes to the database

This setup allows clients to submit notes, which are stored persistently in MongoDB.

**Testing and Validation**
Testing was performed using **curl** and **Postman** to confirm:

* The server starts without errors
* The POST route correctly receives and stores notes
* Data is accurately saved in MongoDB Atlas

Functionality was verified by checking runtime behavior and inspecting database entries.

**Submission Notes**

* The **.env** file is excluded from version control
* All backend files are included and documented
* Screenshots are provided in a separate Word file


