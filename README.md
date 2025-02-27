This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

# 🏆 Tournament Dashboard

A **Full Stack Tournament Dashboard** built with **Next.js (TypeScript), Spring Boot (Java), and PostgreSQL**. This project allows users to view, manage, and interact with tournament data.

## 🚀 Tech Stack

### **Frontend:**
```txt
- Next.js (TypeScript)
- Tailwind CSS
```

### **Backend:**
```txt
- Spring Boot (Java)
- Spring Data JPA
- PostgreSQL
```

## 📌 Features
```txt
✅ List all tournaments
✅ View tournament details
✅ Secure API with CORS enabled
✅ Database integration with PostgreSQL
```

---

## 🛠️ Setup Instructions

### **1️⃣ Clone the Repository**
```sh
git clone [https://github.com/your-username/tournament-dashboard.git](https://github.com/Sid-hac/gamehok_assignment.git)
cd gamehok
```

### **2️⃣ Backend Setup (Spring Boot)**
#### **Prerequisites:**
```txt
- Java 17+
- PostgreSQL installed
- Maven installed
```

#### **Run Backend Locally:**
```sh
cd gamehok
mvn spring-boot:run
```
- The backend will start at: `http://localhost:8080`
- Ensure PostgreSQL is running and configured in `application.properties`

#### **Environment Variables (Backend)**
Create a `.env` file in the `backend` folder and set the following:
```ini
DB_URL=jdbc:postgresql://localhost:5432/tournament_db
DB_USERNAME=postgres
DB_PASSWORD=*******
```

---

### **3️⃣ Frontend Setup (Next.js)**
#### **Prerequisites:**
```txt
- Node.js 18+
- npm or yarn
```

#### **Run Frontend Locally:**
```sh
cd gamehok
npm install
npm run dev
```
- The frontend will start at: `http://localhost:3000`

---

📸 Screenshots

Home Page
([Home Page](https://github.com/Sid-hac/gamehok_assignment/blob/master/Screenshot%202025-02-27%20160012.png))

Tournament Details
([Tournament Details](https://github.com/Sid-hac/gamehok_assignment/blob/master/Screenshot%202025-02-27%20160051.png))

## 🔗 API Endpoints

```yaml
- GET  /tournaments       # Get all tournaments
- GET  /tournaments/{id}  # Get tournament by ID
```

---

## 🤝 Contributing
```txt
Feel free to fork this repository and submit a pull request with improvements!
```

---

## 📄 License
```txt
This project is open-source and available under the MIT License.
```

---

## 🎯 Contact
```yaml
Author: Siddhant Kamble
GitHub: Sid-hac (https://github.com/Sid-hac)
Email: sidengineer.014@gmail.com
```



To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
