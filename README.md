<div dir="rtl" align="right">

# Arabic Dev Snippets 🇸🇦🇪🇬

> كود بالعربي — لكل developer عربي

[![Version](https://img.shields.io/badge/version-1.0.1-00d4aa)](https://marketplace.visualstudio.com/items?itemName=MostafaSaqly.arabic-dev-snippets)
[![License](https://img.shields.io/badge/license-MIT-ff6a6a)](LICENSE)
[![YouTube](https://img.shields.io/badge/YouTube-Saqly%20Courses-red)](https://youtube.com/@saqlycourses)

---

## ليه Arabic Dev Snippets؟

أول extension عربي بيديك:

- كود جاهز بضغطة Tab
- شرح بالعربي لكل snippet
- بيغطي كل الـ stack من Frontend للـ Backend
- مناسب للمبتدئين والمحترفين

---

## التقنيات المدعومة

| التقنية | الـ Prefix | عدد الـ Snippets |
|---|---|---|
| TypeScript | `ts-ar-` | 15 snippet |
| Angular | `ng-ar-` | 25 snippet |
| NestJS | `nest-ar-` | 12 snippet |
| Prisma | `pr-ar-` | 14 snippet |
| Ionic | `ion-ar-` | 22 snippet |
| Git | `git-ar-` | 12 snippet |

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

| الـ Prefix | الوصف |
|---|---|
| `ts-ar-interface` | إنشاء interface — زي العقد بين الـ components |
| `ts-ar-type` | إنشاء type alias — للأنواع البسيطة أو الـ union types |
| `ts-ar-enum` | إنشاء enum — للقيم الثابتة المعروفة مسبقاً |
| `ts-ar-generic` | دالة generic — بتشتغل مع أي نوع من البيانات |
| `ts-ar-decorator` | إنشاء decorator — بيضيف سلوك على الـ class أو الـ method |
| `ts-ar-class` | إنشاء class كامل مع constructor وـ methods |
| `ts-ar-abstract` | إنشاء abstract class للوراثة منه |
| `ts-ar-generic-interface` | interface generic بتتكيف مع أي نوع |
| `ts-ar-utility` | أنواع مساعدة جاهزة — Partial وRequired وPick وOmit |
| `ts-ar-async` | دالة async مع معالجة الأخطاء |
| `ts-ar-typeguard` | type guard للتحقق من النوع وقت التشغيل |
| `ts-ar-mapped` | mapped type لإنشاء نوع جديد من نوع موجود |
| `ts-ar-intersection` | دمج نوعين مع بعض |
| `ts-ar-record` | Record type لربط الـ keys بالقيم |
| `ts-ar-reduce` | تلخيص array في قيمة واحدة |

---

### Angular — `ng-ar-`

#### ملفات TypeScript

| الـ Prefix | الوصف |
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

| الـ Prefix | الوصف |
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

| الـ Prefix | الوصف |
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

| الـ Prefix | الوصف |
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

| الـ Prefix | الوصف |
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

| الـ Prefix | الوصف |
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

| الـ Prefix | الوصف |
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

| الكورس | الرابط |
|---|---|
| Angular من الصفر للاحتراف | [youtube.com/@saqlycourses](https://youtube.com/@saqlycourses) |
| NestJS + Prisma كامل | [youtube.com/@saqlycourses](https://youtube.com/@saqlycourses) |
| Ionic للموبايل | [youtube.com/@saqlycourses](https://youtube.com/@saqlycourses) |

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
