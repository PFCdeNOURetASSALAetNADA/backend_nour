# Sonelgaz Reclamation Backend

نظام إدارة الشكاوى لشركة سونلغاز - الواجهة الخلفية (Backend)

## الوصف
هذا المشروع هو الواجهة الخلفية لنظام إدارة الشكاوى الخاص بشركة سونلغاز. يتيح النظام للمشتركين تقديم شكاوىهم ومتابعتها، كما يتيح للمشغلين والمشرفين إدارة هذه الشكاوى.

## المميزات
- تسجيل المشتركين مع التحقق من البريد الإلكتروني
- إدارة حسابات المشغلين والمشرفين
- تقديم ومتابعة الشكاوى
- نظام إشعارات بالبريد الإلكتروني
- واجهة برمجة تطبيقات (API) آمنة

## المتطلبات
- Node.js (v14 أو أحدث)
- MySQL (v8.0 أو أحدث)
- npm أو yarn

## التثبيت
1. استنساخ المشروع:
```bash
git clone https://github.com/your-username/sonelgaz-reclamation-backend.git
cd sonelgaz-reclamation-backend
```

2. تثبيت الاعتماديات:
```bash
npm install
```

3. إنشاء ملف `.env` وإضافة المتغيرات البيئية:
```env
DB_HOST=localhost
DB_USER=your_username
DB_PASS=your_password
DB_NAME=sonelgaz_reclamation
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your_email@gmail.com
SMTP_PASS=your_app_password
SMTP_FROM=Sonelgaz <your_email@gmail.com>
JWT_SECRET=your_jwt_secret
PORT=3000
```

4. تشغيل قاعدة البيانات:
```bash
mysql -u root -p < sonelgaz_reclamation.sql
```

5. تشغيل الخادم:
```bash
npm run dev
```

## المسارات API
- `/api/abonnes` - إدارة حسابات المشتركين
- `/api/operateurs` - إدارة حسابات المشغلين
- `/api/superviseurs` - إدارة حسابات المشرفين
- `/api/reclamations` - إدارة الشكاوى
- `/api/affectations` - إدارة توزيع الشكاوى

## المساهمة
نرحب بمساهماتكم! يرجى اتباع الخطوات التالية:
1. عمل Fork للمشروع
2. إنشاء فرع جديد (`git checkout -b feature/amazing-feature`)
3. عمل Commit للتغييرات (`git commit -m 'إضافة ميزة رائعة'`)
4. رفع التغييرات (`git push origin feature/amazing-feature`)
5. فتح طلب Pull Request

## الترخيص
هذا المشروع مرخص تحت رخصة MIT - انظر ملف [LICENSE](LICENSE) للتفاصيل.
# backend_email
# finalbackend
# backend_nour
# backend_nour
⌢匠湯污慧⵺䅂䭃久ⵄ䥆䅎≌ഠ∊‣潓慮杬穡䈭䍁䕋䑎䘭义䱁•਍⌢匠湯污慧⵺䅂䭃久ⵄ䥆䅎≌ഠ∊‣楦慮彬慢正湥≤ഠ∊‣潓慮杬穡䈭䍁䕋䑎䘭义䱁•਍⌢映湩污扟捡敫摮•਍⌢映湩污扟捡敫摮•਍⌢丠畯⵲汥栭畯慤•਍