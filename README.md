# energy-optimization-platform
Scalable Energy Resource Optimization Platform built with Java Spring Boot, Angular, Docker, and Kubernetes. Simulates demand forecasting, resource scheduling, and cost optimization for energy transition projects.

A full-stack system designed to optimize **energy resource allocation and scheduling**.  
Built with **Spring Boot (backend)**, **Angular (frontend)**, and deployed using **Docker & Kubernetes** for scalability.  

This project simulates how energy providers can balance **production, consumption, and storage** to reduce costs and improve efficiency — directly aligned with the energy transition goals.

---

## 🚀 Features
- **Energy Demand Forecasting**: REST API endpoints to simulate demand curves.  
- **Resource Scheduling**: Optimize allocation of renewable vs non-renewable sources.  
- **Cost Optimization**: Apply algorithms to minimize operational costs.  
- **Visualization Dashboard**: Angular frontend showing demand, supply, and optimization results.  
- **Authentication & Authorization**: Role-based access using **Keycloak SSO**.  
- **Scalable Architecture**: Microservices with **Spring Boot**, **REST APIs**, and **PostgreSQL**.  
- **CI/CD Ready**: Jenkins pipeline with SonarQube quality checks and Dockerized deployment.  

---

## 🏗️ Tech Stack
- **Backend**: Java 17, Spring Boot, Spring Data JPA, Hibernate, REST APIs  
- **Frontend**: Angular 15, TypeScript, Bootstrap  
- **Database**: PostgreSQL  
- **Optimization**: Linear programming (via OptaPlanner or OR-Tools integration)  
- **Messaging**: RabbitMQ / Kafka  
- **CI/CD**: Jenkins, SonarQube, GitHub Actions  
- **Containerization**: Docker, Kubernetes  
- **Cloud Ready**: AWS (EKS, RDS)  

---
## ⚙️ Running Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/builder-management-system.git
cd builder-management-system
2. Backend Setup
bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
Backend runs on: http://localhost:8080

3. Frontend Setup
bash
cd frontend
npm install
npm start
Frontend runs on: http://localhost:4200

4. Docker Compose (Optional)
bash
docker-compose up --build
This spins up backend, frontend, and PostgreSQL together.

5. Kubernetes Deployment (Optional)
bash
kubectl apply -f k8s/
Deploys services to your cluster (tested with Minikube and AWS EKS).

✅ Scalability Notes
Stateless microservices allow horizontal scaling.

PostgreSQL can be swapped with AWS RDS for production.

RabbitMQ/Kafka integration ensures reliable event-driven communication.

CI/CD pipeline ensures automated builds, tests, and deployments.

📊 Future Enhancements
Add machine learning module for resource optimization.

Integrate Grafana + Prometheus for monitoring.

Expand to multi-tenant architecture for multiple builders.

👨‍💻 Author
Mohamed — Senior Software Engineer | Java Technical Lead Passionate about building scalable enterprise systems with a focus on quality, performance, and collaboration.
