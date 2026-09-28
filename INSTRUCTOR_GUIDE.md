# Instructor Guide

## أفضل طريقة لجعل كل متدرب يرفع المشروع في GitHub

### الخيار الأسهل داخل القاعة: Use this template

1. ارفعي هذا المجلد على GitHub في مستودع باسم:
   `genai-productivity-final-project`
2. من إعدادات المستودع فعّلي:
   **Settings → General → Template repository**
3. ارسلي رابط المستودع للمتدربين.
4. كل متدرب يضغط:
   **Use this template → Create a new repository**
5. يكتب اسم مستودعه، مثل:
   `meeting-follow-up-assistant-alaa`
6. يبدأ يعدل الملفات داخل GitHub مباشرة أو من جهازه.
7. في النهاية يرسل لك رابط مستودعه.

هذه الطريقة أفضل من clone للمبتدئين لأنها تعطي كل شخص نسخة مستقلة مباشرة.

---

## خيار ثاني: Download ZIP

1. المتدرب يحمل ZIP من مستودعك.
2. ينشئ مستودع جديد في حسابه.
3. يرفع الملفات يدويًا من زر:
   **Add file → Upload files**
4. يكتب وصف المشروع ثم يعمل Commit.

هذا مناسب إذا ما تبغين تدخلينهم في أوامر Git.

---

## خيار ثالث للمتقدمين: Clone ثم Push

```bash
git clone <trainer-repo-url>
cd genai-productivity-final-project
git remote remove origin
git remote add origin <student-repo-url>
git add .
git commit -m "Initial final project"
git push -u origin main
```

هذا مناسب فقط إذا المتدربين عندهم خبرة بسيطة في Git.

---

## المقترح للتدريب

استخدمي **Use this template** إذا كان عدد المتدربين كبير أو مستواهم مبتدئ.  
استخدمي **Clone** فقط للمتدربين التقنيين أو إذا كان جزء Git مهم في الدورة.
