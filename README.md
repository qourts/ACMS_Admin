# ACMS Match Control — Admin Site

GitHub Pages package for the ACMS Admin Portal.

## Target repository
Recommended repository: `qourts/ACMS_Admin`

## Files
- `index.html` — redirects the repository root to the Admin Portal
- `admin.html` — complete Admin application with Supabase publish integration
- `.nojekyll` — GitHub Pages compatibility

## Deploy
Upload the files to the repository root, then enable GitHub Pages from `main` / `/(root)`.

Expected URLs:
- Admin root: `https://qourts.github.io/ACMS_Admin/`
- Admin direct: `https://qourts.github.io/ACMS_Admin/admin.html`
- Player button target: `https://qourts.github.io/ACMS_Player/`

## Supabase
The Project URL and browser-safe publishable key are already configured in `admin.html`.
The private ACMS `acms_...` publish key is intentionally NOT included. Enter it once in Admin → Settings → Public Player Portal Sync on the authorized tournament computer, then Save Sync Settings → Test & Publish.

Never commit the private `acms_...` key, `sb_secret_...` keys, or the database password.
