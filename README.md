# nodejs-express-mongodb-bootcamp

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Pug](https://img.shields.io/badge/Pug-A86454?style=for-the-badge&logo=pug&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

This repository is a comprehensive collection of all projects, exercises, and architectural patterns completed during Jonas Schmedtmann's **"Node.js, Express, MongoDB & More: The Complete Bootcamp"** on Udemy. It documents my journey from understanding the Node.js runtime and core modules to building and deploying a full production-ready RESTful API with authentication, security, and payments.

## 🚀 Technical Core
*   **Runtime & Framework:** Node.js, Express.js
*   **Database & ODM:** MongoDB, Mongoose
*   **Authentication & Security:** JWT, bcrypt, rate limiting, data sanitization, Helmet, CORS
*   **Templating & Frontend:** Pug templates, Vanilla JS on the client
*   **File Uploads & Images:** Multer, Sharp
*   **Emails & Payments:** Nodemailer, SendGrid, Stripe
*   **Error Handling & Logging:** Global error handler, custom AppError, Morgan
*   **Deployment & DevOps:** Git, environment configs, Heroku/Render deployment
*   **Development Workflow:** Git with Conventional Commits, ESLint + Prettier

---

## 📚 Course Progress

| Section | Project / Topic              | Status         |
|---------|------------------------------|----------------|
| 01      | Node.js Fundamentals         | Completed ✅   |
| 02      | How Node.js Works            | Completed ✅   |
| 03      | Asynchronous JavaScript      | Completed ✅   |
| 04      | Building a REST API (Natours) | In Progress   |
| 05      | Express & Middleware         | Not Started    |
| 06      | MongoDB & Mongoose           | Not Started    |
| 07      | Error Handling               | Not Started    |
| 08      | Authentication & Security    | Not Started    |
| 09      | Advanced Features (Uploads, Emails, Payments) | Not Started |
| 10      | Deployment                   | Not Started    |
| 11      | Building a Full App (Natours) | Not Started   |

---

## 📁 Repository Structure

This repository follows the same structure as Jonas's original course repo:

- `01-node-basics/` — Node.js core modules, file system, streams
- `02-how-node-works/` — Event loop, libuv, threads
- `03-async-javascript/` — Callbacks, promises, async/await
- `04-natours/` — Main project: REST API for a tour booking app
  - `controllers/`
  - `models/`
  - `routes/`
  - `utils/`
  - `public/`
  - `views/` (Pug templates)
- `05-express/` — Express routing and middleware
- `06-mongodb-mongoose/` — Data modeling and CRUD
- `07-error-handling/` — Global error handling patterns
- `08-auth-security/` — JWT auth, roles, security best practices
- `09-advanced-features/` — Uploads, emails, payments
- `10-deployment/` — Production deployment setup

---

## 🚀 How to Run a Project

```bash
# Navigate to the project folder
cd 04-natours

# Install dependencies
npm install

# Create a .env file and add your config (DB, JWT, etc.)
# See .env.example for the required variables

# Start the development server
npm run start:dev

![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Pug](https://img.shields.io/badge/Pug-A86454?style=for-the-badge&logo=pug&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
