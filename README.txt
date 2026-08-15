AV EVENTS — NEW WORKER PROJECT

This project is designed for Cloudflare Workers Static Assets + D1.

Structure:
- public/        Website and admin files
- src/index.js   Worker/API
- wrangler.jsonc Cloudflare deployment configuration

IMPORTANT:
1. Create a NEW D1 database in Cloudflare.
2. After the Worker is created/deployed, add a D1 binding:
   Variable name: DB
   Database: your NEW AV EVENTS database
3. Add an environment secret:
   ADMIN_PASSWORD
4. Deploy the Worker with the repository connected to Cloudflare Workers Builds.

Do not mix these files with the old AV EVENTS project.
