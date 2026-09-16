# Engineering Journal: Aniket (1024030063)
**Role:** Project Lead & Full Stack Developer (Node.js/Express REST APIs, React.js, JWT Auth, Redux Toolkit, Socket.io, Deployment)  
**Project:** StayPG (StayOG) — Verified PG & Hostel Discovery Platform  
**Course:** UCS503 - Software Engineering Project (2026–2027)

---

## Weekly Progress Log

### Week 1–2: Project Lead & Architectural Inception
- Spearheaded requirement gathering, problem formulation, and project scope definition.
- Coordinated team task allocation across the 12-week Master Gantt schedule.
- Designed system flow, Figma wireframes, and API contract specifications.

### Week 3–4: Backend Core Setup & Authentication Engine
- Architected Node.js (v20 LTS) and Express.js REST API skeleton.
- Implemented dual-token JWT authentication (access + refresh cookies) with bcrypt credential hashing (cost factor 12).
- Set up route middlewares and error handlers across isolated student, owner, and admin roles.

### Week 5–6: Core Backend & Property CRUD APIs
- Engineered Property Listing CRUD endpoints (`/api/listings`).
- Co-developed Cloudinary streaming uploads with Multer.
- Collaborated on MongoDB Atlas 2dsphere index integration for campus proximity search.

### Week 7–8: Frontend Architecture & State Management
- Scaffolded React 18 single-page application with Tailwind CSS and React Router.
- Implemented global state management using Redux Toolkit and authenticated Axios interceptors.
- Developed core views: Landing Page, Search Grid, Property Details, and Owner Dashboard.

### Week 9–10: Booking Lifecycle, Review Gating & Real-Time Chat
- Implemented booking state machine transitions (`PENDING` -> `CONFIRMED` -> `COMPLETED`).
- Engineered data-layer review eligibility gate for completed stays.
- Developed real-time Socket.io chat gateway with `io.use()` handshake JWT verifier.

### Week 11–12: Multi-Tier Testing, Cloud Deployment & Delivery
- Authored Jest unit test suites and Supertest integration tests.
- Configured production deployment pipeline on Render and Vercel.
- Prepared project evaluation presentations and final documentation deliverables.
