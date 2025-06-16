# Morphe — Fitness Application with Machine Learning Integration

> **Morphe** is a unified fitness platform combining a modern backend, intelligent machine learning features, and a responsive Flutter frontend to provide personalized user experiences.  
> This metarepository brings together all components under one roof for easier development, testing, and deployment.

---

## 🧩 Projects Included

1. [`morphe-backend`](morphe-backend)  
   - **Backend API** built using **Django**.
   - RESTful endpoints for managing:
     - User accounts
     - Workout logs
     - Goals and progress tracking
   - Fully containerized with **Docker** for easy deployment.

2. [`morphe-ml-service`](morphe-ml-service)  
   - **Machine Learning Microservice** powered by **FastAPI**.
   - Purpose:
     - Analyze user data
     - Generate workout recommendations
     - Integrate model inference into the ecosystem

3. [`morphe-frontend`](morphe-frontend)  
   - **Frontend mobile application** built with **Flutter and Dart**.
   - Designed to be the main UI for users.
   - Integrates with both Django backend and FastAPI ML services.
   - Cross-platform (iOS / Android).

> 💡 Each component can be developed independently but are integrated here for collaborative development and end-to-end testing.
