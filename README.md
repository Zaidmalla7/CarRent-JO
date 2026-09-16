# مشروع التخرج: نظام إدارة تأجير السيارات - CarRent JO 🚗

![.NET Core](https://img.shields.io/badge/.NET_CORE-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_SERVER-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Bootstrap](https://img.shields.io/badge/BOOTSTRAP-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

<!-- صورتك الرئيسية توضع هنا -->
![الصفحة الرئيسية]  <img width="1914" height="938" alt="Screenshot 2026-09-16 234922" src="https://github.com/user-attachments/assets/57362f17-dbe0-4057-98ee-8d8e373b41dc" />

يعتبر نظام **CarRent JO** منصة إلكترونية متكاملة لإدارة وتأجير السيارات، وقد تم تطويره كمشروع تخرج لطلاب جامعة آل البيت[cite: 1, 2]. تتيح هذه المنصة للعملاء استعراض السيارات، والتحقق من توفرها، وإتمام عملية الحجز والدفع إلكترونياً بالكامل[cite: 2].

- **رابط الموقع المباشر:** [CarRent JO - RunASP](https://carrental11.runasp.net/)[cite: 1]
---

## أبرز ميزات النظام
- **نظام المساعد الذكي:** أداة مبتكرة تقترح أفضل السيارات للعميل بناءً على طبيعة الرحلة والميزانية وعدد الركاب لضمان أفضل تجربة[cite: 2].
- **محاكاة عمليات الدفع:** آلية مدمجة تحاكي بوابات الدفع الإلكترونية للتحقق من البطاقات الوهمية وتأكيد الحجوزات بشكل يحاكي الأنظمة الحقيقية[cite: 2].
- **العرض ثلاثي الأبعاد:** دمج عارض تفاعلي يسمح للمستخدم بمشاهدة تفاصيل السيارة من جميع الزوايا قبل الحجز[cite: 2].
---

## دوري في المشروع
قمت بالعمل على تطوير هذا النظام بالتعاون مع زميلي عبد الكريم نوري[cite: 2]، وتركزت مهامي بشكل أساسي على:
- برمجة المتحكمات الرئيسية وتتضمن: RentalController, PaymentController, HomeController, AdminController[cite: 2].
- تصميم واجهات المستخدم الأمامية وتتضمن: الصفحة الرئيسية، البحث، وتفاصيل السيارة مع دمج عارض ثلاثي الأبعاد للسيارات[cite: 2].
- تطوير نظام الحجوزات بشكل كامل وتضمن ذلك: صفحة الحجز، صفحة حجوزاتي، وإلغاء الحجوزات[cite: 2].
- برمجة واجهات تسجيل الدخول وإنشاء الحساب وتدفقات إعادة التوجيه[cite: 2].
- تصميم الوضع الليلي وتوافق الموقع مع شاشات الهواتف المحمولة[cite: 2].

---

## التقنيات المستخدمة
تم بناء النظام بالاعتماد على معمارية MVC لضمان تنظيم الكود وسهولة الصيانة[cite: 1, 2]:
- **الواجهة الخلفية:** إطار عمل ASP.NET Core MVC مبني بلغة C#[cite: 1, 2].
- **قاعدة البيانات:** تقنية SQL Server مع Entity Framework Core[cite: 1, 2].
- **المصادقة والأمان:** نظام ASP.NET Identity لحماية كلمات المرور[cite: 1, 2].
- **الواجهة الأمامية:** تقنيات Razor Pages, Bootstrap 5, AJAX, HTML, CSS[cite: 1, 2].

---

## التحديات والحلول
خلال فترة التطوير التي استمرت 87 يوماً[cite: 2]، واجهنا عدة تحديات تقنية وقمنا بحلها بنجاح:
- **نظام الحماية:** بدأنا بنظام مستخدمين مخصص، ثم انتقلنا إلى ASP.NET Identity لزيادة الأمان، مما تطلب إعادة بناء قاعدة البيانات[cite: 2].
- **قيود المفاتيح الأجنبية:** واجهنا مشاكل عند حذف الحسابات المرتبطة بحجوزات، وقمنا بحل ذلك بضبط إعدادات Cascade و Restrict داخل سياق قاعدة البيانات[cite: 2].
- **أخطاء الواجهة:** ظهرت أخطاء برمجية بسبب محاولة الوصول لعناصر غير موجودة في بعض الصفحات، وتم حلها بإضافة شروط التحقق من العناصر[cite: 2].
- **تعارضات الأكواد:** لتجنب تعارضات ملفات الإعدادات أثناء العمل المشترك، قمنا بإضافة ملف الإعدادات إلى قائمة التجاهل في Git[cite: 2].

---

## المهارات المكتسبة
- إدارة الأكواد باحترافية والعمل الجماعي باستخدام Git[cite: 1, 2].
- تطبيق معمارية MVC في بيئة عمل حقيقية وفصل المنطق البرمجي عن الواجهات[cite: 1, 2].
- إدارة قواعد البيانات بشكل متقدم واستخدام أدوات الترحيلات[cite: 1, 2].
- التعامل مع المشاكل البرمجية المعقدة في بيئة الإنتاج[cite: 2].

---

## لقطات من النظام

### صفحة جميع السيارات والبحث
*(فلترة السيارات حسب الموقع وتاريخ الاستلام والإعادة)*
![All Cars]  <img width="1918" height="941" alt="Screenshot 2026-09-16 235607" src="https://github.com/user-attachments/assets/414055fa-256e-400f-adb2-aa62da2ee1ea" />


### صفحة تفاصيل السيارة 
*(عرض مواصفات السيارة والنموذج ثلاثي الأبعاد)*
![Car Details]  <img width="1909" height="936" alt="Screenshot 2026-09-16 235658" src="https://github.com/user-attachments/assets/44366441-76bb-4289-8868-6e5dd33162c5" />
<img width="1880" height="887" alt="Screenshot 2026-09-16 235720" src="https://github.com/user-attachments/assets/5ace79fc-d23c-4556-98c3-eab54a2f9035" />
<img width="1909" height="925" alt="Screenshot 2026-09-16 235900" src="https://github.com/user-attachments/assets/0df27825-cf3a-4a4d-8f7c-db92ea288b25" />




### صفحة تسجيل الدخول
*(واجهة تسجيل الدخول الآمنة عبر نظام الهوية)*
![Login Page]
<img width="1905" height="939" alt="Screenshot 2026-09-16 235821" src="https://github.com/user-attachments/assets/9656bb3b-c915-45ac-860c-796ab2f0ad53" />


### صفحة إدارة الحجوزات
*(عرض الحجوزات الحالية والسابقة وإمكانية الموافقة أو الإلغاء)*
![Bookings Management]
<img width="1899" height="929" alt="Screenshot 2026-09-16 235934" src="https://github.com/user-attachments/assets/f40d42af-1e76-4971-9db0-8cbb5494c9eb" />


### لوحة تحكم المشرف
*(إدارة السيارات والبيانات العامة للنظام)*
![Dashboard]
<img width="1902" height="938" alt="image" src="https://github.com/user-attachments/assets/e2a0cc9b-67b2-43ac-b905-8d9f9d070b17" />


### صفحة الصلاحيات والمستخدمين
*(إدارة حسابات المستخدمين وإنشاء حسابات المشرفين)*
![Users Authorization]
<img width="1914" height="955" alt="Screenshot 2026-09-17 000047" src="https://github.com/user-attachments/assets/b9811f87-b59a-4163-bec7-59f4332b9cef" />


## 📬 Contact & Links
* **Developer:** Zaid Yasser Mallah
* **LinkedIn:** [Zaid Mallah](https://www.linkedin.com/in/zaidyasser)
* **Email:** zaidalmallah444@gmail.com
