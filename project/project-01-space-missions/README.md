# 🚀 Space Missions Data Analysis

> A comprehensive analysis of global space missions, exploring trends, costs, and success rates across different countries and companies  
> تحلیلی جامع از مأموریت‌های فضایی جهانی، بررسی روندها، هزینه‌ها و نرخ موفقیت در کشورها و شرکت‌های مختلف

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-yellow.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.24+-orange.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7+-red.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-green.svg)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

---

## 📖 درباره پروژه (About This Project)

**فارسی:**  
این پروژه به تحلیل داده‌های مأموریت‌های فضایی انجام‌شده در سال‌های ۲۰۱۹ و ۲۰۲۰ می‌پردازد. هدف، استخراج الگوها، بررسی عملکرد شرکت‌ها و کشورهای مختلف، و شناسایی عوامل مؤثر بر موفقیت یا شکست مأموریت‌ها است. این تحلیل شامل تمیزکاری داده، تحلیل اکتشافی (EDA)، مصورسازی داده و استخراج بینش‌های کلیدی می‌باشد.

**English:**  
This project analyzes space mission data from 2019 and 2020. The goal is to extract patterns, evaluate the performance of different companies and countries, and identify factors influencing mission success or failure. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, and extracting key insights.

---

## 🗂️ ساختار پروژه (Project Structure)
project-02-space-missions/
│
├── README.md # این فایل / This file
├── analysis.ipynb # نوت‌بوک اصلی تحلیل / Main analysis notebook
├── analysis.py # اسکریپت پایتون / Python script (optional)
│
├── data/
│ └── space_missions.csv # دیتاست اصلی / Main dataset
│
├── images/ # تصاویر و نمودارها / Images & charts
│ ├── missions_by_company.png
│ ├── success_rate_by_country.png
│ ├── cost_distribution.png
│ └── missions_over_time.png
│
└── reports/ # گزارش‌های نهایی / Final reports
└── insights_summary.md # خلاصه بینش‌ها / Summary of insights


---

## 📊 خلاصه داده‌ها (Data Summary)

| ویژگی (Feature) | مقدار (Value) |
| :--- | :--- |
| **تعداد کل مأموریت‌ها** | ۱۵۴ |
| **بازه زمانی** | فوریه ۲۰۱۹ تا اوت ۲۰۲۰ |
| **تعداد شرکت‌های فعال** | ۱۶ شرکت |
| **تعداد کشورهای مشارکت‌کننده** | ۱۱ کشور |
| **میانگین هزینه هر مأموریت** | حدود ۶۳.۵ میلیون دلار |
| **نرخ موفقیت کلی** | حدود ۹۳.۵٪ |

---

## 🎯 سوالات تحلیلی (Analytical Questions)

در این پروژه به سوالات زیر پاسخ داده شده است:

1.  **کدام کشور/شرکت بیشترین مأموریت فضایی را انجام داده است؟**
2.  **نرخ موفقیت هر شرکت یا کشور چقدر است و چه الگویی در آن وجود دارد؟**
3.  **هزینه هر مأموریت چقدر است و چه شرکت‌هایی گران‌ترین مأموریت‌ها را دارند؟**
4.  **روند تعداد مأموریت‌ها در طول زمان (ماهانه یا سالانه) چگونه است؟**
5.  **آیا بین هزینه و موفقیت مأموریت رابطه‌ای وجود دارد؟**
6.  **کدام کشورها بیشترین هزینه را در مأموریت‌های فضایی داشته‌اند؟**

---

## 📈 نمونه تصاویر (Sample Visualizations)

*(تصاویر پس از اتمام تحلیل در این بخش قرار خواهند گرفت)*

![Missions by Company](https://via.placeholder.com/600x300?text=Coming+Soon)
*نمودار تعداد مأموریت‌ها به تفکیک شرکت*

![Success Rate by Country](https://via.placeholder.com/600x300?text=Coming+Soon)
*نمودار نرخ موفقیت به تفکیک کشور*

---

## 🔍 بینش‌های کلیدی (Key Insights)

*(این بخش پس از اتمام تحلیل تکمیل خواهد شد)*

- **بینش ۱:** شرکت SpaceX با انجام ۳۴ مأموریت، پرکارترین شرکت فضایی در این بازه بوده است.
- **بینش ۲:** کشور چین با ۵۶ مأموریت، بیشترین تعداد پرتاب را به خود اختصاص داده است.
- **بینش ۳:** نرخ موفقیت کلی مأموریت‌ها حدود ۹۳.۵٪ بوده و بیشترین شکست‌ها مربوط به شرکت‌های چینی است.
- **بینش ۴:** گران‌ترین مأموریت‌ها مربوط به شرکت Arianespace با هزینه‌ی ۲۰۰ میلیون دلار است.
- **بینش ۵:** روند کلی مأموریت‌ها در سال ۲۰۲۰ نسبت به ۲۰۱۹ افزایشی بوده است.

*(بینش‌های بیشتر پس از تحلیل نهایی اضافه خواهند شد)*

---

## 🚀 نحوه اجرا و استفاده (How to Use)

**مراحل اجرا / Steps to run:**

1. **کلون کردن مخزن / Clone the repository:**
   ```bash
   git clone https://github.com/0hasanbagheri0/Data-Analysis-Portfolio.git
   cd Data-Analysis-Portfolio/projects/project-02-space-missions/
   ```
2. **نصب کتابخانه‌های مورد نیاز / Install required packages:**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```
3. **اجرای نوت‌بوک تحلیل / Run the analysis notebook:**

```bash
jupyter notebook analysis.ipynb
```
4. **برای اجرای اسکریپت پایتون (اختیاری) / Run Python script (optional):**

```bash
python analysis.py
```
# 🛠️ ابزارها و تکنولوژی‌ها (Technologies Used)
 دسته‌بندی (Category)	| کتابخانه/ابزار (Library/Tool)	| کاربرد (Usage)
|---|---|
| زبان برنامه‌نویسی	| Python 3.9+	| هسته اصلی تحلیل
| پردازش داده	| Pandas, NumPy	| تمیزکاری، دستکاری و محاسبات عددی 
| مصورسازی داده	| Matplotlib, Seaborn	| رسم نمودارهای حرفه‌ای 
| محیط توسعه	| Jupyter Notebook |	تحلیل تعاملی و مستندسازی
---
# 📚 منبع داده (Data Source)
## دیتاست: عملیات فضایی ۲۰۱۹-۲۰۲۰
---
## فرمت: CSV
---
## تعداد رکوردها: ۱۵۴ مأموریت
---
## ویژگی‌ها: تاریخ، نام شرکت، مکان، هزینه (میلیون دلار)، وضعیت
---
# 📝 روند انجام پروژه (Project Workflow)
## 1. تعریف مسئله و سوالات تحلیلی
## 2. دریافت و بارگیری داده
## 3. پاکسازی و پیش‌پردازش داده (مدیریت مقادیر خالی، تبدیل تاریخ‌ها)
## 4. تحلیل اکتشافی (EDA) و پاسخ به سوالات کلیدی
## 5. مصورسازی داده برای انتقال بصری یافته‌ها
## 6. استخراج بینش‌های کلیدی و جمع‌بندی نتایج
## 7. مستندسازی کامل در این فایل و نوت‌بوک
---
# 📋 برنامه توسعه آینده (Future Work)
## 1. اضافه کردن تحلیل پیشرفته‌تر با استفاده از آمار استنباطی
## 2. بررسی تأثیر عوامل اقتصادی و سیاسی بر موفقیت مأموریت‌ها
## 3. ایجاد یک داشبورد تعاملی با Plotly یا Dash
## 4. مقایسه با داده‌های سال‌های دیگر برای تحلیل روند بلندمدت
------
# 🤝 مشارکت (Contributing)
## این پروژه به عنوان بخشی از پورتفولیوی شخصی توسعه یافته است. با این حال، نظرات و پیشنهادات شما برای بهبود بسیار ارزشمند است.

## 1. مخزن را Fork کنید.
## 2. یک شاخه جدید ایجاد کنید (git checkout -b improve-analysis).
## 3. تغییرات خود را اعمال کنید (git commit -m 'Improve analysis').
## 4. به مخزن اصلی پوش کنید (git push origin improve-analysis).
## 5. یک Pull Request ایجاد کنید.
---
# 📜 مجوز (License)
## این پروژه تحت مجوز MIT منتشر شده است - برای جزئیات بیشتر به فایل LICENSE در ریشه مخزن مراجعه کنید.
---
# 👤 درباره من (About Me)
## من حسن باقری هستم، یک علاقه‌مند به حوزه تحلیل داده که در مسیر تبدیل شدن به یک متخصص داده گام برمی‌دارم. این پروژه بخشی از مسیر یادگیری من است.

📧 Email: hasan111bagheri@gmail.com

💼 GitHub: github.com/0hasanbagheri0

⭐ اگر این پروژه برای شما مفید بود یا پیشنهادی دارید، خوشحال می‌شوم که بشنوم!

