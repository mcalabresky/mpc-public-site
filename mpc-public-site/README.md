MPC public website

This folder is a standalone Vercel-ready static website intended to replace the current Squarespace-hosted marketing site at:

- https://www.mpcsolutions.org/

Recommended hosting split:

- `www.mpcsolutions.org` -> this public website
- `mpcsolutions.org` -> redirect to `www.mpcsolutions.org`
- `platform.mpcsolutions.org` -> existing MPC platform app

Files:

- `index.html` - public marketing website
- `vercel.json` - minimal Vercel config

Deployment recommendation:

1. Create a separate Vercel project for this folder.
2. Add `www.mpcsolutions.org` and `mpcsolutions.org` to that Vercel project.
3. Keep the platform app in its current Vercel project on `platform.mpcsolutions.org`.
