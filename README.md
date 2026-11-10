# Breast Cancer Prediction 🎗️

تشخیص تومور خوش‌خیم (Benign) و بدخیم (Malignant) با استفاده از رگرسیون لجستیک.

## 📊 دیتاست

[Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) — شامل ۵۶۹ نمونه با ۳۰ ویژگی عددی (اندازه‌گیری‌های سلول تومور مانند شعاع، بافت، محیط،_AREA و ...).

- برچسب: `M` (بدخیم) و `B` (خوش‌خیم) → به `1` و `0` تبدیل شده.

## 🧪 مراحل انجام‌شده

1. حذف ستون `id`
2. تبدیل برچسب‌های `M`/`B` به `1`/`0`
3. نرمال‌سازی ویژگی‌ها با min-max scaling
4. تقسیم داده به آموزش/آزمون (۸۵٪ / ۱۵٪) با حفظ تناسب کلاس‌ها (`stratify`)
5. آموزش مدل Logistic Regression
6. ارزیابی با دقت، ماتریس درهم‌ریختگی و گزارش طبقه‌بندی

## 📈 نتیجه

دقت مدل روی داده‌های تست حدود **~۹۸٪** است (عدد دقیق در خروجی نوت‌بوک).

## 🚀 اجرا

```bash
pip install -r requirements.txt
jupyter notebook Breast-Cancer-Prediction.ipynb
```

## 🛠 تکنولوژی‌ها

Python • Pandas • NumPy • Matplotlib • scikit-learn
