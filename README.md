# Video Streaming Web Application (MERN Stack)

## Overview

This is a full-stack video streaming web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. Users can create accounts, log in, upload their own videos, interact with public videos by commenting and reacting, manage their profiles, and administrators have access to an admin panel for content management.

## Features

* **User Authentication:** Secure registration, login, and logout functionality for users.
* **Video Upload:** Logged-in users can upload their own video content publicly.
* **Home Page:** Displays a feed of uploaded videos (implementation details of the feed might vary, e.g., latest uploads).
* **Uploads Page:** A dedicated page showcasing all the videos uploaded to the platform.
* **Single Video View:** Users can watch individual videos with details, comments, and reactions.
* **Commenting System:** Users can post comments on publicly available videos.
* **Reactions:** Users can react to videos with various emotions (like, dislike, heart, etc.).
* **Profile Page:** Displays the logged-in user's profile information and a list of videos they have uploaded.
* **Admin Panel:** A separate interface for administrators to manage users, videos, and potentially other aspects of the application.

## Technologies Used

* **Frontend:**
    * React.js
    * Redux Toolkit (for state management and API interactions with RTK Query)
    * React Router (for client-side routing)
    * Tailwind CSS (for styling)
    * React Icons (for icons)
    * React Toastify (for notifications)
    * (Potentially other libraries like video-react for video player customization)
* **Backend:**
    * Node.js
    * Express.js (for building the API)
    * MongoDB (for database)
    * Mongoose (for MongoDB object modeling)
    * jsonwebtoken (for authentication)
    * bcrypt (for password hashing)
    * cookie-parser (for handling cookies)
    * cors (for handling Cross-Origin Resource Sharing)
    * dotenv (for managing environment variables)
    * multer (for handling file uploads)
    * (Potentially other middleware for security, validation, etc.)

## Setup Instructions

Follow these steps to get the application running on your local machine:

### 1. Clone the Repository

```bash
git clone <repository_url>
cd <repository_name>
