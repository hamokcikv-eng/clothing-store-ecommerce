# 👗 StyleHub - متجر الملابس الإلكتروني

منصة e-commerce احترافية للملابس مع تكامل WhatsApp وواجهة إدارية متقدمة.

## ✨ المميزات الرئيسية

✅ **تصميم عصري وجامد** - واجهة مستخدم احترافية وسريعة
✅ **عرض المنتجات** - بحث وتصفية متقدمة
✅ **سلة التسوق** - إدارة سهلة للمنتجات
✅ **إرسال WhatsApp** - تنبيهات تلقائية بتفاصيل الطلب
✅ **قاعدة بيانات آمنة** - PostgreSQL مع معايير أمان عالية
✅ **لوحة إدارة** - إدارة المنتجات والطلبات
✅ **API RESTful** - متكامل وآمن

## 🛠️ التقنيات المستخدمة

### Frontend
- **Next.js 14** - React framework
- **TailwindCSS** - تصميم responsive
- **Zustand** - إدارة الحالة
- **Axios** - HTTP requests

### Backend
- **Node.js + Express** - API server
- **PostgreSQL** - قاعدة بيانات
- **Twilio** - WhatsApp integration
- **CORS** - معالجة الطلبات

## 📋 المتطلبات

- Node.js v16+
- PostgreSQL v12+
- npm أو yarn
- حساب Twilio (مجاني)

## 🚀 التثبيت والتشغيل

### 1️⃣ إعداد قاعدة البيانات

```bash
creatdb clothing_store
psql -U postgres -d clothing_store -f backend/db/schema.sql
```

### 2️⃣ تثبيت Backend

```bash
cd backend
npm install
cp .env.example .env
# حرر .env وأضف بيانات Twilio
npm run dev
```

### 3️⃣ تثبيت Frontend

```bash
cd frontend
npm install
npm run dev
```

## 🌐 الروابط

- **Frontend**: http://localhost:3000
- **Backend API**: http://localhost:5000/api
- **Admin Panel**: http://localhost:3000/admin

## 📞 API الرئيسية

- `GET /api/products` - المنتجات
- `POST /api/orders` - إنشاء طلب
- `GET /api/orders` - الطلبات
- `GET /api/customers` - العملاء

## 🔒 الأمان

- SQL Injection Prevention
- CORS معالجة
- Input Validation
- Transaction Support

---

صُنع بـ ❤️ من قبل StyleHub