# خلف الشاشة | Behind the Screen
موقع ثابت (HTML/CSS/JS) بدون خطوة بناء ولا Backend.

## التشغيل
افتح `index.html` في المتصفح (الخطوط ومكتبة QR تحتاج إنترنت).

## التعديل
- **الفيديوهات الستة:** افتح `videos.config.js` وضع الرابط في `url` (رابط YouTube بصيغة embed أو ملف mp4). اترك الحقل فارغًا ليظهر "الفيديو قريبًا".
- **الرابط النهائي لـ QR والمشاركة:** `SITE_URL` في نفس الملف.
- الأسئلة والمحتوى داخل `index.html` (مصفوفات `Q` و`PH` و`TL`).

## النشر مجانًا
الأسهل: **Netlify Drop** (app.netlify.com/drop): اسحب المجلد كله. بدائل: GitHub Pages أو Vercel (Framework: Other، بدون Build command).
بعد النشر ضع الرابط في `SITE_URL`.
