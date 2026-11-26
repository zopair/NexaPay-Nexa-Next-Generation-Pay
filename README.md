# NexaPay | Next Generation + Pay

## وصف المشروع

واجهة عربية متجاوبة (Mobile-First) تقدم تصورًا مقترحًا لإضافة حساب عمل حر دولي بالدولار إلى تجربة مالية مألوفة للمستخدم المصري. تعرض الواجهة الحساب الأساسي بالجنيه المصري، وحساب العمل الحر الدولي بالدولار، ورصيدًا افتراضيًا، وسعر تحويل توضيحيًا، وخدمات سريعة، وسجل معاملات تجريبيًا.

المشروع نموذج واجهة وتصميم للعرض والمناقشة، وليس تطبيق InstaPay الرسمي ولا يمثل شراكة أو اعتمادًا من البنك المركزي المصري أو أي بنك. جميع بيانات الحسابات والأرصدة وأسعار الصرف والمعاملات الواردة في الواجهة افتراضية، وزر التحويل ينفذ محاكاة حسابية فقط.

## عناصر الواجهة

- شريط علوي يحمل اسم صاحب الحقوق وعلامة «تصور مقترح».
- بطاقة الحساب الأساسي بالجنيه المصري.
- بطاقة حساب العمل الحر الدولي (USD) برصيد افتراضي قدره 1,250 دولارًا.
- زر محاكاة تحويل الدولار إلى الجنيه بسعر توضيحي قدره 49.20 جنيه لكل دولار.
- خدمات سريعة: إرسال نقود، طلب دفع، ودفع فواتير.
- سجل معاملات افتراضي.
- تنويه توضيحي وشريط تنقل سفلي ثابت.
- تصميم متجاوب مع الهواتف والشاشات الأكبر.

## المعاينة

https://zopair.github.io/NexaPay-Nexa-Next-Generation-Pay/

## وثائق المشروع

### الوثائق الاستراتيجية والتشغيلية

- [الاستراتيجية التنظيمية والقانونية](docs/COMPLIANCE_STRATEGY.md) — قانون 194 لسنة 2020، KYC/CDD، AML/CFT، دور البنك الشريك، وحدود استخدام Virtual IBAN وIPN.
- [رحلة المستخدم](docs/USER_JOURNEY.md) — من إرسال الحوالة الدولية بالدولار حتى قيد المقابل بالجنيه، مع الحالات والاستثناءات.
- [نموذج الأعمال الأصلي](docs/BUSINESS_MODEL.md) — تصور سابق لنموذج الشراكة والتشغيل؛ يُقرأ مع التحديث الأحدث أدناه.
- [تقييم المخاطر وإدارتها](docs/RISK_MANAGEMENT.md) — مخاطر الصرف والاحتيال والضغط التشغيلي والتكامل والخصوصية وخطة المعالجة.

### عرض الاستحواذ والتواصل مع البنوك

- [عرض الاستحواذ الكامل](docs/ACQUISITION_OFFER.md) — السعر المطلوب 250 مليون جنيه: 50 مليونًا نقدًا عند الإغلاق و200 مليون تُسدد بالكامل وتُخصص لوديعة مستقلة باسم البائع بعائد شهري وفق أسعار البنك للودائع المماثلة.
- [التواصل مع البنوك المصرية](docs/BANK_OUTREACH.md) — قائمة بداية مبنية على مصادر البنك المركزي، ومسودتا منشور LinkedIn بالعربية والإنجليزية، وضوابط التحقق من الحسابات الرسمية قبل المنشن.

الهيكل المالي الوارد في عرض الاستحواذ هو **موقف تفاوضي مقترح**، وليس منتج وديعة مضمون التوفر أو عائدًا ثابتًا أو موافقة من أي بنك. مدة العشر سنوات مستهدفة، وقد تتطلب تجديدات مصرفية وفق المنتجات المتاحة وشروطها.

### دراسة الاستحواذ الكامل والتقييم

**الموقف التجاري الأحدث:** يستهدف مالك المشروع بيع NexaPay / NexaPay-Nexa-Next-Generation-Pay بالكامل إلى بنك أو مؤسسة مصرفية مؤهلة، مقابل سعر مقطوع مطلوب قدره **250,000,000 جنيه مصري**. المقابل البالغ 5 ملايين دولار استرشادي وفق سعر افتراضي 50 جنيهًا للدولار، وليس سعر صرف مضمونًا.

- [دراسة الجدوى الاقتصادية والتقييم الاستراتيجي للاستحواذ الكامل](docs/ACQUISITION_VALUATION_STUDY.md) — حجم السوق، مصادر ITIDA وECES، متوسطات الدخل المفترضة، توقعات 3 و7 و10 سنوات، اختبار قدرة المنافع المصرفية على دعم سعر الاستحواذ، وشروط البيع.
- [بيانات النموذج المالي CSV](docs/ACQUISITION_FINANCIAL_MODEL.csv) — جدول قابل للاستيراد في Excel أو أي برنامج جداول.

**تنبيه منهجي:** أرقام ITIDA عن المستقلين والصادرات الرقمية مؤشرات لحجم السوق، وليست قياسًا مباشرًا للدخل الفردي أو الأموال التي لا تدخل البنوك. السيناريوهات المالية تتضمن افتراضات معلنة وليست ضمانات. الدراسة نفسها تشير إلى أن سعر 250 مليون جنيه هو سعر البيع المطلوب، ولا تصفه كتقييم مستقل معتمد. يجب استكمال التقييم الفني والمالي والقانوني والتحقق المصرفي قبل تقديمه باعتباره قيمة عادلة.

### تنبيه تنظيمي وتشغيلي

هذه الوثائق تصف **تصورًا مقترحًا** وليست اعتمادًا من البنك المركزي أو عرضًا لخدمة مصرفية قائمة. النموذج الحالي واجهة عرض ببيانات افتراضية ولا يستقبل حوالات ولا ينفذ تحويل عملات أو أوامر IPN. كما أن KYC السابق لدى البنك الأساسي لا يلغي واجب البنك المسؤول عن المنتج في التحقق من كفاية البيانات وتحديثها وتطبيق العناية الواجبة المستمرة. لا يبدأ التشغيل الحقيقي إلا بعد اعتماد البنك الشريك والهيكل القانوني والتكاملات والموافقات الرقابية اللازمة.

## حقوق الملكية والإيداع الإلكتروني

جميع الحقوق محفوظة للسيد / على حسين فكرى زبير على.

تم رفع نسخة الواجهة إلى مستودع GitHub:
- المستودع الحالي: https://github.com/zopair/NexaPay-Nexa-Next-Generation-Pay
- الفرع: `main`
- تاريخ الإيداع الأول للنسخة: 08 نوفمبر 2026
- وقت الإيداع: 09:30:59 مساءً بتوقيت مصر (UTC+02:00)
- البصمة الإلكترونية (Git Commit SHA) لنسخة الإيداع: `a6c8f43fb87c0cca701d21a852c4863c2375c55e`

تمت إضافة بيان الحقوق وبيانات الإيداع إلى الواجهة في تحديث GitHub رقم:
`384cdb8ed713928d99b952de1947c35e33ff1648`

## النشر والتشغيل

يتم نشر ملف `index.html` الموجود في جذر المستودع مباشرة عبر GitHub Pages باستخدام سير العمل الموجود في `.github/workflows/pages.yml`. لا يتطلب المشروع تثبيت حزم أو تشغيل عملية بناء؛ يعتمد على HTML وCSS وJavaScript، مع تحميل Cairo وTailwind CSS عبر CDN.

## الفيديو التوضيحي

فيديو قصير يشرح واجهة **NexaPay**، الحساب الأساسي بالجنيه، حساب العمل الحر الدولي بالدولار، والخطوة الحسابية لتحويل الرصيد الافتراضي إلى الجنيه:

[مشاهدة فيديو NexaPay Demo (MP4)](media/insta-freelancer-demo.mp4)

- المدة: 18 ثانية.
- الدقة: 640×360.
- الصيغة: MP4 / H.264.
- الفيديو صامت ومصمم للعرض السريع داخل GitHub.
- جميع الأرصدة وأسعار الصرف المعروضة افتراضية، والتحويل محاكاة توضيحية فقط.

### إعادة بناء الفيديو

تم تجهيز مسار بناء مفتوح المصدر وقابل لإعادة الإنتاج:
- `render_demo.py`: يرسم المشاهد العربية من الصفر باستخدام Pillow.
- `build_video.sh`: يجمع المشاهد ويصدر MP4 باستخدام FFmpeg.
- `.github/workflows/build-demo-video.yml`: يعيد توليد الفيديو تلقائيًا عند تحديث ملفات البناء، ثم يضيف الناتج إلى المستودع.

المصادر المفتوحة:
- [FFmpeg](https://github.com/FFmpeg/FFmpeg) — معالجة وترميز الفيديو (LGPL/GPL بحسب خيارات البناء).
- [Pillow](https://github.com/python-pillow/Pillow) — رسم المشاهد والصور.
- [GitHub Actions](https://github.com/actions/runner) — تشغيل مسار البناء.

لإعادة البناء محليًا، ثبّت FFmpeg وPillow والخطوط العربية Noto Sans Arabic ثم نفّذ:
```bash
python render_demo.py
bash build_video.sh
```


## Technical Setup & Verification

The current landing page is a static `index.html` with inline CSS/JavaScript and locally tracked video/screenshots. It requires no runtime package installation to preview:

```bash
git clone https://github.com/zopair/NexaPay-Nexa-Next-Generation-Pay.git
cd NexaPay-Nexa-Next-Generation-Pay
python -m http.server 8000
```

Open `http://localhost:8000/`. The Pages workflow copies only the root `index.html` to the site artifact. The separate demo-video workflow uses Python Pillow and FFmpeg to regenerate the MP4.

**Observed CI / workflow boundaries:**

- Static Pages deployment and demo-video build runs on 11 November 2026 completed successfully; the later observed Pages deployments on 22 November 2026 also succeeded.
- The current `.github/workflows/ci.yml` calls `npm install`, `npm test`, and `npm run build`, but the current repository tree contains no `package.json`. Treat that CI definition as stale and do not rely on its historical green result as a current reproducible test.
- No automated tests or package scripts are present in the current tree.
- `.github/workflows/build-demo-video.yml` has `contents: write` and commits regenerated video directly to `main`; it is not a PR-based review workflow.

## Proof of Concept & Enterprise Customization Readiness

**Status: Static proposal and demonstration interface only.** The bilingual wallet concept, fictional EGP/USD balances, sample transaction history, illustrative FX conversion, pricing/offer copy, and 18-second demo video are present. No bank account, virtual IBAN, remittance, custody, FX conversion, InstaPay, IPN, payment, or settlement service is integrated.

| Area | Current state |
|---|---|
| Responsive Arabic-first UI | Implemented as static HTML/CSS/JavaScript |
| Demo account balances and transactions | Fictional display data |
| FX conversion | Local arithmetic simulation using illustrative rate |
| Purchase / business offer | Gumroad link and proposal copy only |
| Banking / remittance / payment integration | Not implemented |
| Regulatory approval / bank partnership | Not evidenced; no endorsement claimed |
| Demo video | Tracked MP4; reproducible Pillow/FFmpeg build workflow |
| Pages deployment | Successful historical runs observed |
| Automated tests | None found in current tree |
| Current npm CI | Stale: references absent `package.json` |
| IP declaration | `docs/IP_DECLARATION.md` references a different project, Abid Gateway, and contains uncompleted declarant placeholders; it is not a NexaPay rights declaration |
| Project license | No root `LICENSE` file present in the reviewed tree |

### Readiness gates

1. Keep all financial values and conversion rates explicitly marked as illustrative until a licensed bank partner supplies approved product terms and pricing.
2. Obtain qualified Egyptian legal/regulatory review and written bank-partner approval before any account, remittance, payment, custody, or FX service is described as available.
3. Replace the copied `docs/IP_DECLARATION.md` template with a NexaPay-specific, correctly completed and legally reviewed declaration before relying on it as project evidence.
4. Reconcile the current npm CI workflow with the static-only repository: either add a real package/test setup or replace it with static HTML validation.
5. Change demo-video automation to create an artifact or PR rather than committing directly to `main`, if owner review is required before modifying the published asset.
6. Select and add a project license, while preserving FFmpeg/Pillow and media licensing obligations.

## Intellectual Property & Authorship

Public project attribution: **Aly Hussein Zopair (علي حسين زبير ALY HUSSEIN ZOPAIR)**.

The existing Arabic rights statement in this README is preserved verbatim. The separate `docs/IP_DECLARATION.md` currently names **Abid Gateway**, not NexaPay, and contains blank declarant/signature fields; it must not be presented as a completed NexaPay ownership declaration. Git history and timestamp records are supporting provenance evidence, not a substitute for a signed legal declaration or independent legal advice.
