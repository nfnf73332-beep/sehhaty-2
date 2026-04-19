# ☁️ دليل نشر ديموهات صحتي 2.0 على GitHub Pages

خطوات من الصفر — لا تحتاج خبرة تقنية. يستغرق الأمر **٥ دقائق** والنتيجة رابط حقيقي HTTPS يعمل فيه كل شيء.

---

## 📋 ما ستحصل عليه

بعد إنهاء هذا الدليل:
- رابط رسمي مثل: `https://your-username.github.io/sehhaty-2/`
- يعمل من أي جهاز ومتصفح — بدون تثبيت أي شيء
- الكاميرا ونماذج AI تعمل لأن الرابط HTTPS
- مشاركة الرابط مع قيادات الوزارة مباشرة

---

## الطريقة الأسهل (بدون سطر أوامر) — موصى بها

### الخطوة ١: أنشئ حساب GitHub (إن لم يكن لديك)
- افتح [github.com](https://github.com) → Sign up
- مجاني تمامًا للمستودعات العامة

### الخطوة ٢: أنشئ مستودع (repository) جديد
1. بعد تسجيل الدخول، اضغط **+** أعلى اليسار → **New repository**
2. **Repository name:** `sehhaty-2` (أو أي اسم تختاره)
3. اختر **Public** ⚠ (مطلوب لاستخدام GitHub Pages المجاني)
4. ضع علامة على **Add a README file**
5. اضغط **Create repository**

### الخطوة ٣: ارفع ملفات المشروع
1. داخل المستودع الجديد، اضغط **Add file** → **Upload files**
2. **اسحب** جميع الملفات التالية من مجلد «صحتي» دفعة واحدة:
   - `index.html`
   - `demo-mirror.html`
   - `demo-trainer.html`
   - `demo-chef.html`
   - `demo-dashcam.html`
   - `diagnostic.html`
   - `.nojekyll` ⚠ **مهم جدًا** (ملف مخفي — قد تحتاج إظهاره)
   - `README.md` (سيسأل عن الاستبدال — نعم)
3. في الأسفل اكتب رسالة مثل: `رفع ديموهات صحتي 2.0`
4. اضغط **Commit changes**

> **إن لم تظهر `.nojekyll`** على Mac: اضغط `Cmd + Shift + .` في Finder لإظهار الملفات المخفية.
> على Windows: View → Show → Hidden items.

### الخطوة ٤: فعّل GitHub Pages
1. في المستودع، اضغط **Settings** (أعلى اليمين)
2. من القائمة الجانبية اضغط **Pages**
3. تحت **Source** اختر **Deploy from a branch**
4. اختر **Branch: main** و **Folder: / (root)**
5. اضغط **Save**

### الخطوة ٥: انتظر ~٢ دقيقة وافتح الرابط
- سيظهر رابط أعلى الصفحة:
  `Your site is live at https://USERNAME.github.io/sehhaty-2/`
- اضغطه → افتح الديموهات → وافق على إذن الكاميرا

✅ **تم!** شارك الرابط مع من تريد.

---

## الطريقة الأسرع (إن كان لديك Git مثبت) — للمتقدمين

```bash
cd "/المسار/إلى/مجلد/صحتي"
git init
git add .
git commit -m "Initial commit — Sehhaty 2.0 demos"
git branch -M main
git remote add origin https://github.com/USERNAME/sehhaty-2.git
git push -u origin main
```

ثم الخطوة ٤ أعلاه لتفعيل Pages.

---

## 🔄 تحديث الموقع لاحقًا

**من الواجهة:**
- افتح الملف على GitHub → اضغط ✏️ (pencil) → عدّل → Commit.

**أو ارفع نسخة جديدة:**
- Add file → Upload files → ارفع الملفات المحدثة → Commit.

التحديث ينعكس على الموقع خلال دقيقة.

---

## 🌐 ربط دومين مخصص (اختياري)

إن أردت دومينًا احترافيًا مثل `sehhaty-demo.com`:
1. اشترِ الدومين (Namecheap, GoDaddy, إلخ)
2. في GitHub → Settings → Pages → **Custom domain**
3. اتبع تعليمات DNS التي يعرضها GitHub

---

## ⚠ مشاكل شائعة

**الصفحة تظهر 404**
→ تأكد أن الملف اسمه `index.html` (ليس `Index.html`). GitHub حساس لحالة الأحرف.

**الديموهات تعمل لكن CSS غير موجود**
→ المحتمل نسيت ملف `.nojekyll`. أضفه وجرّب مرة أخرى.

**الكاميرا لا تعمل حتى على الموقع الحي**
→ تأكد من الضغط على «Allow» عند طلب الإذن. إذا رفضت سابقًا، اضغط 🔒 في شريط العناوين وامنح الإذن.

**نماذج MediaPipe بطيئة**
→ طبيعي أول مرة (تحميل ~٥ ميجا). في الزيارات التالية محفوظة في الكاش.

---

## 🔐 جعل المستودع خاصًا

GitHub Pages يحتاج Public في الخطة المجانية. لو تحتاج Private:
- ترقية لـ **GitHub Pro** (٤ دولار/شهر) → يتيح Pages للمستودعات الخاصة
- أو استخدم بديلاً: **Vercel** / **Netlify** / **Cloudflare Pages** (كلها مجانية وتدعم Private)

---

## ✉ مشاركة الرابط

بعد النشر، شارك الرابط مع قيادات الوزارة عبر:
- رسالة مباشرة (WhatsApp, Email)
- ضمن عرض تقديمي (PowerPoint)
- QR code للوصول من الجوال

للتحويل لـ QR: استخدم [qr-code-generator.com](https://www.qr-code-generator.com)

---

**نصيحة:** جرّب الرابط على جهاز مختلف قبل المشاركة للتأكد من شغل كل شيء.
