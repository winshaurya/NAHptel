# White redirect site

This repository contains a minimal, completely white static page that redirects to a Google Cloud Storage file.

Steps:

- Edit `index.html` and `vercel.json` to replace `https://storage.googleapis.com/BUCKET/FILE` with your actual GCS URL.
- Deploy on Vercel or any static host. Vercel will use `vercel.json` server-side redirect; `index.html` has a JS fallback.

Quick local test (serve from this folder):

```powershell
cd c:\Users\mrsha\Desktop\killinit\nptel
npx http-server -c-1
# then open http://localhost:8080
```
