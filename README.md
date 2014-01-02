Arabic Less Framework
==========

<h3>Arabic Framework
reset and Variables and Mixins For Less</h3>


<h5>هي عبارة عن مكتبة لتسهيل العمل يوجد بها اختصارات كثيرة للمبرمج للعمل على قالب عربي كامل و انشاء مل</h5>

<h2>الخطوات الاساسية</h2>

<ul>
  <li>تحميل الملف و فك الضفط</li>
  <li>css في الفولدر ال arabic.less وضع الملف الخاص ب </li>
  <li>style.less وليكون css عمل ملف جديد داخل فولدر</li>
</ul>

<h2>تفعيل الملف</h2>
<p>و في اعلى الصفحة يكتب style.cssداخل ملف</p>
<p>@import "arabic.less"</p>

<h2>mixin اهم</h2>

.arabic-html();
.arabic-fonts();
.container(@width: 1024px);
.btn();
.hide();
.clearfix();
.imgSize();

<h2>variables اهم</h2>

@color: "your color option";
@tablet;
@mobile;
