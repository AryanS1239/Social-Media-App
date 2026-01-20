# Social Media Platform (MERN Stack)

A fully functional social media application built with the MERN stack (MongoDB, Express, React, Node.js). This platform allows users to share posts, interact with friends, and manage their profiles, similar to Instagram or Facebook.

## 🚀 Features

- **User Authentication:** Secure Login and Registration system with JWT (JSON Web Tokens).
- **Social Interactions:** Users can Create, Like, Comment on, and Delete posts.
- **Follow System:** Follow and Unfollow other users to see their content in your feed.
- **Media Support:** Image uploads supported via Cloudinary.
- **Real-time UI:** Built with Redux for state management and Bootstrap 4 for responsive design.
- **Profile Management:** Users can edit their personal details and profile pictures.

## 🛠️ Tech Stack

- **Frontend:** React.js, Redux, Bootstrap 4
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Image Storage:** Cloudinary API

## 🔑 Environment Variables

To run this project, you will need to add the following environment variables to your backend configuration (or a `.env` file locally):

| Variable               | Description                              |
| :--------------------- | :--------------------------------------- |
| `MONGODB_URL`          | Connection string for MongoDB Atlas      |
| `ACCESS_TOKEN_SECRET`  | Secret key for generating access tokens  |
| `REFRESH_TOKEN_SECRET` | Secret key for generating refresh tokens |
| `CLOUD_NAME`           | Your Cloudinary Cloud Name               |
| `CLOUD_API_KEY`        | Your Cloudinary API Key                  |
| `CLOUD_API_SECRET`     | Your Cloudinary API Secret               |

## 💻 How to Run Locally

1.  **Install Dependencies:**

    ```bash
    # Install backend dependencies
    npm install

    # Install frontend dependencies
    cd client
    npm install
    ```

2.  **Start the App:**
    ```bash
    # Run both client and server
    npm run dev
    ```
