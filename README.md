# الصرف: درس المزيد بحرفين — open-slide deck

Slide deck for **أ. أسماء الحارثية**, الصف الثاني عشر, built with [open-slide](https://www.npmjs.com/package/@open-slide/core).

## Run locally

```sh
npm install
npm run dev
```

Then open <http://localhost:5173/s/mazeed-harfain>. On Windows, double-click `▶ تشغيل العرض.bat` instead.

## Deploy (Cloudflare Pages)

```sh
sh deploy/build.sh
npx wrangler pages deploy dist --project-name mazeed-harfain
```

## Folders

- `slides/mazeed-harfain` — the deck source
- `new/` — the original PDF this deck was rebuilt from
