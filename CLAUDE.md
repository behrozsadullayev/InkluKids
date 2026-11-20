# InkluKids — loyiha haqida

InkluKids — inklyuziv ta'lim oladigan bolalar uchun o'zbek tilidagi o'quv sayti
(yozuvga tayyorlov: chiziqlar, doiralar, egri chiziqlar; qum ustida mashqlar).
Qahramonlar: Harfjon (`img/harfjon.webp`) va Ziyo (`img/ziyo.webp`).

## Tuzilishi
- `index.html` — kirish nuqtasi, `app.css` va `app.js` ni ulaydi.
- `app.js` — **yig'ilgan (bundled, minified) React kodi**. Asl manba kodi bu yerda yo'q.
- `app.css` — barcha uslublar.
- `video/` — kirish va 4 ta o'yin videosi (+ poster rasmlari).
- `materiallar/` — chop etiladigan PDF ish varaqlari.
- `chatgpt-versiya/` — ChatGPT takomillashtirgan variant (foydalanuvchi qo'yadi).

## Ishga tushirish
```bash
python3 -m http.server 8000
```
Keyin brauzerda: http://localhost:8000

## Ishlash qoidalari
- Interfeys tili — o'zbek (lotin). Foydalanuvchi bilan ham o'zbekcha gaplash.
- Auditoriya — maxsus ehtiyojli bolalar: katta tugmalar, aniq kontrast,
  sodda matn, ovoz/animatsiya ehtiyotkor, klaviatura bilan boshqarish.
- Original fayllarni o'chirishdan oldin so'ra. Katta o'zgarishdan oldin reja ko'rsat.
- Minified `app.js` ni qo'lda tahrirlash qiyin: kerak bo'lsa, loyihani o'qiladigan
  manba kodiga (masalan, Vite + React yoki oddiy HTML/JS modullar) qayta tuzishni taklif qil.
