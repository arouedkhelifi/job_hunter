# Job Hunter 🎯

A full-stack job application tracking system built with TypeScript. Job Hunter helps job seekers organize their job search process, track applications, and manage interviews all in one place.

## Features ✨

- **Job Application Tracking**: Keep track of all your job applications in one centralized location
- **Application Status Management**: Track the status of each application (Applied, Interview, Offer, Rejected)
- **Company Information**: Store details about companies you're applying to
- **Dashboard Analytics**: Visualize your job search progress
- **Search & Filter**: Quickly find specific applications using advanced filters
- **Responsive Design**: Access your job hunt dashboard from any device

  📸 App Screenshots
you can see the app screenshots in the screenshots folder

## Tech Stack 🛠️

### Frontend (Client)
- **TypeScript** (82.8%)
- **React** 
- Modern UI/UX design
- Responsive layout

### Backend
- **TypeScript**
- **Node.js** with **Express** 
- RESTful API architecture
- Database integration (MongoDB/PostgreSQL/MySQL)

### Additional Technologies
- **JavaScript** (15.9%)
- **CSS** (1.3%)
- Authentication (JWT/OAuth)
- Password encryption

## Prerequisites 📋

Before running this application, make sure you have the following installed:

- **Node.js** (v16 or higher)
- **npm** or **yarn**
- **Database** (MongoDB)
- **Git**

## Installation 🚀

### 1. Clone the repository

```bash
git clone https://github.com/arouedkhelifi/job_hunter.git
cd job_hunter
```

### 2. Install dependencies

Install root dependencies:
```bash
npm install
```

Install backend dependencies:
```bash
cd backend
npm install
cd ..
```

Install client dependencies:
```bash
cd client
npm install
cd ..
```

### 3. Environment Configuration

Create a `.env` file in the **backend** directory:

```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Database Configuration
DATABASE_URL=your_database_connection_string
DB_NAME=job_hunter

# Authentication
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=7d

# Optional: Email Configuration
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your_email@gmail.com
EMAIL_PASSWORD=your_email_password
```

Create a `.env` file in the **client** directory:

```env
REACT_APP_API_URL=http://localhost:5000/api
# Or your framework's equivalent
```

### 4. Database Setup

Set up your database and run migrations:

```bash
cd backend
npm run migrate
# or
npm run db:setup
```

## Running the Application 🏃

### Development Mode

Run both backend and client concurrently from the root directory:

```bash
npm run dev
```

Or run them separately:

**Backend:**
```bash
cd backend
npm start
```
Backend will run on `http://localhost:5000`

**Client:**
```bash
cd client
npm run dev

```
Frontend will run on `http://localhost:3000`

## Project Structure 📁

```
job_hunter/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── config/
│   │   └── utils/
│   ├── package.json
│   └── tsconfig.json
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   │   └── utils/
│   ├── package.json
│   └── tsconfig.json
├── package.json
├── package-lock.json
└── README.md
```

## Contributing 🤝

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contributors

- [Bacem Touil](https://github.com/Bacemtouil-ZB) - [@Bacemtouil-ZB](https://github.com/Bacemtouil-ZB)
- [yahyazarred](https://github.com/yahyazarred) - [@yahyazarred](https://github.com/yahyazarred)
- [Baxem8](https://github.com/Baxem8) - [@Baxem8](https://github.com/Baxem8)

⭐ If you find this project helpful, please give it a star on GitHub!

