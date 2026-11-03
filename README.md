# المِسْبار — موقع التعريف (paltest.net)

صفحة ثابتة (`public/index.html`) مع 38 ملفاً صوتياً للجولات التعريفية (`public/audio`).
لا توجد خطوة بناء.

## النشر على Cloudflare
- من لوحة Cloudflare: Workers & Pages ← Create ← Import a repository، واختر هذا المستودع.
  أمر البناء: فارغ. أمر النشر: `npx wrangler deploy`.
- أو محلياً: `npx wrangler login` ثم `npx wrangler deploy`.

النطاق `paltest.net` معرّف في `wrangler.jsonc` كنطاق مخصّص (يجب ألا يكون عليه سجل CNAME قديم).

## ملاحظة
وكيل الدردشة ومولّد العقود يعملان في النسخة المنشورة داخل Claude فقط؛ على هذا الموقع يعمل الوكيل بأجوبة سريعة ثابتة ويعرض المولّد رسالة تعريفية.
