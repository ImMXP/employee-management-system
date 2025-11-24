# 🏢 نظام إدارة الموظفين القائم على البرمجة الشيئية (OOP-Based Employee Management System)

## ✨ شارات المشروع (Project Status)

[![لغة البرمجة: Java](https://img.shields.io/badge/Language-Java-blue.svg)](https://www.java.com/)

[![GitHub stars](https://img.shields.io/github/stars/ImMXP/OOP-Based-Employee-Management-System)](https://github.com/ImMXP/OOP-Based-Employee-Management-System/stargazers)

---

## 💡 نظرة عامة - المفهوم

هذا المشروع يمثل **نظاماً مبسطاً لإدارة الموظفين** تم تطويره باستخدام لغة البرمجة **Java** مع التركيز القوي على تطبيق مفاهيم **البرمجة الشيئية (OOP)** الأساسية: التغليف (Encapsulation)، الوراثة (Inheritance)، وتعدد الأشكال (Polymorphism).

الهدف هو بناء هيكل كلاسات واضح وفعال يُمكّن من إضافة أنواع موظفين جديدة بسهولة.

## 🚀 الميزات الرئيسية

* **تصنيف الموظفين:** يدعم النظام تصنيف الموظفين إلى فئات متخصصة (`Engineer`، `Intern`، `Manager`) ترث جميعها من فئة أساسية (`Employee`).
* **هيكل بيانات مُنظَّم:** تطبيق مبادئ OOP لضمان كود نظيف ومقروء.
* **قابلية التوسع:** سهولة إضافة خصائص أو سلوكيات جديدة للموظفين دون الحاجة لإعادة هيكلة النظام بالكامل.
* **وحدة اختبار مُدمَجة:** يتضمن الملف `TestEmployee.java` كمنفذ رئيسي لاختبار جميع وظائف الكلاسات.

## 🛠️ التقنيات المستخدمة (Tech Stack)

| التقنية | الوصف |
| :--- | :--- |
| **Java** | اللغة الرئيسية المعتمدة في تطوير النظام. |
| **OOP** | المنهجية التصميمية لنمذجة الكائنات والعلاقات. |
| **UML** | (اختياري) يتضمن المستودع مخطط UML يوضح علاقات الكلاسات وهيكلها. |

## ⚙️ البدء والتشغيل

لتشغيل كود Java هذا محلياً، اتبع الخطوات التالية:

### المتطلبات الأساسية (Prerequisites)

* **Java Development Kit (JDK):** الإصدار 8 أو أعلى.
* **بيئة تطوير متكاملة (IDE):** مثل IntelliJ IDEA, Eclipse, أو VS Code مع دعم Java.

### خطوات التشغيل

1.  **استنساخ المستودع (Clone the repository):**
    ```bash
    git clone [https://github.com/ImMXP/OOP-Based-Employee-Management-System.git](https://github.com/ImMXP/OOP-Based-Employee-Management-System.git)
    ```
2.  **فتح المشروع:**
    * افتح مجلد `OOP-Based-Employee-Management-System` في IDE الذي تختاره.
3.  **تجميع وتشغيل الملف:**
    * قم بتشغيل الملف `TestEmployee.java` (Run `TestEmployee.java`).

## 📁 هيكل الكلاسات

| اسم الملف | الوصف |
| :--- | :--- |
| `Employee.java` | الكلاس الأساسي الذي يحتوي على الخصائص العامة للموظف. |
| `Engineer.java` | كلاس يمثل فئة المهندسين ويرث من `Employee`. |
| `Intern.java` | كلاس يمثل فئة المتدربين ويرث من `Employee`. |
| `Manager.java` | كلاس يمثل فئة المدراء ويرث من `Employee`. |
| `TestEmployee.java` | كلاس الاختبار والتشغيل الرئيسي (Main Class). |

---

## 👨‍💻 المطورون
* **Moha0x**
* **Teammate**

---

## ⚖️ الترخيص

تم تطوير هذا المشروع كجزء من متطلبات أكاديمية.
