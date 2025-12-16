# EventHive 🐝

EventHive is a modern, full-stack **Event Management Dashboard** built using the **MERN Stack**. It enables organizers to create and manage events, control ticket approvals, and allows public users to register through unique, shareable event links.

---

## 🚀 Features

* **Organizer Dashboard** – Create, update, and manage events seamlessly.
* **Public Registration** – Share event-specific links for attendee registration without login.
* **Approval Systems**

  * **Auto-Approve** – Instant ticket generation after registration.
  * **Manual Approve** – Organizers review and approve requests before issuing tickets.
* **Digital Tickets** – Visually generated tickets with unique IDs.
* **Secure Authentication** – JWT-based authentication for organizers.
* **Dark Mode UI** – Premium glassmorphism design with dark theme.

---

## 🛠️ Tech Stack

**Frontend**

* React.js
* React Router
* Axios
* CSS (Glassmorphism UI)

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB (Atlas)

**Authentication & Security**

* JSON Web Tokens (JWT)
* Bcrypt

---

## 📦 Prerequisites

Before running the project, ensure you have the following installed:

* **Node.js** (v14 or higher)
* **MongoDB Atlas** account (or local MongoDB)
* **Git**

---

## 🔧 Installation & Setup

Follow the steps below to run EventHive locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/PBS-Alekhya/EventHive.git
cd event-hive
```

---

### 2️⃣ Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the **backend** folder and add the following:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_random_string
```

Start the backend server:

```bash
node server.js
```

✅ Expected output:

```
Server running on port 5000
MongoDB Connected
```

---

### 3️⃣ Frontend Setup

Open a new terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the React application:

```bash
npm start
```

The app will open automatically at:

👉 **[http://localhost:3000](http://localhost:3000)**

---

## 📖 Usage Guide

1. **Sign Up** – Create a new organizer account.
2. **Dashboard** – Click **"+ Create New Event"**.
3. **Choose Approval Mode**

   * **Auto Mode** – Tickets are generated instantly.
   * **Manual Mode** – Organizer approves registrations manually.
4. **Public Event Link**

   * Click **"Public Page"** on the event card.
   * Share or open the link in an incognito window to test registration.
5. **Manual Approval Flow**

   * Dashboard → **View Requests**
   * Approve or Reject attendees

---

## 📌 Notes

* Public users do **not** need to log in to register.
* Only organizers require authentication.
* Each ticket includes a **unique ID** for verification.


