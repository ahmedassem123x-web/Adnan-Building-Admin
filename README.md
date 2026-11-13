# Adnan Building — Admin Panel

Private control panel for the Adnan Building landing page
(https://github.com/ahmedassem123x-web/Adnan-Building).

- **Access:** login required. Username `admin`; the password is set by the owner
  on first use (only its SHA-256 hash is stored, in the browser — never in this repo).
- **Not indexed:** `robots.txt` disallows everything; the panel sends
  `noindex,nofollow`.
- **What it does:** edit every section's text and colors, live preview,
  download a ready `index.html`.
- **Going live:** the panel never touches the live site. Send the downloaded
  `index.html` to Muse, who pushes it to the `Adnan-Building` repo after approval.
  Vercel + GitHub Pages redeploy automatically.

لوحة تحكم خاصة بصفحة شركة عدنان للبناء — الدخول بكلمة مرور يحددها المالك
عند أول استخدام، ولا تظهر في محركات البحث.
