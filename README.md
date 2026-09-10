# مکتب آیین — آیین دادرسی مدنی

برنامه آموزشی قانون آیین دادرسی دادگاه‌های عمومی و انقلاب در امور مدنی (مصوب ۱۳۷۹).

## ساختار آماده برای GitHub Pages

- `index.html` در **ریشه مخزن** (برای سرو شدن مستقیم توسط GitHub Pages)
- `manifest.json` — Web App Manifest استاندارد
- `sw.js` — Service Worker ساده برای پشتیبانی آفلاین و شناسایی توسط PWABuilder
- مسیرهای نسبی (`./`) برای جلوگیری از خطای ۴۰۴

### فعال‌سازی GitHub Pages

1. به Settings → Pages بروید
2. Source را روی **Deploy from a branch** بگذارید
3. Branch: `main` و پوشه `/ (root)` را انتخاب کنید
4. ذخیره کنید

آدرس تقریبی: `https://khabarelm-art.github.io/mobina/`

### PWABuilder

فایل‌های `manifest.json` و `sw.js` در ریشه قرار دارند تا PWABuilder بتواند برنامه را به‌عنوان PWA استاندارد تشخیص دهد.

## برنامه کامل (سورس)

سورس تعاملی React + TanStack در پوشه `src/` قرار دارد و برای اجرای کامل به محیط Node یا هاست سرور (مثل Vercel) نیاز دارد.

```bash
npm install
npm run dev
```
