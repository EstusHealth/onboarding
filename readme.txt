Estus Health onboarding

index.html  OT Alignment Quiz for prospective occupational therapists.
            28 questions across eight chapters (pay, supervision, experience and
            scope, tech, gaming, life outside work, burnout prevention via James
            Clear / Cal Newport / inversion, autonomy and growth), ending in
            a radar "alignment graph" against the Estus fit zone, a class, likely
            caseload streams, the candidate's inversion answers, and a shareable
            results link.

            Self-contained static page: open it in a browser or host it anywhere
            (GitHub Pages, Vercel). Nothing is stored or sent; results live in the
            link's #hash, so a candidate can send their link to Liam.

Tuning: edit DIMS (fit-zone thresholds and weights), Q (questions and scores),
NOTES, STREAMS and CLASSES at the top of the <script> in index.html.

Deploying to Vercel
  1. In Vercel: Add New > Project > import the estushealth/onboarding repo.
  2. Framework preset: Other. Leave Build Command and Output Directory empty
     (it's a static site served from the repo root). Deploy.
  3. Optional: add a custom domain (e.g. quiz.estushealth.com.au) under
     Settings > Domains.
  vercel.json adds clean URLs and basic security headers; .vercelignore keeps
  this readme off the live site. Share links are built from whatever URL the
  page is served on, so they work on the custom domain automatically.
