# 🏢 نظام إدارة الموظفين (OOP-Based Employee Management System)

<div align="center">

![Java](https://img.shields.io/badge/Language-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![OOP](https://img.shields.io/badge/Concepts-OOP-blue?style=for-the-badge)

**نظام كونسول (Console App) تفاعلي لإدارة بيانات الموظفين باستخدام مفاهيم البرمجة الشيئية.**

</div>

---

## 📝 نبذة عن المشروع

هذا المشروع هو تطبيق عملي لمفاهيم **البرمجة الكائنية (OOP)** في لغة Java. يتيح النظام للمسؤولين (Admins) تسجيل الدخول وإدارة سجلات الموظفين من مختلف الأقسام (مدراء، مهندسين، متدربين) وتخزين البيانات مؤقتاً ومعالجتها.

تم التركيز في التصميم على:
* **الوراثة (Inheritance):** جميع الفئات ترث من الفئة الأم `Employee`.
* **تعدد الأشكال (Polymorphism):** معالجة أنواع مختلفة من الموظفين بنفس الطريقة.
* **التغليف (Encapsulation):** حماية البيانات باستخدام `private` fields و `public` methods.

---

## ✨ المميزات الرئيسية

1.  **🔐 نظام تسجيل دخول آمن:** التحقق من اسم المستخدم وكلمة المرور قبل الوصول للنظام.
2.  **📋 إدارة الموظفين:**
    * إضافة **مدراء (Managers)** مع احتساب المكافآت.
    * إضافة **مهندسين (Engineers)**.
    * إضافة **متدربين (Interns)**.
3.  **📊 عرض البيانات:** عرض قائمة شاملة ومنظمة لجميع الموظفين المضافين.
4.  **💾 تخزين البيانات:** استخدام المصفوفات (Arrays) لتخزين وإدارة عدد كبير من الموظفين أثناء تشغيل البرنامج.

---

## 🛠️ هيكل المشروع (Project Structure)

```text
employee-management-system/
├── 📄 TestEmployee.java       # (Main Class) نقطة انطلاق البرنامج والقوائم
├── 📄 Employee.java           # الفئة الأساسية (Parent Class)
├── 📄 Manager.java            # فئة المدراء (ترث من Employee)
├── 📄 Engnieer.java           # فئة المهندسين (ترث من Employee)
├── 📄 Intern.java             # فئة المتدربين (ترث من Employee)
├── 📄 AdminstratorDATA.java   # قاعدة بيانات المسؤولين (Login Credentials)
├── 📄 UML.pdf                 # مخطط UML للتصميم
└── 📄 README.md               # ملف التوثيق
```

---

## ▶️ طريقة التشغيل (How to Run)

```bash
git clone https://github.com/ImMXP/employee-management-system.git
cd employee-management-system
javac *.java
java TestEmployee
```

### 🔑 بيانات الدخول التجريبية (Demo Login)

| Username | Password |
| :-- | :-- |
| `admin1` | `password1` |
| `admin2` | `password2` |
| `admin3` | `password3` |

> حسابات تجريبية للتشغيل المحلي فقط، ومعرّفة في `AdminstratorDATA.java`.
> Sample accounts for local testing only, defined in `AdminstratorDATA.java`.
