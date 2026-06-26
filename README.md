````markdown
# 💼 Job Portal - MERN Stack

A modern and responsive **Job Portal Application** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This platform connects job seekers with employers through a secure and user-friendly interface.

The application provides **JWT Authentication**, **Role-Based Authorization**, **Resume Upload**, **Company Management**, and **Job Application Tracking** with a clean UI built using **Tailwind CSS** and **shadcn/ui**.

---

## 🚀 Features

### 👨‍💼 Job Seeker

- User Registration & Login
- Secure Authentication
- Update Profile
- Upload Resume
- Browse Jobs
- Search Jobs
- Filter Jobs
- View Job Details
- Apply for Jobs
- Track Applied Jobs
- View Company Details

---

### 🏢 Employer

- Employer Registration & Login
- Create Company
- Update Company Profile
- Upload Company Logo
- Post New Jobs
- Edit Jobs
- Delete Jobs
- View Posted Jobs
- Manage Applicants
- Accept / Reject Applications

---

### 🔐 Authentication & Security

- JWT Authentication
- HTTP-Only Cookie Authentication
- Password Hashing (bcryptjs)
- Protected Routes
- Role-Based Authorization
- Environment Variables
- Secure API Endpoints

---

## 🛠️ Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- shadcn/ui
- Redux Toolkit
- Redux Persist
- React Router DOM
- Axios
- Lucide React
- Sonner (Toast Notifications)

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcryptjs
- Multer
- Cloudinary
- Cookie Parser
- CORS
- dotenv

### Development Tools

- Git
- GitHub
- npm
- Visual Studio Code
- ESLint
- Prettier

---

## 📁 Project Structure

```text
Job-Portal
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   ├── server.js
│   └── package.json
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── hooks
│   │   ├── pages
│   │   ├── redux
│   │   ├── utils
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── README.md
└── .gitignore
````

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/job-portal.git

cd job-portal
```

---

### 2. Install Backend

```bash
cd backend

npm install
```

Create a `.env` file inside the backend folder.

```env
PORT=8000

MONGO_URI=your_mongodb_connection_string

SECRET_KEY=your_jwt_secret

CLOUD_NAME=your_cloudinary_name
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret

FRONTEND_URL=http://localhost:5173
```

Run the backend server.

```bash
npm run dev
```

---

### 3. Install Frontend

```bash
cd frontend

npm install

npm run dev
```

---

## 🔑 Environment Variables

```env
PORT=

MONGO_URI=

SECRET_KEY=

CLOUD_NAME=

API_KEY=

API_SECRET=

FRONTEND_URL=
```

---

## 📡 API Routes

### Authentication

```
POST   /api/v1/user/register
POST   /api/v1/user/login
POST   /api/v1/user/logout
GET    /api/v1/user/profile
PUT    /api/v1/user/profile/update
```

### Company

```
POST   /api/v1/company/register
GET    /api/v1/company
GET    /api/v1/company/:id
PUT    /api/v1/company/update/:id
```

### Jobs

```
POST   /api/v1/job/post
GET    /api/v1/job/get
GET    /api/v1/job/getadminjobs
GET    /api/v1/job/get/:id
PUT    /api/v1/job/update/:id
DELETE /api/v1/job/delete/:id
```

### Applications

```
POST   /api/v1/application/apply/:id
GET    /api/v1/application/get
GET    /api/v1/application/:id/applicants
PUT    /api/v1/application/status/:id/update
```

---

## 🔄 Application Workflow

### Job Seeker

```
Register/Login
      │
      ▼
Browse Jobs
      │
      ▼
Search & Filter
      │
      ▼
View Job Details
      │
      ▼
Apply for Job
      │
      ▼
Track Application Status
```

### Employer

```
Register/Login
      │
      ▼
Create Company
      │
      ▼
Post Job
      │
      ▼
Manage Jobs
      │
      ▼
Review Applicants
      │
      ▼
Accept / Reject Applications
```

---

## 🔒 Security Features

* JWT Authentication
* HTTP-Only Cookies
* Password Encryption
* Protected Routes
* Role-Based Access Control
* Input Validation
* Secure File Uploads
* Environment Variables

---

## ✨ Future Improvements

* Email Verification
* Forgot Password
* Refresh Token Authentication
* Google Login
* LinkedIn Login
* Resume Parsing
* Saved Jobs
* Job Recommendations
* Real-Time Notifications
* Chat System
* Interview Scheduling
* Admin Dashboard
* Analytics Dashboard
* Docker Support
* CI/CD Pipeline
* Unit Testing
* Dark Mode

---

## 📸 Screenshots

Add screenshots of your application here.

* Home Page
* Login Page
* Register Page
* Student Dashboard
* Recruiter Dashboard
* Company Management
* Job Listings
* Job Details
* Applicants Page

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 👨‍💻 Author

**Nirajan Lama**

Full Stack MERN Developer

---

# ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

```
```
