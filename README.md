![NavbarGit](frontend/src/assets/images/NavbarGit.png)

# 🚗 Parking Management System

Complete parking management project developed with **Spring Boot** and an integrated front end.
It supports vehicle registration, entry and exit control, reports, and user authentication.

---

## ✨ Features

### Back-end
- Vehicle registration (license plate, model, and color)
- Entry and exit records with automatic parking duration calculation
- Daily report generation (PDF/CSV)
- JWT authentication for secure access

### Front-end
- Responsive web interface (React)
- User login and registration
- Dashboard with real-time metrics
- Forms for vehicle registration and payments

---

## 🔧 Technologies Used

### Back-end
- Java 21
- Spring Boot 3.2
- Spring Security
- Spring Data JPA
- H2 Database (testing)
- Lombok
- OpenAPI (Swagger)

### Front-end
- React 18
- Axios (API integration)
- Bootstrap 5

### Testing
- Mockito
- Pitest (mutation testing)

---

## 🚀 Setup and Execution

### Prerequisites
- Java 21
- Node.js 18+
- MySQL 8+ (optional for production)

### Back-end

Clone the repository:
```bash
git clone https://github.com/lokesh95225/Parking-Management-System.git
```

Enter the back-end directory:
```bash
cd Parking-Management-System/backend
```

Run the application by starting `DemoAuthAppApplication`.

### Front-end

Enter the front-end directory:
```bash
cd Parking-Management-System/frontend
```

Install the dependencies:
```bash
npm install
```

Start the application:
```bash
npm start
```

Open `http://localhost:3000` in your browser.

## 🔒 Authentication
Authentication is protected by JWT. The following endpoints are available:
- **Registration:** `POST /api/auth/register`
- **Login:** `POST /api/auth/login`

Register on the registration page and then log in to access the application features.

---

## 📊 Quality
![Code Coverage](https://img.shields.io/badge/coverage-100%25-brightgreen)
![Killed Mutants](https://img.shields.io/badge/mutants-99%25-brightgreen)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)

---

## 📄 API Documentation
Visit `http://localhost:8080/swagger-ui.html` after starting the back end.
