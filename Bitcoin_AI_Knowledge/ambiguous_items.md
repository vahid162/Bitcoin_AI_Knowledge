# موارد مبهم

این فایل برای ثبت بخش‌هایی است که هنوز برای تبدیل‌شدن به دانش قابل‌اعتماد، شواهد کافی ندارند.

موارد زیر باید در این فایل ثبت شوند:

- واژه‌ها یا جملات نامفهوم Transcript
- خطاهای احتمالی تبدیل گفتار به متن
- اعداد، نام شاخص‌ها یا سطوح نامطمئن
- موارد وابسته به تصویر یا نمودار
- ادعاهای فاقد منبع یا تایم‌استمپ
- برداشت‌هایی که ممکن است استنباط مدل باشند

## وضعیت‌های مجاز

- `open`
- `needs_audio_review`
- `needs_visual_review`
- `needs_source_verification`
- `resolved`
- `rejected`

## قالب ثبت ابهام

```text
Ambiguity ID:
Source ID:
Timestamp:
Raw transcript text:
Possible interpretation:
Reason for uncertainty:
Required review: audio | visual | source | terminology
Related Rule IDs:
Status:
Resolution:
Resolved by:
Resolution date:
```

## قواعد حل ابهام

- متن خام باید حفظ شود.
- تفسیر احتمالی نباید به‌عنوان واقعیت ثبت شود.
- پس از حل ابهام، دلیل و منبع اصلاح باید ثبت شود.
- اگر ابهام بر یک قاعده اثر دارد، وضعیت آن قاعده باید تا زمان حل، `candidate` یا `needs_visual_review` باقی بماند.

## موارد ثبت‌شده

هنوز مورد مبهمی ثبت نشده است.
