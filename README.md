# Pragati Glow
React/Vite storefront + admin authentication starter for Cloudflare Pages and Supabase.

1. Create Supabase project.
2. Run supabase/schema.sql in SQL Editor.
3. Create an admin Auth user, then insert that user's UUID into public.admin_users.
4. Copy .env.example to .env.local and fill project URL + publishable key.
5. npm install && npm run dev
6. Push to GitHub.
7. Cloudflare Pages: production branch main, build npm run build, directory dist. Add the two VITE_ env vars.
