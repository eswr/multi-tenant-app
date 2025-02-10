# multiTenantApp

Prompt: implementing your HIPAA‑compliant, multi‑tenant web application infrastructure using code

Overview of the Stack:
• Backend API: Elixir/Phoenix
• Client Apps: Three Next.js/React apps (Admin Dashboard, Caregiver App, Guardian App)
• Database: PostgreSQL (managed via RDS) with multi‑tenant design and encryption for HIPAA‑sensitive fields
• File Storage: AWS S3 (with encryption)
• Load Balancing & Edge Caching: Nginx (or AWS ALB) and CDN for static assets
• Horizontal Scaling: EKS cluster autoscaling for containerized backend and client deployments
• Caching: In‑memory caches (Redis/ETS for real‑time data) plus CDN caching for static assets


