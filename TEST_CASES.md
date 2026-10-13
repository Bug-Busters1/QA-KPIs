<div align="center">

# 🧪 Test Cases Suite - QA Assistant System
### حالات الاختبار التفصيلية لنظام مساعد الجودة والفرز الذكي 

[![Team](https://img.shields.io/badge/Team-Bug%20Busters1-orange.svg)](https://github.com/Bug-Busters1)
[![QA Engineer](https://img.shields.io/badge/QA%20Engineer-Abd%20Elrahman%20Esmat-purple.svg)](https://github.com/Bug-Busters1)
[![Module Status](https://img.shields.io/badge/Status-Ready%20for%20Execution-success.svg)](https://github.com/Bug-Busters1)

</div>

---

## 📌 جدول المحتويات (Table of Contents)
- [1. مقدمة عن وثيقة حالات الاختبار](#1-مقدمة-عن-وثيقة-حالات-الاختبار)
- [2. اختبارات المصادقة وإدارة المستخدمين (Authentication Module)](#2-اختبارات-المصادقة-وإدارة-المستخدمين-authentication-module)
- [3. اختبارات إدارة الأخطاء والباجات (Bug Management Module)](#3-اختبارات-إدارة-الأخطاء-والباجات-bug-management-module)
- [4. اختبارات الذكاء الاصطناعي والفرز الذكي (AI Triage Module)](#4-اختبارات-الذكاء-اصطناعي-والفرز-الذكي-ai-triage-module)
- [5. اختبارات لوحة التحكم والإحصائيات (Dashboard & Reports)](#5-اختبارات-لوحة-التحكم-والإحصائيات-dashboard--reports)

---

## 1. مقدمة عن وثيقة حالات الاختبار
تحتوي هذه الوثيقة على السيناريوهات وحالات الاختبار الأساسية (`Test Cases`) للتحقق من سلامة وصحة جميع وظائف **QA Assistant System**، بما في ذلك الواجهات، العمليات البرمجية، ودقة خوارزميات الذكاء الاصطناعي.

---

## 2. اختبارات المصادقة وإدارة المستخدمين (Authentication Module)
*الهدف: التحقق من أمان النظام وصلاحيات الأدوار المختلفة (QA Engineer, Team Leader, Developer, PM).*

| Test ID | Test Scenario / Description | Expected Result | Status |
| :--- | :--- | :--- | :--- |
| **TC_AUTH_01** | تسجيل الدخول ببيانات صحيحة ومسجلة مسبقاً. | يتم توجيه المستخدم بنجاح إلى لوحة التحكم الرئيسية (Dashboard). | ⏳ Pending |
| **TC_AUTH_02** | محاولة تسجيل الدخول بكلمة مرور خاطئة. | منع الدخول وظهور رسالة خطأ واضحة (Invalid Credentials). | ⏳ Pending |
| **TC_AUTH_03** | التحقق من صلاحيات الأدوار (QA مقابل Developer). | ظهور الميزات والصلاحيات المخصصة لكل دور برلمجي فقط. | ⏳ Pending |
| **TC_AUTH_04** | تسجيل الخروج من النظام (Logout). | إنهاء الجلسة وتوجيه المستخدم لصفحة تسجيل الدخول بأمان. | ⏳ Pending |

---

## 3. اختبارات إدارة الأخطاء والباجات (Bug Management Module)
*الهدف: ضمان كفاءة إنشاء، تعديل، وتتبع العيوب البرمجية.*

| Test ID | Test Scenario / Description | Expected Result | Status |
| :--- | :--- | :--- | :--- |
| **TC_BUG_01** | إنشاء Bug Report جديد بجميع الحقول الإلزامية (العنوان، الخطوات، المتوقع). | حفظ الباغ بنجاح وظهوره في قائمة الأخطاء العامة. | ⏳ Pending |
| **TC_BUG_02** | محاولة حفظ Bug Report مع ترك حقل إلزامي فارغ. | منع الحفظ وإظهار تنبيهات بضرورة ملء الحقول الناقصة. | ⏳ Pending |
| **TC_BUG_03** | فلترة الباجات حسب حالة الخطأ (Open, Resolved, Closed). | عرض الباجات المطابقة للفلتر المحدد بدقة فورية. | ⏳ Pending |
| **TC_BUG_04** | تعديل تفاصيل أو حالة خطأ موجود مسبقاً. | تحديث البيانات في قاعدة البيانات وعرض التعديل بنجاح. | ⏳ Pending |

---

## 4. اختبارات الذكاء الاصطناعي والفرز الذكي (AI Triage Module)
*الهدف: قياس دقة وكفاءة اقتراحات الـ AI في مساعدة فريق الـ QA.*

| Test ID | Test Scenario / Description | Expected Result | Status |
| :--- | :--- | :--- | :--- |
| **TC_AI_01** | إدخال وصف لباج جديد والتحقق من اقتراح الـ Severity & Priority. | يقترح النظام مستوى الخطورة والأولوية بدقة وفقاً للمحتوى. | ⏳ Pending |
| **TC_AI_02** | إدخال تقرير خطأ يشبه تماماً خطأ مسجلاً مسبقاً (Duplicate Test). | يكتشف النظام التشابه وينبه المستخدم بأن الباغ مكرر (Potential Duplicate). | ⏳ Pending |
| **TC_AI_03** | مراجعة اقتراحات الـ AI وقبولها أو تعديلها يدوياً (Human Review). | استجابة السيستم لتعديل المستخدم واعتماد التقييم النهائي البشري. | ⏳ Pending |
| **TC_AI_04** | اختبار سرعة توليد الملخصات الآلية (Concise Summaries) لوصف معقد. | تقديم ملخص قصير وواضح للخطأ في وقت قياسي. | ⏳ Pending |

---

## 5. اختبارات لوحة التحكم والإحصائيات (Dashboard & Reports)
*الهدف: التأكد من صحة ودقة البيانات والرسوم البيانية المعروضة.*

| Test ID | Test Scenario / Description | Expected Result | Status |
| :--- | :--- | :--- | :--- |
| **TC_DASH_01** | التحقق من صحة إجمالي عدد الباجات المفتوحة والمغلقة في الـ Dashboard. | تطابق الأرقام المعروضة تماماً مع قاعدة البيانات الحية. | ⏳ Pending |
| **TC_DASH_02** | مراجعة تحديث الرسوم البيانية لتوزيع الباجات حسب الشدة والنوع. | تحديث الرسومات البيانية ديناميكياً عند إضافة باجات جديدة. | ⏳ Pending |

---
<div align="center">
  <sub>Document Managed by <b>Abd Elrahman Esmat</b> (QA Engineer) — Bug Busters1 Team</sub>
</div>
