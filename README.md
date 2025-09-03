# 📧 Spam Email Detection with AdaBoost

این پروژه یک مدل یادگیری ماشین برای **تشخیص ایمیل‌های اسپم** است.  
در این پروژه از روش‌های **پردازش متن (TF-IDF)** و الگوریتم **AdaBoostClassifier** استفاده شده است.  
مدل ساخته شده توانست به **دقت حدود 96٪** برسد.  

---

## 🚀 ویژگی‌ها
- تبدیل متن ایمیل‌ها به بردار عددی با **TF-IDF**
- آموزش مدل با استفاده از **AdaBoost**
- جستجوی بهترین پارامترها با **GridSearchCV**
- ارزیابی مدل با:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix
- رسم نمودارهای:
  - توزیع داده‌ها (Spam vs Normal)
  - Confusion Matrix (Heatmap)
  - Precision, Recall, F1-score

---

## 📂 دیتاست
- دیتاست مورد استفاده: `spam.csv`
- شامل دو ستون اصلی:
  - `text` → متن ایمیل
  - `label` → 0 برای ایمیل عادی، 1 برای اسپم  

*(در صورت نیاز می‌توانید از دیتاست معروف [SpamBase UCI](https://archive.ics.uci.edu/ml/datasets/spambase) یا دیتاست‌های مشابه استفاده کنید.)*

---

## ⚙️ نحوه اجرا
1. نصب کتابخانه‌های مورد نیاز:
```bash
pip install pandas scikit-learn seaborn matplotlib
