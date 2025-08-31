# QM CRM — Sprint 3 (Preview)

Single‑page preview (React via CDN + Tailwind CDN). No build step required.

## Quick Start (Open Locally)
1. Download this repo as ZIP and unzip.
2. Double‑click `index.html` → opens in your browser.

## Publish on GitHub Pages (Recommended)
### Option A — Upload via Web UI
1. Create a new repository on GitHub (e.g. `qm-crm-sprint3`), public.
2. Click **Add file → Upload files** and upload `index.html` from this folder, then **Commit**.
3. Go to **Settings → Pages**:
   - **Build and deployment → Source:** select **Deploy from a branch**.
   - **Branch:** `main` / root (`/`).
   - Save → wait for the green check.
4. Your site will be live at: `https://<your-user>.github.io/qm-crm-sprint3/`.

### Option B — Push from your machine (Git)
```bash
# If you don't have git initialized yet:
git init
git add index.html
git commit -m "Add Sprint 3 preview (single page)"
git branch -M main
git remote add origin https://github.com/<your-user>/qm-crm-sprint3.git
git push -u origin main
# Then enable GitHub Pages in Settings → Pages as described above
```

### Custom Domain (Optional)
- In **Settings → Pages**, add your domain (e.g. `crm.qualitymakers.com`).
- Create a DNS `CNAME` for `crm.qualitymakers.com` → `<your-user>.github.io`.

## How to Edit / Update
- Edit `index.html` directly on GitHub (press `.` for web editor), or locally then push.
- Every push to `main` instantly updates the live site (after ~1 min).

## Notes
- This is a **static preview**; no backend. For WordPress integration later, we’ll migrate the SPA to a plugin using REST routes and DB tables.
- If you see CORS errors when loading local file attachments, that’s expected for local URLs. On GitHub Pages, file uploads won’t persist (static hosting).

© 2025 Quality Makers