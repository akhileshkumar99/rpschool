# School Website Admin System

## Setup Instructions

### 1. Install MongoDB
Download and install MongoDB from https://www.mongodb.com/try/download/community
Start MongoDB service: `mongod`

### 2. Install Server Dependencies
```bash
cd server
npm install
```

### 3. Start Server
```bash
npm start
```
Server runs on http://localhost:5000

### 4. Start React App
```bash
cd ..
npm run dev
```

### 5. Access Admin Panel
- Click "Admin" link in footer
- Login: admin / admin123

## Features
- Admin authentication
- Gallery image upload/delete
- Hero slides management
- Faculty management
- Courses management
- MongoDB database
- File upload support

## Database Collections
- admins
- galleries
- heroslides
- faculties
- courses
