# Bank Soalan Interaktif TIMSS — Matematik (JPNK Kedah)

Laman web statik berasingan untuk bank soalan interaktif TIMSS subjek **Matematik**.
310 soalan, sumbangan guru-guru seluruh negeri Kedah.

## Cara Deploy ke GitHub Pages

1. Cipta repositori GitHub BAHARU (cth. `bank-soalan-matematik-timss-kedah`) — **berasingan**
   daripada repo Sains.
2. Muat naik SEMUA fail dalam folder ini (`index.html`, `style.css`, `app.js`,
   `questions.json`) terus ke ROOT repositori tersebut.
3. Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)` → Save.
4. Tunggu 1-2 minit. Laman akan hidup di:
   `https://<nama-akaun-github>.github.io/bank-soalan-matematik-timss-kedah/`

## Kemas kini data

Edit `questions.json` — setiap soalan ialah satu objek `{id, guru, sekolah, topik, slug, html}`.
`id` mesti unik dalam fail ini.
