# E-learning Plataform (microfrontends + mmicroservices)

This is an **online learning plataform** projec developed as an MVP, using a **modern architecture** with:

- **Microfrontends** (Next.js/React)

- **Microservices** (Spring Boot)

- **AWS Deployment** (Amplify, ECS, RDS, API Gateway, S3)

- **CI/CD** with Github Actions

---

## Project Idea

The goal is to create a **modular and scalable E-Learning Plataform**, where each feature is independent, allowing isolated deploymennts, easy maintenance, and application growt.

Main functionalities:

- **User authentication** (login, registration, password recovery)

- **Course catalog** (listing, search, and categories)

- **Interactive lessons** (video, quizzes, progress tracking)

- **Admin panel** (foor instructors to manage courses)

- **Payment and monetizaation** (integration with Stripe/ Mercado Pago)

- **Notifications and events** (for students and insctructors)

## Project Structure

```bash
e-learning-platform/
│
├── frontend/        # Microfrontends
│   ├── auth-frontend/
│   ├── catalog-frontend/
│   ├── lessons-frontend/
│   └── admin-frontend/
│
├── backend/         # Microservices
│   ├── users-service/
│   ├── courses-service/
│   ├── payments-service/
│   └── progress-service/
│
├── infra/           # Cloud and Docker configurations
│   ├── docker-compose.yml
│   └── README.md
│
└── README.md
```

If you want, i can also make a **short, catchy project description at the top** for GitHub to immediately catch attention from recruiters or coollaborators. Do you want me to do that?
