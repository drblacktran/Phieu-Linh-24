# Project Tasks for The Phieu Linh Project

## Frontend Tasks

### 1. Setup Project
- **Technologies:** Next.js, TailwindCSS
- **Steps:**
  - Create a new Next.js application using `npx create-next-app my-next-app`.
  - Install TailwindCSS by following the official guide.
  - Configure TailwindCSS in your Next.js project to ensure it purges unused styles in production.

### 2. Landing Page Design and Implementation
- **Technologies:** React, TailwindCSS
- **Steps:**
  - Design the layout using Figma for visual guidance.
  - Implement the layout in Next.js using React components.
  - Style the components with TailwindCSS to match the design.

### 3. Navigation Bar
- **Technologies:** React, TailwindCSS
- **Steps:**
  - Create a responsive navigation bar component using React.
  - Implement routing using Next.js’ `Link` component to handle navigation.
  - Style the navigation bar using TailwindCSS.

### 4. Members Carousel
- **Technologies:** React, TailwindCSS
- **Steps:**
  - Develop a carousel component using a React library like `react-slick`.
  - Style the carousel with TailwindCSS and add hover effects to reveal more information about each member.

### 5. Donation Section
- **Technologies:** React, TailwindCSS
- **Steps:**
  - Implement a form for donations using React state for form handling.
  - Create a dynamic leaderboard component that updates based on donation data.
  - Add toggle functionality to show/hide industry donations.

### 6. Admin Panel
- **Technologies:** React, TailwindCSS
- **Steps:**
  - Build UI components for the admin panel to manage content updates.
  - Implement image upload functionality using React.

## Backend Tasks

### 1. Setup Backend Project
- **Technologies:** Node.js, Express
- **Steps:**
  - Initialize a new Node.js project with `npm init`.
  - Install Express and set up a basic server with routes for handling requests.
  - Configure middleware for JSON parsing and error handling.

### 2. User Authentication System
- **Technologies:** Node.js, Express, MongoDB or PostgreSQL
- **Steps:**
  - Implement JWT-based authentication.
  - Set up routes for user registration and login.
  - Connect to the database to store user data securely.

### 3. Content Management System
- **Technologies:** Node.js, Express
- **Steps:**
  - Create API endpoints for CRUD operations on website content.
  - Use MongoDB or PostgreSQL to store content data, ensuring data integrity.

### 4. Donation Management
- **Technologies:** Node.js, Express, MongoDB or PostgreSQL
- **Steps:**
  - Develop endpoints to handle donation data submissions and updates.
  - Implement logic to aggregate donations and update totals in real time.

### 5. Database Design
- **Technologies:** MongoDB or PostgreSQL
- **Steps:**
  - Design the schema for users, donations, and content.
  - Set up models using Mongoose (for MongoDB) or Sequelize (for PostgreSQL).

### 6. Deployment and Maintenance
- **Technologies:** Node.js, MongoDB or PostgreSQL, possibly Docker or Heroku
- **Steps:**
  - Prepare the application for deployment.
  - Set up a CI/CD pipeline using GitHub Actions.
  - Deploy the backend to Heroku or another cloud service provider.

## Integrating CI/CD

- **Frontend CI/CD:**
  - Set up GitHub Actions to run linting and build tests on push or pull requests.
  - Configure automated deployment to Vercel or Netlify upon successful builds and tests.

- **Backend CI/CD:**
  - Use GitHub Actions for automated testing and linting.
  - Automate deployments to Heroku or another service, ensuring that the latest changes are always live and tested.