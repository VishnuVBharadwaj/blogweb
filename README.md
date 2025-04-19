

- **User Authentication**:
  - Signup and login with JWT token authentication
  - Secure password hashing
  - Protected routes for authenticated users

- **Blog Management**:
  - Create new blog posts with titles, content, and optional images
  - Read all blog posts with pagination
  - Update and delete your own posts
  - Preview of posts in a list format

- **Modern UI**:
  - Responsive design for all device sizes
  - Clean, minimalist interface
  - Beautiful typography and spacing

## Tech Stack

- **Frontend**:
  - React with TypeScript
  - React Router for navigation
  - React Hook Form for form management
  - Tailwind CSS for styling
  - shadcn/ui components

- **Backend** (to be implemented):
  - Node.js with Express
  - MongoDB for database
  - JWT for authentication
  - bcrypt for password hashing

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm run dev
   ```

## Project Structure

- `/src/components`: Reusable UI components
- `/src/contexts`: React context for state management
- `/src/lib`: Utility functions and API calls
- `/src/pages`: Individual page components
- `/src/types`: TypeScript interfaces and types

## Authentication Flow

The application uses JWT (JSON Web Tokens) for authentication:
1. User registers or logs in
2. Server validates credentials and returns a JWT
3. Token is stored in localStorage and added to API requests
4. Protected routes check for valid token before rendering

## Next Steps

- Implement backend API with Express and MongoDB
- Add comment functionality to blog posts
- Implement user profile management
- Add rich text editor for blog content
