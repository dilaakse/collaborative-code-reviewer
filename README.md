# Collaborative Real-Time Code Reviewer 

A microservices-based web platform that enables real-time collaborative code editing and automated quality analysis for Python and JavaScript.

## 🚀 Key Features
* **Real-Time Collaboration:** Synchronized code editing and peer commenting via Socket.io.
* **Automated Analysis:** Best practice checks using Pylint and ESLint engines.
* **Secure Auth:** JWT-based stateless authentication with password hashing (bcryptjs).
* **Monaco Editor:** VS Code-grade editing experience integrated into the browser.

## 🛠️ Tech Stack
* **Frontend:** React, Monaco Editor.
* **Gateway:** Node.js, Express.
* **Services:** 
  * Auth: Node.js, JWT, MongoDB[.
  * Analysis: Python, FastAPI, Pylint/ESLint.
  * Collaboration: Node.js, Socket.io.

## 🏗️ Architecture
The system follows a **4+1 View Model** and utilizes a microservices-oriented layered architecture.

## 👥 Team Members
* **Tuğba Gül:** Auth Service, React Frontend, Use Case View
* **Zeynep Dilara Köse:** Analysis Service, API Gateway, Logical & Process 
