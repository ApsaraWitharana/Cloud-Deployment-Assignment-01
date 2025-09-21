# Cloud-Deployment-Assignment-01

# 📘 Enterprise Cloud Architecture

## 🚀 Project Overview  
**Enterprise Cloud Architecture** is a microservices-based demo application designed for educational institutions.  
It demonstrates modern **microservices patterns** such as service separation, independent data stores, file/media handling service, developer-friendly local setup, and deployment-ready configurations for **multi-cloud platforms (AWS & GCP)**.

---

## 👩‍🎓 Student Details  
- **Name**: W.P. Sachini Apsara  
- **Student Registration Number**: 2301682022  
- **Email**: asachini095@gmail.com  

---

## 🔑 Key Services  

- **Course Service** — Spring Boot + MySQL (**Port 8081**)  
- **Student Service** — Spring Boot + MongoDB (**Port 8082**)  
- **Media Service** — Spring Boot (file uploads) (**Port 8083**)  
- **Frontend** — React + TypeScript (Vite + Material-UI) (**Port 5173**)  

🎥 **Demo Video**: *Watch Project*  

---

## 🧰 Technology Stack  

- **Backend**: Spring Boot 3.5.5, Java 21, Maven  
- **Frontend**: React 18, TypeScript, Vite, Material-UI  
- **Datastores**: MySQL (relational), MongoDB (document)  
- **Cloud**: AWS & GCP ready configuration  
- **Build & Run**: Maven, npm/yarn, optional Docker  

---

## ⚙️ Prerequisites  

Ensure you have the following installed:  
- Java 21 (JDK 21)  
- Node.js 18+  
- Maven 3.8+  
- MySQL server  
- MongoDB  
- (Optional) Docker & Docker Compose  

---

## 📝 Quick Start (One-Minute Copy-Paste)  

```bash
# Clone repository
git clone https://github.com/ApsaraWitharana/Cloud-Deployment-Assignment-01.git
cd Cloud-Deployment-Assignment-01

# Build backend services
mvn clean install -DskipTests

# Start services
cd course-service && mvn spring-boot:run
cd ../student-service && mvn spring-boot:run
cd ../media-service && mvn spring-boot:run

# Start frontend
cd ../frontend-app
npm install && npm run dev
```

## Screenshort

![WhatsApp Image 2025-09-21 at 20 15 13_ebf728e9](https://github.com/user-attachments/assets/c3463b01-1151-4596-b27a-053ab1d54e22)

![WhatsApp Image 2025-09-21 at 20 15 26_b188fda3](https://github.com/user-attachments/assets/3fd66293-0949-40e2-a107-ce0fddbd5130)

![WhatsApp Image 2025-09-21 at 20 15 42_6dc40792](https://github.com/user-attachments/assets/02269020-2750-40f1-8556-4fddb93c088c)

![WhatsApp Image 2025-09-21 at 20 15 56_1b0d7231](https://github.com/user-attachments/assets/be35ee26-5c93-448c-9d59-d3b0c19622e0)

### Screen Video


## 💜License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or collaboration:
- **Author:** [Sachini Apsara](https://github.com/ApsaraWitharana)
  
<div align="center">
    © 2025 All Rights Reserved, Designed By Sachini Apsara
</div>

⭐ **Feel free to contribute, star the repo, and explore more!**
