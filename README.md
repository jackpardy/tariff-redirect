# tariff-redirect

Render static site that keeps the old address,
`trampoline-tariff-calculator.onrender.com`, sending visitors to
<https://tariff.pardy.ie>, keeping the path and any `#share=` link.

Render setup: Static Site from this repo, no build command, publish directory
`.`, and a Rewrite from `/*` to `/index.html` so every path loads the redirect.
