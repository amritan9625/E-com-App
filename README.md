# E-com-App

A full-stack e-commerce application built with **Spring Boot** for the backend and **React (Vite)** for the frontend.  
The project demonstrates CRUD operations, product management, and a responsive UI.

---

## 📂 Project Structure

```
E-com-App/
│
├── Backend/      # Spring Boot backend (REST APIs, business logic, DB integration)
│   ├── src/
│   ├── pom.xml
│   └── ...
│
├── Interface/    # React (Vite) frontend (UI, components, routing)
│   ├── src/
│   ├── package.json
│   └── ...
│
└── README.md     # Project documentation
```

---

## 🚀 Tech Stack

- **Backend:** Spring Boot, Spring Web, Spring Data JPA, H2/MySQL (choose based on your setup), Lombok  
- **Frontend:** React.js (Vite), Tailwind CSS / CSS Modules (if used)  
- **Database:** H2 (in-memory) or MySQL (persistent)  
- **Build Tools:** Maven (backend), npm (frontend)

---

## ⚙️ Backend Setup (Spring Boot)

1. Navigate to the backend folder:
   ```bash
   cd Backend
   ```

2. Build and run the project:
   ```bash
   ./mvnw spring-boot:run
   ```
   or if using Maven globally:
   ```bash
   mvn spring-boot:run
   ```

3. The backend will start at:
   ```
   http://localhost:8080
   ```

---

## 💻 Frontend Setup (React + Vite)

1. Navigate to the frontend folder:
   ```bash
   cd Interface
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. The frontend will start at:
   ```
   http://localhost:5173
   ```

---

## 🔗 API Endpoints (Examples)

- `GET /api/products` → Get all products  
- `POST /api/products` → Add a new product  
- `PUT /api/products/{id}` → Update product details  
- `DELETE /api/products/{id}` → Delete a product  

---

## 🛠 Features

- Add, update, and delete products  
- Shopping cart with checkout  
- Responsive UI with navigation  
- RESTful APIs with Spring Boot  
- Frontend-backend integration

---

## 📌 Future Improvements

- User authentication & authorization (JWT)  
- Payment gateway integration  
- Order history and tracking  
- Deployment on cloud platforms (AWS, Vercel, etc.)

---

