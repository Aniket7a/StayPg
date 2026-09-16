# Engineering Journal: Hasrat Aulakh (1024030991)
**Role:** Backend Developer (Node.js, Express.js, REST APIs, JWT Auth, Socket.io)  
**Project:** StayPG (StayOG) — Verified PG & Hostel Discovery Platform  
**Course:** UCS503 - Software Engineering Project (2026–2027)

---

## Weekly Progress Log

### Week 1–2: Architecture & API Design
- Defined REST API endpoints and data schemas.
- Outlined 3-tier controller-service-repository backend structure.

### Week 3–6: Authentication & Role Guarding
- Implemented JWT access and refresh token rotation with HTTP-only cookies.
- Added bcrypt.js password hashing (salt rounds 12).
- Designed role-guard middleware enforcing Student / Owner / Admin access boundaries.

### Week 7–9: Booking State Machine & Review Gating
- Implemented booking state machine (PENDING -> CONFIRMED -> COMPLETED).
- Engineered review eligibility gate restricting review submission to completed bookings.
- Integrated Cloudinary multipart image upload pipeline with Multer.

### Week 10–12: Real-Time Messaging & API Optimization
- Implemented Socket.io gateway with dedicated `io.use()` handshake JWT verifier.
- Added room isolation and event emission for live booking updates and chat messages.
- Achieved backend unit test coverage >= 78.4% using Jest and Supertest.
