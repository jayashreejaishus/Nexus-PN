# Pronet a proffesional networking platform

A full-stack professional networking platform inspired by LinkedIn, where users can connect, share posts, interact with content, and manage their professional profiles.

## Live Demo

- **Live Preview:https://nyx-nexus.netlify.app

## Features

- User Authentication and Authorization
- User Registration and Login
- Create, Edit, and Delete Posts
- Like and Comment on Posts
- User Profiles and Profile Management
- View and Interact with Other Users
- Responsive User Interface
- Real-time User Interactions
- Secure Data Management

## Tech Stack

### Frontend
- React.js / Next.js
- TypeScript / JavaScript
- Tailwind CSS
- HTML5
- CSS3

### Backend
- Node.js
- Express.js / Next.js API Routes

### Database
- MongoDB

### Authentication
- Clerk / JWT Authentication

### Deployment
- Vercel

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- Git
- MongoDB account or local MongoDB installation

### Installation

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate to the project directory**

```bash
cd LinkedIn-Clone
```

**3. Install dependencies**

```bash
npm install
```

**4. Configure Environment Variables**

Create a `.env.local` file in the root directory and add the required environment variables.

```env
MONGO_URI=YOUR_MONGODB_CONNECTION_STRING

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=YOUR_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY=YOUR_CLERK_SECRET_KEY

CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_NAME
CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET=YOUR_CLOUDINARY_API_SECRET
```

*Replace the placeholders with your actual credentials. Never upload your secret keys to GitHub.*

**5. Start the development server**

```bash
npm run dev
```

**6. Open the application
