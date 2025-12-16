# EventHive 🐝

EventHive is a modern, full-stack Event Management Dashboard built with the MERN Stack. It allows organizers to create events, manage ticket approvals, and enables public users to register via unique event links.

## 🚀 Features

* **Organizer Dashboard:** Create and manage events with ease.
* **Public Registration:** Shareable links for attendees to register without logging in.
* **Approval Systems:**
    * **Auto-Approve:** Instant ticket generation.
    * **Manual Approve:** Organizers review requests before issuing tickets.
* **Digital Tickets:** visual ticket generation with unique IDs.
* **Secure Authentication:** JWT-based login/signup for organizers.
* **Dark Mode UI:** Sleek, glassmorphism design for a premium feel.

## 🛠️ Tech Stack

* **Frontend:** React.js, React Router, Axios, CSS (Glassmorphism).
* **Backend:** Node.js, Express.js.
* **Database:** MongoDB (Atlas).
* **Auth:** JSON Web Token (JWT), Bcrypt.

## 📦 Prerequisites

Before running the project, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v14 or higher)
* [MongoDB Atlas](https://www.mongodb.com/atlas/database) Account (for the database URI)

## 🔧 Installation & Setup

Follow these steps to get the project running on your local machine.

Prerequisites
Node.js installed.

MongoDB Atlas account (or local MongoDB installed).

Git installed.

1. Clone the Repository
Bash

git clone [https://github.com/YOUR_GITHUB_USERNAME/event-hive.git](https://github.com/YOUR_GITHUB_USERNAME/event-hive.git)
cd event-hive
2. Backend Setup
Navigate to the backend folder:


cd backend
Install dependencies:



npm install
Create a .env file in the backend folder and add your credentials:

Code snippet

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_random_string

Start the server:

node server.js
You should see: Server running on port 5000 and MongoDB Connected.

3. Frontend Setup
Open a new terminal window and navigate to the frontend folder:

cd frontend

Install dependencies:

npm install

Start the React app:

npm start
The app will open automatically at http://localhost:3000.

📖 Usage Guide

Sign Up: Create a new organizer account.

Dashboard: Click "+ Create New Event".

Choose Mode:

Select "Auto" if you want tickets generated instantly.

Select "Manual" if you want to approve attendees yourself.

Public Link: Click the "Public Page" button on an event card. Copy the URL and open it in a new browser/incognito window to test registration.

Approve (Manual Mode): Go back to Dashboard -> Click "View Requests" -> Approve or Reject candidates.