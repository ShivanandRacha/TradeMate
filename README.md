# TradeMate – Stock Trading Platform

A full-stack stock trading platform, offering functionalities like live order placements, holding management, and position tracking. Built using modern JavaScript technologies and scalable design principles.

## 🚀 Features

- 📈 Real-time portfolio management (Holdings, Orders, Positions)
- 🔐 User authentication & secure API access (via `.env`)
- 🧾 Backend built on modular Mongoose schemas and models
- ⚙️ RESTful APIs for integration with a frontend or third-party apps
- 💼 Ready to integrate with a React/Next.js frontend (not included)

## 🛠️ Tech Stack

**Backend:**
- Node.js
- Express.js
- MongoDB + Mongoose

**Project Structure:**
```
TradeMate-main/
│
├── backend/
│   ├── model/               # Mongoose models (Holdings, Orders, Positions)
│   ├── schemas/             # Mongoose schemas
│   ├── index.js             # Main server file
│   ├── .env                 # Environment variables
│   └── package.json
```

## 🧪 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/TradeMate-main.git
cd TradeMate-main/backend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment

Create a `.env` file in the `backend/` directory and add your MongoDB URI:

```
MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<dbname>?retryWrites=true&w=majority
PORT=5000
```

### 4. Run the Server

```bash
node index.js
```

The backend server should now be running at `http://localhost:5000`.

---

## 📡 API Overview

Basic endpoints provided by the backend:

- `GET /api/holdings`
- `GET /api/orders`
- `GET /api/positions`
- `POST /api/...` (Add endpoints for creating new records)

> Full API documentation is coming soon.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or features.

---

## 🌐 Acknowledgments

Inspired by Zerodha’s clean UX and robust trading system. This is a student project and not intended for real trading purposes.
