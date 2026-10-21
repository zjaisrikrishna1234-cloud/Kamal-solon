# Kamal Hair Dresser – Booking Website

Static website + Supabase backend.

## Files
- `index.html` – customer website (services, booking, manage booking)
- `admin.html` – admin panel (login required)
- `supabase/schema.sql` – database schema reference (already applied to your project)

## Deploy (Netlify)
1. Netlify -> Add new site -> Deploy manually.
2. Drag and drop this whole folder (or the zip's contents).
3. Customer site: https://YOUR-SITE.netlify.app
4. Admin panel: https://YOUR-SITE.netlify.app/admin.html

## Supabase
- Project URL and publishable key are set at the top of the script in both HTML files.
- Admin users are listed in the `admins` table (add a row with the user's id from Authentication -> Users).
- Never put a service_role / secret key in these files.
