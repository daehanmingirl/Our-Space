# Our Space — demo & landing (Netlify)

- `index.html` — demo Our Space (frontend penuh, jalan dalam browser, data demo simpan dalam localStorage).
- `landing.html` — landing page jualan.

Dihoskat percuma melalui **Netlify**.

## Deploy (sekali je, ±3 minit)

1. Buka https://app.netlify.com → sign up / login (boleh guna akaun GitHub atau Google).
2. Kat dashboard, cari kotak **"Drag and drop your site output here"** (atau Sites → Add new site → Deploy manually).
3. **Drag seluruh folder `site/` ni** ke kotak tu. Netlify terus build & deploy.
4. Link live keluar terus, contoh: `https://random-name-12345.netlify.app`
5. Rename domain: Site configuration → Change site name → contoh `our-space` → jadi `https://our-space.netlify.app`

**Penting:** letak landing page sebagai muka depan (optional). Kalau nak orang land di landing page dulu, rename `landing.html` → `index.html` dan demo jadi `demo.html` (update link butang "Cuba demo" dalam landing dari `index.html` ke `demo.html`). Kalau tak, demo terus jadi muka depan macam sekarang.

## Update demo/landing

Drag folder `site/` semula ke kotak deploy yang sama — Netlify overwrite automatik.
