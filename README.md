# Work Quanta - Task Management System

## Application Name
Work Quanta

## Contributors
- Ishaan Mittal (https://github.com/kalicharm21)
- Veedushi Jain (https://github.com/Veedushi2101)

## Introduction
Work Quanta is a comprehensive task management system designed to help teams and individuals organize their work efficiently. It offers real-time collaboration, task tracking, and prioritization to ensure seamless project management.

## Description
Work Quanta is focused on providing a streamlined workflow for:
- Teams handling multiple projects.
- Freelancers managing personal tasks.
- Startups coordinating team efforts.
- Enterprises seeking to track project progress.

It integrates features such as role-based permissions, secure authentication, and real-time updates to enhance productivity.

## Screenshots
![WhatsApp Image 2025-03-24 at 12 48 23_97a4b681](https://github.com/user-attachments/assets/3ebc271d-a0f6-46bb-94ad-e79d14770077)
![WhatsApp Image 2025-03-24 at 12 48 23_7df99942](https://github.com/user-attachments/assets/7c5783c3-249e-4fbd-9faa-50fb0f56a115)

---

## Tech Stack
- Frontend: Next.js, Tailwind CSS, TypeScript
- Backend: Node.js, Express, MongoDB, React
- Authentication: JWT, bcrypt, nodemailer
- Charts: Recharts

---

## Getting Started
### Prerequisites
- Node.js (v18+)
- MongoDB
- Git

### Installing Git
1. Download Git from [here](https://git-scm.com/).
2. Install Git by following the installation wizard.
3. Verify installation:
   ```bash
   git --version
   ```

### Clone the Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/Work-Quanta.git
   cd Work-Quanta-main
   ```

### Installation
1. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```
2. Install dependencies for the frontend:
   ```bash
   cd ../client
   npm install
   ```

### Configuration
1. Add these variables in your .env file 
```plaintext
* MONGO_URI=your_mongo_uri
* JWT_SECRET=secret or anything random
* CLIENT_URL=http://localhost:3000 or any localhost port that you are using
* PORT=8000
   ```

2. Create a `.env` file in the `client` directory with the following:
   ```plaintext
   NEXT_PUBLIC_API_URL=http://localhost:5000
   ```

### Running the Application
1. Start the backend:
   ```bash
   cd backend
   npm start
   ```

2. Start the frontend:
   ```bash
   cd ../client
   npm run dev
   ```

The frontend will run at `http://localhost:3000` and the backend at `http://localhost:5000`.

---

## Project Structure
```
Work-Quanta-main
├── backend
│   ├── src
│   │   ├── controllers
│   │   ├── db
│   │   ├── helpers
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   └── views
└── client
    ├── app
    ├── components
    ├── context
    ├── hooks
    ├── providers
    ├── public
    └── utils
```

---

## API Endpoints
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Authenticate user
- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create a task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task

---

## Contributing
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`.
3. Commit changes: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Create a Pull Request.

Happy coding! 🚀

