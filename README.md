# CreaDev — Digital Product Studio

صفحة تعريفية (Landing Page) أحادية الملف لاستوديو تطوير منتجات رقمية، مبنية بالكامل بـ HTML/CSS/JS خالص بدون أي أطر عمل (Frameworks) أو خطوة بناء (Build Step). الصفحة جاهزة للعرض فورًا بمجرد فتح الملف في المتصفح.

## 🔗 عرض مباشر

افتح الملف `agency.html` مباشرة في أي متصفح — لا حاجة لأي إعداد أو تثبيت.

## ✨ المميزات

- **تصميم Glassmorphism وخلفية Aurora** متحركة مع إضاءة تتبع مؤشر الفأرة
- **تأثيرات 3D Tilt** على البطاقات (الخدمات، الأعمال، الفريق) عبر مكتبة VanillaTilt
- **عدّادات إحصائيات متحركة (Count-up)** تعمل عند الظهور في الشاشة
- **Reveal on Scroll** باستخدام Intersection Observer لإظهار العناصر بسلاسة عند التمرير
- **Parallax** خفيف في قسم الـ Hero يتبع حركة الفأرة
- **أزرار Ripple + Magnetic** لتحسين تجربة التفاعل
- **شريط تقنيات متحرك (Marquee)** بأيقونات Devicon الرسمية
- **دعم كامل لـ RTL** عبر خصائص `inset-inline-start` بدلاً من `left/right`
- **احترام `prefers-reduced-motion`** لتعطيل الحركات لمن يفضّل ذلك
- **شريط تقدّم التمرير (Scroll Progress Bar)** أعلى الصفحة
- تصميم متجاوب (Responsive) بالكامل لجميع أحجام الشاشات

## 📄 أقسام الصفحة

| القسم | الوصف |
|---|---|
| Hero | العنوان الرئيسي، CTA، وشريط التقنيات المستخدمة |
| Stats | إحصائيات سريعة (المشاريع المنجزة، نسبة رضا العملاء...) |
| Services | خمس خدمات رئيسية يقدمها الاستوديو |
| Work | نماذج من أعمال سابقة |
| Team | فريق العمل مع روابط GitHub |
| Process | خطوات آلية العمل (٤ مراحل) |
| Global | نطاق العمل الجغرافي |
| Contact | نموذج تواصل |

## 🛠️ التقنيات المستخدمة

- **HTML5 / CSS3** خالص (بدون أي إطار عمل CSS)
- **JavaScript (Vanilla)** بدون مكتبات إضافية عدا:
  - [VanillaTilt.js](https://github.com/micku7zu/vanilla-tilt.js) — تأثير الإمالة ثلاثي الأبعاد
  - [Devicon](https://devicon.dev/) — أيقونات التقنيات
- **Google Fonts**: Sora, Inter, JetBrains Mono

## 📁 هيكل المشروع

```
Our-team-portfolio-main/
└── agency.html    # الصفحة بالكامل (HTML + CSS + JS في ملف واحد)
```

## 🚀 طريقة التشغيل محليًا

```bash
git clone <رابط-المستودع>
cd Our-team-portfolio-main
# افتح الملف مباشرة في المتصفح
open agency.html      # macOS
start agency.html     # Windows
xdg-open agency.html  # Linux
```

أو يمكن تشغيله عبر أي خادم محلي بسيط، مثل:

```bash
python -m http.server 8000
```

ثم زيارة `http://localhost:8000/agency.html`

## 👥 الفريق

| الاسم | الدور | GitHub |
|---|---|---|
| عادل أحمد البوشي | Product Manager | [@adel307](https://github.com/adel307) |
| أحمد عيد | QA Engineer | [@ahmed1eid](https://github.com/ahmed1eid) |
| إسلام حمدي | Backend Team Leader | [@islam412](https://github.com/islam412) |

## 📝 ملاحظات للتطوير

- نموذج التواصل (`#contact`) حاليًا واجهة فقط بدون ربط خلفي (Backend) — يحتاج لربطه بخدمة إرسال بريد أو API.
- بيانات "الأعمال" (`#work`) نماذج توضيحية (Placeholder) ويُنصح باستبدالها بأعمال حقيقية.
- صور الفريق تُجلب من GitHub Avatars تلقائيًا؛ في حال تعذّر تحميل الصورة تظهر أيقونة بديلة تلقائيًا.

## 📄 الترخيص

© 2026 CreaDev. جميع الحقوق محفوظة.
