# 🔗 URL Shortener

A full-stack URL Shortener application built with **Spring Boot**, **Spring Security (JWT)**, **React.js**, **Tailwind CSS**, and **MySQL**.  
The project allows users to shorten long URLs, manage their links, view analytics, and securely authenticate using JWT-based login and signup.

---

## 🚀 Features

- **User Authentication** (Signup & Login with JWT)
- **Shorten URLs** with unique short codes
- **Redirect Functionality** (short → original URL)
- **URL Analytics Dashboard** (track clicks, usage stats)
- **Manage URLs** (view all, update, delete)
- **Role-based Access Control**
- **Frontend Integration** (React + Tailwind CSS)
- **Secure REST APIs** (Spring Boot)
- **Dockerized Deployment**
- **Cloud Database Support**
- **Custom Domain & Path Routing**

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Security + JWT
- Spring Data JPA + Hibernate
- MySQL
- Docker

### Frontend
- React.js
- Tailwind CSS
- Axios

### Deployment
- Docker
- Cloud Database (MySQL)
- Free Hosting Platforms (Render / Railway / Netlify)

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/harsharb05/URL-shortener-project.git
cd URL-shortener-project
```

### 2. Backend Setup
```bash
cd backend
mvn clean install
mvn spring-boot:run
```

- Configure `application.properties`:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/urlshortener
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
jwt.secret=your_jwt_secret_key
```

Backend will run on: `http://localhost:8080`

### 3. Frontend Setup
```bash
cd frontend
npm install
npm start
```

Frontend will run on: `http://localhost:3000`

---

## 📊 Dashboard Features

- View all shortened URLs
- Track click analytics (per link)
- Filter by user
- Responsive & modern UI with Tailwind CSS

---

## 🐳 Docker Deployment

```bash
# Build and run using docker-compose
docker-compose up --build
```

---

## 🌍 Deployment

- **Backend**: Deploy on Render / Railway / Heroku / AWS / Dockerized VPS  
- **Frontend**: Deploy on Netlify / Vercel  
- **Database**: Use MySQL Cloud (Railway / AWS RDS)
---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify for your own projects.

---

## 👨‍💻 Author

- GitHub: [@harsharb05](https://github.com/harsharb05)  
