# Vibely

## Table of Contents
- About  
- Features  
- Technology Stack  
- Project Phases & Progress  
- Getting Started  
- Contact  

## About
Vibely is a MERN stack social media platform designed to foster authentic connection and community. Users can create profiles, share posts, follow others, and engage through likes, comments, and conversations. Vibely’s mission is to make digital social interaction feel personal, vibrant, and engaging.

## Features

### Core Features
- User Authentication & Authorization: Secure signup/login with JWT.
- Profile Management: Rich user profiles with bio, photo, interests.
- Post Creation & Feed: Users can create, edit, delete posts; personalized feed based on follows.
- Likes & Comments: Engage with content through reactions and threaded comments.
- Follow System: Follow/unfollow users to curate your network.
- Saved Posts & Notifications: Bookmark content and receive updates.
- Real-time Interactions: Notifications, chat, and live updates (in later phases).

## Technology Stack

### Frontend
- React  
- React Router / App-level routing  
- Tailwind CSS / Custom CSS  
- Context API or Redux (optional for complex state)  
- Axios (or fetch wrapper)  
- JWT handling in client  

### Backend
- Node.js  
- Express.js  
- Mongoose (MongoDB ODM)  
- bcrypt (password hashing)  
- jsonwebtoken (JWT authentication)  
- Socket.IO (real-time features in later phases)

### Database
- MongoDB

## Project Phases & Progress

The development of Vibely is structured into incremental phases to build a scalable, interactive social media experience.

### Phase 1: MVP Social Core (In Progress / Initial)
**Goal:** Establish user identity, content creation, and basic social graph.

**Frontend:**
- ⬜ User Registration & Login pages  
- ⬜ Profile creation & editing UI  
- ⬜ Post creation / deletion interface  
- ⬜ Feed showing posts from followed users  
- ⬜ Saved posts UI  

**Backend:**
- ⬜ User signup/login endpoints (with JWT)  
- ⬜ Profile CRUD endpoints  
- ⬜ Post CRUD endpoints  
- ⬜ Follow / unfollow endpoints  
- ⬜ Saved posts endpoint  

### Phase 2: Engagement & Discovery
**Goal:** Deepen interaction and introduce content discovery.

- ⬜ Likes & comments system  
- ⬜ Suggested users / content algorithm  
- ⬜ Notification system (non-real-time)  
- ⬜ Edit post/profile functionality  
- ⬜ Bookmarking & alerts  

### Phase 3: Real-Time & Communication
**Goal:** Add immediacy and two-way communication.

- ⬜ Real-time notifications (via Socket.IO)  
- ⬜ Chat System: Direct messaging between users with message history, typing indicators, and read receipts.  
- ⬜ Presence/online status  
- ⬜ Media upload in chat (images, GIFs)  
- ⬜ Explore / trending feed with live updates  

### Phase 4: Polish & Accessibility
**Goal:** Refine UX, add advanced conveniences, and ensure inclusivity.

- ⬜ Dark mode toggle  
- ⬜ Accessibility improvements (ARIA, keyboard nav)  
- ⬜ Progressive Web App support  
- ⬜ Performance optimizations & caching  
- ⬜ Account settings & privacy controls  

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)  
- npm or yarn  
- MongoDB (local instance or Atlas)

### 1. Clone the repository

git clone https://github.com/rajil-s/vibely.git
cd vibely
2. Install dependencies
Backend:
cd server
npm install

Frontend:
cd ../client
npm install
# or

3. Configure environment variables
Copy example env files and populate:

Backend (/server/.env):

ini
Copy
Edit
PORT=5000
MONGO_URI=
JWT_SECRET=
Frontend (/client/.env.local):


VITE_API_BASE_URL=http://localhost:5000/api
4. Start services
Start MongoDB (if local):


mongodb
Run backend:
cd server
npm run dev
# or
yarn dev
Run frontend:

cd ../client
npm run dev
# or
yarn dev
5. Access Vibely
Open your browser at http://localhost:3000

Contact
For questions, feedback, or contributions:

Email: shrestharajill11@gmail.com



License
MIT License © 2025 Rajil
