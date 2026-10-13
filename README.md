# KPIs - QA Assistant System & Smart AI-Powered Bug Triage

## إيه هي الـ KPIs؟
مؤشرات الأداء الرئيسية اللي هنقيس بيها نجاح المشروع.

## ليه محتاجينها؟
- نقيس جودة السيستم
- نقيس أداء الـ AI
- نعرف إحنا ماشيين صح ولا لأ

## الـ KPIs

### 1) KPIs خاصة بجودة السيستم

| KPI | المعادلة | الهدف |
|-----|----------|-------|
| Test Case Pass Rate | (Passed ÷ Total) × 100 | ≥ 90% |
| Defect Density | عدد الباجات ÷ عدد الـ Modules | < 5 |
| Defect Removal Efficiency | (باجات اتلقطت قبل التسليم ÷ الإجمالي) × 100 | ≥ 95% |
| Test Coverage | (Features المختبرة ÷ الإجمالي) × 100 | 100% |
| Mean Time to Detect (MTTD) | مجموع أوقات الاكتشاف ÷ عدد الباجات | < 2 يوم |
| Mean Time to Resolve (MTTR) | مجموع أوقات الحل ÷ عدد الباجات | < 5 أيام |

### 2) KPIs خاصة بالـ AI (Bug Triage)

| KPI | المعادلة | الهدف |
|-----|----------|-------|
| Classification Accuracy | (اقتراحات صح ÷ الإجمالي) × 100 | ≥ 80% |
| Duplicate Detection Precision | (مكررات صح ÷ إجمالي اللي قال مكرر) × 100 | ≥ 75% |
| Recommendation Acceptance Rate | (اقتراحات اتقبلت ÷ الإجمالي) × 100 | ≥ 70% |
| Time Saved in Triage | وقت يدوي - وقت آلي | ≥ 50% توفير |

## إزاي هنقيس؟
- Manual Testing للواجهة
- API Testing للـ Backend
- سيناريوهات خاصة لاختبار الـ AI
- تسجيل كل نتيجة في Test Execution Report
