# ACMS Match Control — Admin Portal v4.47

Production Admin repository package for GitHub Pages.

## Production URLs
- Admin: https://qourts.github.io/ACMS_Admin/admin.html
- Player: https://qourts.github.io/ACMS_InterHospital/

## Supabase
The Admin HTML contains the browser-safe Supabase project URL and publishable key. The private ACMS publish key is intentionally NOT committed.

After deploying to GitHub Pages, open Admin > Settings > Public Player Portal Sync and paste the rotated private `acms_...` publish key on the authorized tournament computer, then click **Save Sync Settings** and **Test & Publish**.

Never commit the private ACMS publish key, an `sb_secret_...` key, or the database password.
