OMNI-AGENT-AI / THERYN AI - CLOUDFLARE PAGES BUILD

This folder contains the prebuilt frontend only. It is intentionally much smaller
than the original Replit export and is suitable for Cloudflare Pages Direct Upload.

IMPORTANT:
The frontend still expects the Omni Agent backend/API at /api/* and Clerk auth.
Uploading this folder makes the web interface available, but it does NOT host the
Node/API backend. The backend must be deployed separately and the frontend's API
configuration must point to it if it is not on the same domain.

Do not upload .env files or API secrets to a static hosting service.
