## 🚀 Code Initiation

Follow these steps to get the FreightShare platform running locally:

### 1. Clone the repository
```
git clone https://github.com/yourusername/freightshare-platform.git
cd freightshare-platform
```

### 2. Install dependencies

Install server and client dependencies:
```
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 3. Environment setup

Set up the required environment variables. Copy the sample environment files and update with your configuration:
```
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
```
- Edit `.env` files to include your database URL, API keys, and other secrets.

### 4. Start the development servers

Start backend and frontend apps:
```
# In backend/
npm run dev

# In frontend/ (new terminal)
npm start
```

Open `http://localhost:3000` to view the frontend application.
```

Let me know if you want the full README including this section as a downloadable markdown file.
