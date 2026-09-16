# Engineering Journal: Ajay Bhatti (1024030989)
**Role:** Database & DevOps Lead (MongoDB Atlas, 2dsphere Geo-Indexing, Cloudinary, Deployment)  
**Project:** StayPG (StayOG) — Verified PG & Hostel Discovery Platform  
**Course:** UCS503 - Software Engineering Project (2026–2027)

---

## Weekly Progress Log

### Week 1–2: Database Schema & Entity Modeling
- Designed relational ER diagram and normalized collection schemas in MongoDB.
- Mapped relationships across Users, Listings, Bookings, Reviews, and Messages.

### Week 3–6: Geospatial Indexing & Query Engineering
- Configured MongoDB Atlas 2dsphere geospatial index on property GeoJSON coordinates.
- Benchmarked `$geoNear` aggregation pipeline against in-memory Haversine (reduced latency to 214 ms).
- Created compound indexes for filtered search predicates.

### Week 7–9: Cloud Services & Storage Pipeline
- Set up Cloudinary account and image transformation pipelines.
- Configured environment variables, CORS policies, and rate-limiting rules.

### Week 10–12: Cloud Hosting & CI/CD Pipeline
- Configured deployment on Render/Railway for backend and Vercel/Netlify for frontend.
- Automated testing via GitHub Actions CI workflows.
