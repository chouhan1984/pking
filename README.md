# Patialaking

A full-stack web application for business directory and classifieds ads for Patiala.

## Features

- Business Directory (posting, approval)
- Classified Ads (posting, approval)
- User registration/login (JWT authentication)
- Admin panel for approvals

## Structure

```
Patialaking/
  backend/
    models/
    routes/
    middleware/
    server.js
    .env.example
    package.json
  frontend/
    src/
      pages/
      components/
      App.js
      index.js
    package.json
```

## Setup Instructions

1. **Clone the repo:**
   ```
   git clone https://github.com/chouhan1984/pking.git
   cd pking
   ```

2. **Backend:**
   - Go to the backend folder: `cd backend`
   - Copy `.env.example` to `.env` and set your MongoDB URI and JWT secret.
   - Install dependencies: `npm install`
   - Start MongoDB locally or use MongoDB Atlas.
   - Run server: `node server.js`

3. **Frontend:**
   - Go to the frontend folder: `cd ../frontend`
   - Install dependencies: `npm install`
   - Start React app: `npm start`

4. **Admin User:**
   - Register a user and manually set the role to `admin` in the database for admin approval functionalities.

## Admin Approval

- Admin can log in and access `/admin-approval` route for approving businesses and ads.

---

**Need help?**  
Raise an issue in this repository!