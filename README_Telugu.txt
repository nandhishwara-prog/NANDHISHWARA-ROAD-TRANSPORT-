NRT ONLINE BILTY SYSTEM - SETUP (TELUGU)

1. Supabase lo free project create cheyyandi.
2. SQL Editor open chesi supabase-schema.sql lo unna SQL motham paste chesi Run cheyyandi.
3. Supabase -> Settings -> API Keys / Connect lo:
   - Project URL
   - Publishable key (sb_publishable_...)
   teesukondi.
4. supabase-config.js lo:
   SUPABASE_URL = mee Project URL
   SUPABASE_PUBLISHABLE_KEY = mee Publishable key
   petti save cheyyandi.
   IMPORTANT: secret/service_role key ni ikkada pettakandi.
5. Ee 4 files ni GitHub Pages repository root lo upload cheyyandi:
   index.html
   bilty.html
   supabase-config.js
   supabase-schema.sql
   (schema.sql website ki avasaram ledu; Supabase SQL Editor kosam matrame.)
6. GitHub Pages publish ayyaka:
   https://nandhishwara-prog.github.io/NANDHISHWARA-ROAD-TRANSPORT-/bilty.html
   ane page open avutundi.
7. First time "Create account" tho NRT staff login create chesi, login avvandi.

FEATURES
- Automatic LR number
- Cloud database storage
- Mobile/PC search
- LR records list
- A4 3-copy print
- Consignor / Consignee / Transporter copies
- Status field
- Supabase Auth login
- RLS protected database

NOTE
GitHub Pages static hosting kosam; permanent LR data Supabase database lo store avutundi.
Pages deployment trigger test
