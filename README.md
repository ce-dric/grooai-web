# GrooAI — company website

One-page company site for GrooAI (그루에이아이), served by GitHub Pages at **https://grooai.dev**.

- `index.html` — the whole site (single file: HTML, CSS, a little JSON-LD; no build step)
- `CNAME` — the custom domain GitHub Pages serves (`grooai.dev`)

## Local preview

Open `index.html` in a browser. Nothing to install.

## Deploying

Push to `main`. GitHub Pages publishes the repository root; `CNAME` and, once the
certificate is issued, "Enforce HTTPS" keep the custom domain on `https://grooai.dev`.

DNS (at the registrar):

- `A` records on `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `CNAME` on `www` → `ce-dric.github.io`

## Content

Company details shown on the site come from the business registration (사업자등록증명):
GrooAI (그루에이아이), representative Changwoo Song (송창우),
Business Reg. 104-47-04055, Daejeon, Republic of Korea. Contact: changwoo.dev@gmail.com.
