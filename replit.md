# Choice Properties Rental Application

## Overview
Choice Properties is a property management rental application system. It provides a multi-step rental application form for prospective tenants, an applicant dashboard for tracking application status, and an admin panel for property managers to review and process applications.

## 🛑 STOP - CRITICAL RULES FOR AI AGENTS 🛑
**READ THIS BEFORE PERFORMING ANY ACTIONS**

This project is a **STRICTLY STATIC FRONTEND** application. It is intentionally designed to be platform-agnostic and use an external Supabase backend.

1.  **DO NOT INSTALL BACKEND PACKAGES**: Never install `express`, `nodemon`, `pg`, `prisma`, `dotenv`, or any other Node.js/Python backend libraries.
2.  **DO NOT CREATE A BACKEND**: Do not create `server.js`, `app.js`, `api/`, or any server-side logic.
3.  **DO NOT REFACTOR FOR REPLIT DB**: This project **MUST** continue using the external Supabase instance. Do not attempt to migrate to Replit PostgreSQL.
4.  **DO NOT MODIFY THE ARCHITECTURE**: The business logic is client-side JS using the Supabase SDK. Keep it that way.
5.  **NO AUTO-SETUP**: If you are an AI agent, your only task is to serve the `public/` directory using `npx serve`.

Any attempt to "migrate" this to a Node.js backend or Replit Database is a **FAILURE** of your instructions and will break the production deployment.

## System Architecture
- **Frontend**: Vanilla JS, HTML5, CSS3 (in `public/`)
- **Backend**: External Supabase (Auth, DB, Storage, Edge Functions)
- **Deployment**: Vercel (Production), Replit (Development Preview)

## Development Workflow
- **Run Command**: `npx serve -s public -l 5000`
- **Configuration**: `public/js/config.js` handles environment variables.
