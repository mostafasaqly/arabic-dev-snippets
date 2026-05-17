<div dir="rtl" align="right">

# Arabic Dev Snippets 🇸🇦🇪🇬

> كود بالعربي — لكل developer عربي

[![Version](https://img.shields.io/badge/Version-1.0.2-00d4aa)](https://marketplace.visualstudio.com/items?itemName=MostafaSaqly.arabic-dev-snippets)
[![License](https://img.shields.io/badge/License-MIT-ff6a6a)](LICENSE)
[![YouTube](https://img.shields.io/badge/YouTube-Saqly_Courses-red)](https://youtube.com/@saqlycourses)

---

## ليه Arabic Dev Snippets؟

أول extension عربي بيديك:

- كود جاهز بضغطة Tab
- شرح بالعربي لكل snippet
- بيغطي كل الـ stack من Frontend للـ Backend
- مناسب للمبتدئين والمحترفين

---

## التقنيات المدعومة

| Technology | Prefix | Snippets |
|---|---|---|
| TypeScript | `ts-ar-` | 15 |
| Angular | `ng-ar-` | 25 |
| NestJS | `nest-ar-` | 12 |
| Prisma | `pr-ar-` | 14 |
| Ionic | `ion-ar-` | 22 |
| Git | `git-ar-` | 12 |

**الإجمالي: أكتر من 100 snippet**

---

## التثبيت

### من داخل VS Code

1. افتح VS Code
2. اضغط `Ctrl+P`
3. اكتب:

```
ext install MostafaSaqly.arabic-dev-snippets
```

### من الـ Marketplace

ابحث عن **Arabic Dev Snippets** في تبويب الـ Extensions

---

## طريقة الاستخدام

1. افتح أي ملف TypeScript أو HTML
2. ابدأ الكتابة بالـ prefix المناسب
3. اختار الـ snippet من القائمة
4. اضغط **Tab** والكود بيكتب لوحده

---

## قائمة الـ Snippets الكاملة

---

### TypeScript — `ts-ar-`

| Prefix | الوصف |
|---|---|
| `ts-ar-interface` | تعريف شكل الكائن وحقوله |
| `ts-ar-type` | تعريف نوع مخصص بسيط أو اتحادي |
| `ts-ar-enum` | قائمة قيم ثابتة معروفة مسبقاً |
| `ts-ar-generic` | دالة تشتغل مع أي نوع من البيانات |
| `ts-ar-decorator` | إضافة سلوك على الكلاس أو الميثود |
| `ts-ar-class` | قالب كامل لإنشاء الكائنات |
| `ts-ar-abstract` | كلاس مجرد يورث منه ولا يستخدم مباشرة |
| `ts-ar-generic-interface` | واجهة تتكيف مع أي نوع بيانات |
| `ts-ar-utility` | أنواع مساعدة جاهزة لتحويل الأنواع |
| `ts-ar-async` | دالة غير متزامنة مع معالجة الأخطاء |
| `ts-ar-typeguard` | التحقق من نوع البيانات وقت التشغيل |
| `ts-ar-mapped` | إنشاء نوع جديد بناءً على نوع موجود |
| `ts-ar-intersection` | دمج نوعين معاً في نوع واحد |
| `ts-ar-record` | ربط المفاتيح بقيم من نوع معين |
| `ts-ar-reduce` | تلخيص مصفوفة في قيمة واحدة |

---

### Angular — `ng-ar-`

#### ملفات TypeScript

| Prefix | الوصف |
|---|---|
| `ng-ar-component` | إنشاء component — المبنة الأساسية في Angular |
| `ng-ar-service` | إنشاء service — لمشاركة البيانات والـ logic |
| `ng-ar-guard` | إنشاء route guard — بيمنع الدخول بدون إذن |
| `ng-ar-interceptor` | إنشاء HTTP interceptor — بيضيف الـ token تلقائياً |
| `ng-ar-pipe` | إنشاء pipe — بيغير شكل العرض |
| `ng-ar-signal` | استخدام signals — إدارة الـ state في Angular 17 |
| `ng-ar-resolver` | إنشاء resolver — بيجيب البيانات قبل ما الصفحة تفتح |
| `ng-ar-reactive-form` | إنشاء reactive form كامل مع الـ validation |
| `ng-ar-store` | store بسيط بالـ signals |
| `ng-ar-ondestroy` | إلغاء الـ subscriptions عند تدمير الـ component |
| `ng-ar-directive` | إنشاء custom directive |
| `ng-ar-io` | تمرير بيانات بالـ Input والـ Output |
| `ng-ar-input-signal` | Input signal — الطريقة الجديدة في Angular 17 |

#### ملفات HTML

| Prefix | الوصف |
|---|---|
| `ng-ar-template` | قالب أساسي لـ component |
| `ng-ar-for` | تكرار العناصر — الطريقة القديمة `*ngFor` |
| `ng-ar-if` | إظهار وإخفاء العناصر — الطريقة القديمة `*ngIf` |
| `ng-ar-for-new` | تكرار العناصر `@for` — Angular 17 |
| `ng-ar-if-new` | الشرط `@if` — Angular 17 |
| `ng-ar-switch-new` | الـ switch `@switch` — Angular 17 |
| `ng-ar-switch` | الـ switch القديم `ngSwitch` |
| `ng-ar-form` | قالب reactive form |
| `ng-ar-twoway` | ربط ثنائي الاتجاه `[(ngModel)]` |
| `ng-ar-event` | ربط أحداث HTML بدوال الـ component |
| `ng-ar-class-style` | إضافة classes وـ styles بشكل ديناميكي |
| `ng-ar-bind` | ربط خصائص HTML |
| `ng-ar-defer` | تحميل كسول `@defer` — Angular 17 |

---

### NestJS — `nest-ar-`

| Prefix | الوصف |
|---|---|
| `nest-ar-module` | إنشاء module — بينظم الكود في وحدات |
| `nest-ar-controller` | إنشاء controller — بيستقبل الـ HTTP requests |
| `nest-ar-service` | إنشاء service — منطق العمل الرئيسي |
| `nest-ar-dto` | إنشاء DTO — بيحدد شكل البيانات الجاية |
| `nest-ar-guard` | إنشاء guard — بيتحقق من صلاحية المستخدم |
| `nest-ar-pipe` | إنشاء pipe — بيتحقق من البيانات أو بيحولها |
| `nest-ar-interceptor` | إنشاء interceptor — بيلتقط الـ request والـ response |
| `nest-ar-filter` | إنشاء exception filter — بيمسك الأخطاء |
| `nest-ar-decorator` | إنشاء custom decorator لجلب بيانات من الـ request |
| `nest-ar-schedule` | جدولة مهام — تشغيل مهمة تلقائياً في وقت معين |
| `nest-ar-prisma-module` | إنشاء Prisma service للتواصل مع قاعدة البيانات |
| `nest-ar-jwt` | مصادقة كاملة بالـ JWT |

---

### Prisma — `pr-ar-`

| Prefix | الوصف |
|---|---|
| `pr-ar-model` | تعريف model — جدول في قاعدة البيانات |
| `pr-ar-findmany` | جيب كل السجلات مع فلترة وترتيب |
| `pr-ar-findone` | جيب سجل واحد بالـ ID |
| `pr-ar-create` | إضافة سجل جديد |
| `pr-ar-update` | تعديل سجل موجود |
| `pr-ar-delete` | حذف سجل |
| `pr-ar-relation` | علاقة One-to-Many بين جدولين |
| `pr-ar-many-to-many` | علاقة Many-to-Many |
| `pr-ar-transaction` | transaction — تنفيذ عمليات متعددة مع بعض |
| `pr-ar-pagination` | تقسيم النتايج لصفحات |
| `pr-ar-search` | بحث في أكتر من حقل |
| `pr-ar-upsert` | إضافة أو تحديث سجل |
| `pr-ar-deletemany` | حذف متعدد بشرط |
| `pr-ar-aggregate` | إحصائيات — مجموع ومتوسط وأقصى وأقل |

---

### Ionic — `ion-ar-`

#### ملفات TypeScript

| Prefix | الوصف |
|---|---|
| `ion-ar-page` | صفحة Ionic كاملة |
| `ion-ar-modal` | نافذة منبثقة — بتظهر فوق الصفحة الحالية |
| `ion-ar-toast` | رسالة صغيرة بتظهر وتتخلى لوحدها |
| `ion-ar-alert` | رسالة تأكيد قبل تنفيذ عملية مهمة |
| `ion-ar-loading` | مؤشر تحميل أثناء انتظار البيانات |
| `ion-ar-actionsheet` | قائمة خيارات بتظهر من تحت الشاشة |
| `ion-ar-popover` | نافذة صغيرة بتطلع جنب العنصر |
| `ion-ar-nav` | التنقل بين الصفحات |
| `ion-ar-storage` | حفظ وجلب البيانات من التخزين المحلي |
| `ion-ar-refresher` | بيسمح المستخدم يسحب لأسفل لتحديث البيانات |
| `ion-ar-infinite` | تحميل بيانات إضافية عند الوصول لآخر الصفحة |
| `ion-ar-camera` | التقاط صور من الكاميرا أو الاستوديو |

#### ملفات HTML

| Prefix | الوصف |
|---|---|
| `ion-ar-list` | قائمة عناصر قابلة للنقر |
| `ion-ar-card` | card بعنوان ومحتوى وأزرار |
| `ion-ar-grid` | تقسيم الشاشة لأعمدة |
| `ion-ar-search` | شريط البحث |
| `ion-ar-refresher-html` | قالب السحب للتحديث |
| `ion-ar-infinite-html` | قالب التحميل اللانهائي |
| `ion-ar-segment` | تبويبات للتنقل بين المحتوى |
| `ion-ar-slides` | slider للصور والبطاقات |
| `ion-ar-tabs` | شريط التنقل السفلي |
| `ion-ar-form-html` | نموذج Ionic كامل مع تحقق |

---

### Git — `git-ar-`

| Prefix | الوصف |
|---|---|
| `git-ar-init` | إنشاء repo جديد وربطه بـ GitHub |
| `git-ar-branch` | إنشاء branch والانتقال إليه |
| `git-ar-commit` | حفظ التغييرات بشكل صحيح |
| `git-ar-merge` | دمج الـ branches |
| `git-ar-undo` | التراجع عن التغييرات |
| `git-ar-remote` | رفع وجلب التغييرات |
| `git-ar-conflict` | حل الـ conflicts عند الدمج |
| `git-ar-stash` | حفظ مؤقت للتغييرات بدون commit |
| `git-ar-log` | عرض تاريخ الـ commits بشكل جميل |
| `git-ar-tag` | وسم الـ releases |
| `git-ar-rebase` | interactive rebase لإعادة كتابة التاريخ |
| `git-ar-clean` | تنظيف الـ repo من الـ branches القديمة |

---

## تعلم أكتر

الـ snippets دي مشروحة بالتفصيل في **Saqly Courses**:

| Course | الوصف | الرابط |
|---|---|---|
| Angular | من الصفر للاحتراف | [youtube.com/@saqlycourses](https://youtube.com/@saqlycourses) |
| NestJS + Prisma | كورس كامل | [youtube.com/@saqlycourses](https://youtube.com/@saqlycourses) |
| Ionic | تطبيقات الموبايل | [youtube.com/@saqlycourses](https://youtube.com/@saqlycourses) |

---

## المساهمة في المشروع

الـ extension ده open source — مرحب بأي مساهمة!

```bash
git clone https://github.com/MostafaSaqly/arabic-dev-snippets
cd arabic-dev-snippets
npm install
code .
```

### عاوز تضيف snippet جديدة؟

1. افتح الملف المناسب في مجلد `snippets/`
2. أضف الـ snippet بنفس الشكل الموجود
3. افتح Pull Request

---

## الرخصة

MIT License — مجاني للاستخدام الشخصي والتجاري

---

## دعم المشروع

لو الـ extension أفادك:

- اعمل Star على GitHub
- اشترك في [Saqly Courses](https://youtube.com/@saqlycourses)
- شارك الـ extension مع زمايلك

---

<div align="center">

صنيع بـ ❤️ للـ developers العرب

[YouTube](https://youtube.com/@saqlycourses) • [GitHub](https://github.com/MostafaSaqly) • [LinkedIn](https://linkedin.com/in/mostafasaqly)

</div>

</div>
