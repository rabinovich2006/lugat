# Balaçıqlar İçün Resimli Luğat

A trilingual + Ukrainian picture dictionary for Crimean Tatar children, by Veli Bakalov.

This is a static site rendering of the original 2019 print dictionary:
- 27 vocabulary chapters (~1,000 illustrated words)
- 16 biographies of notable Crimean Tatar writers and public figures
- Crimean Tatar primary headwords with English, Russian, and Ukrainian translations on hover/tap

## Deploying to Vercel

This is a pure static site — no build step. To deploy:

1. Push this repo to GitHub
2. On vercel.com, click **New Project** → **Import Git Repository**
3. Select this repo, accept the defaults, click **Deploy**

The included `vercel.json` adds long-lived caching for `/images/*` and `/assets/*`.
