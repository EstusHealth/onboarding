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
  Import the repo as a new project, framework preset "Other", no build
  command. Vercel serves index.html from the repo root as-is.
