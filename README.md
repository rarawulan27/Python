# A/B Testing in Python

This project analyzes a marketing dataset using statistical A/B testing and cohort-based user retention analysis.

## 🔬 Analysis Summary

- **A/B Testing** (ANOVA + Tukey HSD) was used to determine the most effective promotion strategy.
- **Cohort Analysis** was simulated using `LocationID` and weekly transaction data to estimate retention.

## 📊 Tools & Libraries
- Python (pandas, seaborn, scipy, statsmodels)
- Google Colab
- Matplotlib

## 📁 Files
- `cohort_analysis.ipynb`: Main notebook
- `WA_Marketing-Campaign.csv`: Dataset used (from Kaggle)

📉 Promosi 2 tidak hanya memiliki rata-rata terendah, tetapi juga performa yang secara statistik lebih rendah signifikan dibanding Promosi 1 dan 3.

🏆 Promosi 1 unggul secara rata-rata tertinggi dan konsisten (std dev relatif kecil).

📊 Promosi 3 mendekati performa Promosi 1, dan tidak berbeda signifikan berdasarkan uji Tukey.

-Berdasarkan analisis statistik deskriptif dan uji ANOVA dilanjutkan dengan Tukey HSD, Promosi 1 dan 3 terbukti secara signifikan menghasilkan penjualan lebih tinggi dibandingkan Promosi 2. Oleh karena itu, Promosi 2 sebaiknya ditinjau ulang atau dioptimalkan, sementara Promosi 1 dapat dipertahankan sebagai strategi unggulan.
