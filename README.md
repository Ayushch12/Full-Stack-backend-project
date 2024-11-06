

# SyncVote REST API

### Powered by Node.js and TypeScript

---

### 🚀 Quick Start

1. **Install Dependencies**:
   ```bash
   npm install
   ```

---

### 🛠 Prerequisites

Ensure **Redis** is installed and running.

1. **Download Redis**:
   - Visit [Redis.io](https://redis.io/download) and select the appropriate version for your operating system.

2. **Start Redis Server**:
   - Once installed, launch Redis by running:
     ```bash
     redis-server
     ```
   - Verify that Redis is up and running before starting the project.

---

### 👨‍💻 Development Setup

1. **Configure Environment**:
   - Copy `.env.example` to `.env` and update any required environment variables.

2. **Start the Development Server**:
   ```bash
   npm run dev
   ```
   - Open [http://localhost:8080](http://localhost:8080) to view the app.
   - For API documentation and testing, visit [http://localhost:8080/api-docs](http://localhost:8080/api-docs).

   **Note**: When accessing `/api-docs`, remember to add your Authorization token. Click “Authorize” at the top, enter your token (no need for “Bearer”; it’s handled automatically), and ignore the second input field.

---

### 👤 Creating a New Admin User

To set up a new admin:
```bash
npm run create-admin
```
