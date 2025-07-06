# 📝 User Feedback System

A modern, responsive feedback collection application built using **Express.js**, **MongoDB**, and **Bootstrap 5**.

It allows users to submit feedback through a user-friendly form and automatically sends **email notifications** to administrators. Admins can manage all submissions via a clean dashboard interface.

---

## 🚀 Features

- 📝 Interactive feedback form with simple UI  
- 📧 Email notifications to admin on each new feedback  
- 🗂️ Admin dashboard to view and manage submissions  
- 📱 Responsive design using Bootstrap 5  
- 🛡️ MongoDB database integration for secure storage  

---

## 🛠️ Tech Stack

| Layer        | Technology                                  |
|--------------|----------------------------------------------|
| Frontend     | HTML, CSS, Bootstrap 5, EJS Templating       |
| Backend      | Node.js, Express.js                          |
| Database     | MongoDB with Mongoose                        |
| Email        | Nodemailer with Gmail SMTP                   |
| Others       | dotenv for environment configs               |

---

## 📂 Project Structure

```
User_feedback_system/
│-- public/              # Static assets (CSS, JS)
│-- views/               # EJS templates for UI
│-- routes/              # Express routes (user, admin)
│-- models/              # Mongoose models (Feedback)
│-- controllers/         # Logic for routes
│-- config/              # Mail config and environment setup
│-- app.js               # Application entry point
│-- .env                 # Environment variables
│-- package.json         # Project metadata and dependencies
```

---

## ⚙️ Installation & Setup

### 🔽 1. Clone the Repository

```bash
git clone https://github.com/priti-kumari56/User_feedback_system.git
cd User_feedback_system
```

### 📦 2. Install Dependencies

```bash
npm install
```

### 🔐 3. Create a `.env` File

```ini
PORT=3000
EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-app-specific-password
ADMIN_EMAIL=admin@example.com
MONGODB_URI=mongodb://localhost:27017/feedback-app
```

> ⚠️ **Note**: Use an **App Password** from Gmail (requires 2-Step Verification) instead of your regular password.

### 🧭 4. Start MongoDB

```bash
mongod
```

> Or make sure your **MongoDB Atlas** connection string is added if you're using a cloud database.

### 🚀 5. Run the Application

```bash
node app.js
```

> Or for development with auto-reload:

```bash
npm run dev
```

### 🌐 6. Open in Browser

- User feedback form: [http://localhost:3000](http://localhost:3000)  
- Admin dashboard: [http://localhost:3000/admin](http://localhost:3000/admin)

---

## 💬 Usage

- Open the homepage and submit feedback as a user.  
- Admins can visit `/admin` to view all feedback messages.  
- Each feedback submission is stored in MongoDB and an email alert is sent to the admin.

---

## ✉️ Gmail App Password Setup

1. Enable **2-Step Verification** on your Gmail account  
2. Navigate to **Google Account → Security → App Passwords**  
3. Generate an **App Password**  
4. Use that password as `EMAIL_PASS` in your `.env` file  

---

## 🌐 Deployment

You can deploy this app using platforms like:

- [Render](https://render.com)
- [Heroku](https://heroku.com)
- [Railway](https://railway.app)

Use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for cloud database hosting.

Set your environment variables securely on the platform’s dashboard.

---

## 📦 Dependencies

```json
{
  "express": "^4.21.1",
  "mongoose": "^8.8.2",
  "nodemailer": "^6.9.9",
  "dotenv": "^16.4.5",
  "ejs": "^3.1.10",
  "body-parser": "^1.20.2"
}
```

---

## 🤝 Contributing

Feel free to **fork this repository** and submit a **pull request** for any bug fixes, enhancements, or features.

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more info.

---

## 📞 Contact

📧 Email: [pritikumari.engineer@gmail.com](mailto:pritikumari.engineer@gmail.com)  
🔗 GitHub: [@priti-kumari56](https://github.com/priti-kumari56)  
🔗 LinkedIn: [@pritiku](https://www.linkedin.com/in/pritiku)

---
