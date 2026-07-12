# ارزیابی‌ها

این فایل روش‌ها و نتایج آزمون استخراج دانش و کاربرد قواعد را ثبت می‌کند.

ارزیابی باید دو موضوع متفاوت را جدا بسنجد:

1. آیا قاعده از منبع به‌درستی استخراج شده است؟
2. آیا استفاده از قاعده در تحلیل‌های جدید مفید و قابل‌اتکا است؟

## اصول ارزیابی

- اطلاعات آینده نباید وارد ورودی تحلیل تاریخی شوند.
- زمان تحلیل و افق ارزیابی باید پیش از مشاهده نتیجه مشخص شوند.
- نمونه‌های موفق و ناموفق هر دو ثبت شوند.
- داده آموزشی، داده تنظیم و داده آزمون از هم جدا باشند.
- برای سناریوهای معاملاتی، کارمزد، لغزش قیمت و Funding لحاظ شوند.
- عملکرد روی داده‌های دیده‌نشده و Walk-forward بررسی شود.
- یک پیش‌بینی درست، به‌تنهایی اعتبار یک روش را اثبات نمی‌کند.

## معیارهای استخراج دانش

- صحت انتساب به منبع
- صحت تایم‌استمپ
- وفاداری به قدرت ادعای مدرس
- جداسازی قاعده از مثال تاریخی
- تشخیص وابستگی تصویری
- شناسایی ابهام Transcript
- عدم افزودن دانش ساخته‌شده توسط مدل

## معیارهای تحلیل

- استفاده از Rule ID صحیح
- وجود شرایط کاربرد قاعده
- تشخیص شواهد ناقص یا متعارض
- تعریف شرایط ابطال
- تفکیک مشاهده از استنباط
- امکان نتیجه `no trade` یا `insufficient data`
- کالیبراسیون احتمال‌ها، فقط در صورت وجود روش آماری

## قالب ارزیابی استخراج

```text
Evaluation ID:
Evaluation type: extraction
Source ID:
Rule IDs evaluated:
Reviewer:
Evaluation date:
Source attribution correct: yes | no | partial
Timestamp correct: yes | no | partial
Historical context separated: yes | no | partial
Visual dependency identified: yes | no | partial
Unsupported additions found:
Ambiguities missed:
Result: pass | fail | needs_revision
Notes:
```

## قالب ارزیابی تحلیل تاریخی

```text
Evaluation ID:
Evaluation type: historical_application
Analysis timestamp:
Evaluation horizon:
Rules available at analysis time:
Market data available at analysis time:
Information intentionally withheld:
Model output:
Expected behavior:
Observed outcome after cutoff:
Invalidation triggered: yes | no | unclear
Fees assumption:
Slippage assumption:
Funding assumption:
Maximum favorable excursion:
Maximum adverse excursion:
Result:
Leakage check:
Notes:
```

## گزارش‌های ارزیابی

هنوز ارزیابی‌ای ثبت نشده است.
