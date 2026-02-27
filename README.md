# URL-Management-API

**Tech Stack** : Node.js, Express.js(Backend), MongoDB, REST API

URL shortening service built with Node.js and MongoDB featuring expiration control, analytics tracking, rate-limited REST APIs and modular backend architecture.
This application provides a RESTful API for generating and managing short URLs.
It is designed with scalability, clean architecture, and future product expansion in mind.


Build a well-structured backend system

Apply REST API best practices

Implement database indexing and validation

Enforce production-level security fundamentals
**Feature:**
- Generate short URLs
- Custom alias support
- Expiration-based link control
- Click tracking with metadata
          Timestamp
          IP address
          User-Agent
- Rate limiting to prevent abuse
- Centralized error handling
- Modular MVC-style architecture

**Architecture**:
  |
  | ----> routes/       → API routes
  | ----> controllers/  → Request handling logic
  | ----> models/       → MongoDB schema
  | ----> middlewares/  → Validation & rate limiting
  | ----> utils/        → Short code generation logic

**Packages :**
1. Node.js
2.  MongoDB (Mongo Atlas)
3. Mongoose
4. Express.js
5. Morgan (HTTP logging)



