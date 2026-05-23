# Student Details Management Application

A full-stack web application developed to manage student records efficiently using CRUD (Create, Read, Update, Delete) operations. \
This project was built as an academic project to gain hands-on experience in application development, database management, containerization, CI/CD, and cloud deployment.

---
## 🚀 Features

- Add new student records
- View student details
- Update existing student information
- Delete student records
- Responsive frontend interface
- MySQL database integration
- Docker containerization
- Jenkins CI/CD pipeline integration
- OpenShift deployment support
---
## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JavaScript

### Backend & Database
- MySQL

### DevOps Tools
- Docker
- Jenkins
- OpenShift

---

## 📂 Project Architecture

Frontend UI  →  Application Logic  →  MySQL Database

                     ↓
                  Docker
                     ↓
                 Jenkins CI/CD
                     ↓
              OpenShift Deployment

---

## ⚙️ CRUD Operations

| Operation | Description |
|-----------|-------------|
| Create    | Add new student details |
| Read      | Display all student records |
| Update    | Modify existing student information |
| Delete    | Remove student records from database |

---

## 🐳 Docker Setup

### Build Docker Image

```bash
docker build -t student-details-app .
```

### Run Docker Container

```bash
docker run -p 8081:8081 student-details-app
```

---

## 🔄 Jenkins CI/CD Pipeline

The project uses Jenkins for:
- Automated build process
- Continuous Integration
- Deployment automation
- Docker image creation
- SonarQube analysis

 <img width="1920" height="1080" alt="Screenshot 2026-05-22 115535" src="https://github.com/user-attachments/assets/eba1aadf-acff-45f2-af72-b204a6cc0a03" />


---

## ☁️ OpenShift Deployment

The application is deployed using OpenShift for container orchestration and cloud-native deployment.

### Deploy Application

```bash
oc new-project student-app
oc new-app student-details-app
oc expose svc/student-details-app
```
<img width="1919" height="863" alt="Screenshot 2026-05-22 120511" src="https://github.com/user-attachments/assets/f2265a00-07c4-457c-a1fe-311a60c858fd" />

---

## 📸 Project Screenshots

<img width="1916" height="962" alt="Screenshot 2026-05-22 114956" src="https://github.com/user-attachments/assets/ad4a8e28-1c97-4c5c-8ac6-21dab8a7b51d" />

<img width="1908" height="755" alt="Screenshot 2026-05-22 115013" src="https://github.com/user-attachments/assets/b2bcb855-5bde-4e92-a863-b000f7e77d12" />

---

## 🎯 Learning Outcomes

Through this project, we gained practical experience in:

- Full-stack application development
- Database management using MySQL
- Containerization using Docker
- CI/CD pipeline automation with Jenkins
- OpenShift deployment and orchestration
- Team collaboration and project management

---

## 📌 Future Enhancements

- User authentication and authorization
- Search and filter functionality
- Role-based access control
- Cloud database integration
- Advanced UI improvements

---

## 🙏 Acknowledgement

We sincerely thank our college and faculty members for their guidance and support throughout the development of this project.

---

## 📄 License

This project is developed for academic and learning purposes.

