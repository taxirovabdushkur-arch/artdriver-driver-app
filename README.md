# Artdriver — Haydovchi ilovasi (interaktiv maket)

Bitta static HTML fayl (`index.html`) ichida qurilgan interaktiv prototip: to'liq ekran xarita, smena statusi (Old/Pauza/Off — sabab va dedlayn bilan), rahbariyat bilan chat va alohida "Xarajatlar" moduli.

Build qadam kerak emas — bu toza HTML/CSS/JS.

## Local ko'rish

`index.html` faylini brauzerda oching, yoki:

```bash
npx serve .
```

## Vercel'ga joylash

**Variant A — Vercel CLI orqali:**

```bash
npm i -g vercel
vercel login
vercel
```

`vercel` buyrug'ini shu papka ichida ishga tushiring, savollarga standart javob bering (framework: Other / static).

**Variant B — GitHub orqali:**

```bash
git remote add origin <GitHub repo URL>
git branch -M main
git push -u origin main
```

So'ng [vercel.com/new](https://vercel.com/new) orqali shu GitHub repo'ni import qiling — Vercel static HTML'ni avtomatik aniqlaydi, qo'shimcha sozlash shart emas.
