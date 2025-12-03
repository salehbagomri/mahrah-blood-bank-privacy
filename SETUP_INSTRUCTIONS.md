# 📝 تعليمات رفع سياسة الخصوصية على GitHub
# Setup Instructions for Privacy Policy on GitHub

---

## 🚀 الخطوات - Steps

### 1. إنشاء المستودع - Create Repository ✅

لقد قمت بالفعل بإنشاء المستودع:
You've already created the repository:

```
https://github.com/salehbagomri/mahrah-blood-bank-privacy.git
```

---

### 2. نقل الملفات إلى مجلد المستودع - Move Files to Repository Folder

انسخ الملفات التالية إلى مجلد المستودع المحلي:
Copy the following files to your local repository folder:

```
d:\mahrah_blood_bank_app\privacy-policy-repo\
├── README.md
├── PRIVACY_POLICY.md
├── index.html
└── SETUP_INSTRUCTIONS.md (هذا الملف)
```

---

### 3. رفع الملفات على GitHub - Upload Files to GitHub

افتح Command Prompt أو Git Bash في مجلد المستودع وقم بتنفيذ الأوامر التالية:
Open Command Prompt or Git Bash in the repository folder and execute:

```bash
# التأكد من أنك في مجلد المستودع
# Make sure you're in the repository folder
cd path/to/mahrah-blood-bank-privacy

# إضافة جميع الملفات
# Add all files
git add .

# إنشاء commit
# Create commit
git commit -m "Add privacy policy files"

# رفع الملفات
# Push files
git push origin main
```

**ملاحظة:** إذا كان الفرع الافتراضي هو `master` بدلاً من `main`، استخدم:
**Note:** If the default branch is `master` instead of `main`, use:

```bash
git push origin master
```

---

### 4. تفعيل GitHub Pages - Enable GitHub Pages

1. اذهب إلى المستودع على GitHub:
   Go to your repository on GitHub:
   ```
   https://github.com/salehbagomri/mahrah-blood-bank-privacy
   ```

2. اضغط على **Settings** (الإعدادات) في الأعلى
   Click on **Settings** at the top

3. اختر **Pages** من القائمة الجانبية
   Select **Pages** from the sidebar

4. في قسم **Source**:
   In the **Source** section:
   - **Branch**: اختر `main` (أو `master`)
   - **Folder**: اختر `/ (root)`
   - اضغط **Save**

5. انتظر دقيقة واحدة، ثم ارجع إلى صفحة Pages
   Wait one minute, then return to the Pages page

6. ستجد الرابط:
   You'll find the link:
   ```
   https://salehbagomri.github.io/mahrah-blood-bank-privacy/
   ```

---

### 5. التحقق من الرابط - Verify the Link

افتح الرابط في المتصفح للتأكد من أن السياسة تظهر بشكل صحيح:
Open the link in your browser to verify the policy displays correctly:

```
https://salehbagomri.github.io/mahrah-blood-bank-privacy/
```

يجب أن ترى:
You should see:
- صفحة HTML جميلة بتصميم احترافي
- زر التبديل بين العربية والإنجليزية
- جميع أقسام سياسة الخصوصية

---

### 6. استخدام الرابط في Google Play Store - Use Link in Google Play Store

عند رفع التطبيق على Play Console:
When uploading the app to Play Console:

1. في قسم **Store Listing**
2. في حقل **Privacy Policy**، أدخل الرابط:
   ```
   https://salehbagomri.github.io/mahrah-blood-bank-privacy/
   ```

---

## 🔧 أوامر Git الكاملة (إذا لم تقم بإنشاء المستودع بعد)
## Complete Git Commands (If you haven't created the repository yet)

```bash
# 1. إنشاء مجلد جديد
# Create new folder
mkdir mahrah-blood-bank-privacy
cd mahrah-blood-bank-privacy

# 2. تهيئة Git
# Initialize Git
git init

# 3. نسخ الملفات إلى المجلد
# Copy files to folder
# (انسخ الملفات يدوياً أو استخدم الأمر cp)

# 4. إضافة الملفات
# Add files
git add .

# 5. إنشاء أول commit
# Create first commit
git commit -m "Initial commit: Add privacy policy"

# 6. ربط المستودع المحلي بـ GitHub
# Connect local repository to GitHub
git remote add origin https://github.com/salehbagomri/mahrah-blood-bank-privacy.git

# 7. تحديد الفرع الرئيسي
# Set main branch
git branch -M main

# 8. رفع الملفات
# Push files
git push -u origin main
```

---

## 📋 قائمة التحقق - Checklist

- [ ] نسخ الملفات إلى مجلد المستودع
- [ ] رفع الملفات على GitHub
- [ ] تفعيل GitHub Pages
- [ ] التحقق من الرابط يعمل
- [ ] استخدام الرابط في Play Store

---

## 🔄 تحديث السياسة مستقبلاً - Update Policy in Future

عندما تريد تحديث السياسة:
When you want to update the policy:

```bash
# 1. تعديل الملفات محلياً
# Edit files locally

# 2. إضافة التعديلات
# Add changes
git add .

# 3. إنشاء commit
# Create commit
git commit -m "Update privacy policy - [اكتب وصف التحديث]"

# 4. رفع التحديثات
# Push updates
git push origin main
```

سيتم تحديث الموقع تلقائياً خلال دقائق!
The site will update automatically within minutes!

---

## ⚠️ نصائح مهمة - Important Tips

1. **احتفظ بنسخة احتياطية**: احتفظ بنسخة من ملف PRIVACY_POLICY.md في مكان آمن
   **Keep backup**: Save a copy of PRIVACY_POLICY.md in a safe place

2. **تحديث التاريخ**: عند تحديث السياسة، حدث تاريخ "آخر تحديث"
   **Update date**: When updating policy, update "Last Updated" date

3. **إخطار المستخدمين**: أخبر المستخدمين بأي تغييرات جوهرية
   **Notify users**: Inform users about any material changes

4. **الاحتفاظ بالإصدارات القديمة**: Git يحفظ جميع الإصدارات السابقة تلقائياً
   **Keep old versions**: Git automatically saves all previous versions

---

## 📞 المساعدة - Help

إذا واجهت أي مشاكل:
If you encounter any issues:

- راجع وثائق GitHub Pages: https://pages.github.com/
- تواصل مع الدعم الفني لـ GitHub

---

## ✅ انتهى!

بعد اتباع هذه الخطوات، ستكون سياسة الخصوصية متاحة على:
After following these steps, your privacy policy will be available at:

**https://salehbagomri.github.io/mahrah-blood-bank-privacy/**

يمكنك استخدام هذا الرابط في:
You can use this link in:
- Google Play Console (إلزامي - Mandatory)
- Firebase Console
- التطبيق نفسه (في إعدادات "حول" - In app "About" settings)

---

💙 **صُنع بحب لأهالي المهرة**
