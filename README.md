```markdown

Welcome to the documentation for your MERN stack application! This repository contains the source code for the backend and frontend of your project. Below, you'll find important information on how to set up and configure your application using environment variables.

## Backend Environment Variables

Create a `.env` file in the backend directory and add the following variables:

```dotenv
# MongoDB connection URI
MONGO_URI=

# Node environment (e.g., development, production)
NODE_ENV=

# Secret key for JWT (JSON Web Tokens)
JWT_SECRET=

# Email settings for sending emails (using Office 365 in this case)
EMAIL_HOST=smtp.office365.com
EMAIL_USER=@outlook.com
EMAIL_PASS=''

# Frontend URL for CORS
FRONTEND_URL=http://localhost:3000

# Encryption key
CRYPTR_KEY=
```

Ensure to replace the placeholders with your actual values.

## Frontend Environment Variables

Create a `.env.local` file in the frontend directory and add the following variables:

```dotenv
# Backend URL for API requests
REACT_APP_BACKEND_URL=http://localhost:5000

# Cloudinary configuration for image uploads
REACT_APP_CLOUD_NAME=
REACT_APP_UPLOAD_PRESET=

# Google OAuth client ID and client secret
REACT_APP_GOOGLE_CLIENT_ID=
REACT_APP_GOOGLE_CLIENT_SECRET=
```

Again, replace the placeholders with your actual values.

## Getting Started

Follow these steps to get your MERN stack application up and running:

1. Backend Setup:

   ```bash
   cd backend
   npm install
   npm start
   ```

2. Frontend Setup:

   ```bash
   cd frontend
   npm install
   npm start
   ```

Visit `http://localhost:3000` to access the application.

## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.
