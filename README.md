# منصة تقييم الأداء الذكي - جامعة ديالى
## Smart Performance Evaluation Platform - University of Diyala

منصة ذكية لتقييم الأداء التراكمي لمنتسبي جامعة ديالى في قسم ضمان الجودة، مبنية بـ Streamlit مع واجهة عربية RTL احترافية.

A smart cumulative performance evaluation platform for University of Diyala staff in the Quality Assurance department, built with Streamlit with a professional Arabic RTL interface.

---

## ✨ الميزات الرئيسية | Key Features

- 📊 **لوحة معلومات تفاعلية** — KPIs، رسوم بيانية، أشرطة تقدم
- 👥 **إدارة المنتسبين** — إضافة، حذف، تعديل، عرض بطاقات أو جدول
- 📝 **التقييم الذاتي** — يُدخل المنتسب درجته الذاتية
- 📋 **تقييم المشرف** — مراجعة واعتماد الدرجات النهائية
- 📈 **التقييم التراكمي** — تقرير سنوات متعددة لكل منتسب
- 🤖 **التحليل الذكي بالذكاء الاصطناعي**:
  - تحليل الاتجاه (تحسن/تراجع)
  - التنبؤ بالأداء المستقبلي
  - كشف فجوة التقييم الذاتي
  - التصنيف الذكي المركب
  - التوصيات التلقائية
- 📊 **تقارير وإحصائيات** — مقارنات، هيستوجرام، تصدير شامل
- 📄 **تقارير PDF و Excel** — لكل منتسب
- 🔍 **بحث شامل** — بالاسم، الهاتف، الجهة
- 🌙 **الوضع الداكن** — Dark mode toggle
- ⚙️ **لوحة المشرف المحمية** — كلمة مرور لإعدادات الترميز
- 🖨️ **طباعة احترافية** — Print-ready CSS

## 🚀 التشغيل | Running

```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

ثم افتح: `http://localhost:8501`

## 🔐 كلمة مرور المشرف
**Admin Password:** `admin2026`

## 📁 هيكل المشروع | Project Structure

```
A4/
├── app.py                    # Main Streamlit application
├── requirements.txt          # Python dependencies
├── diyala_full_seal.png     # University logo
├── tahoma.ttf               # Arabic font
└── data/                    # JSON data store
    ├── affiliations.json
    ├── certificates.json
    ├── nicknames.json
    ├── positions.json
    ├── associates.json
    ├── evaluation_years.json
    └── evaluations.json
```

## 🛠️ التقنيات | Tech Stack

- **Streamlit** — Web framework
- **Pandas** — Data processing
- **Plotly** — Interactive charts
- **openpyxl** — Excel export
- **fpdf + arabic-reshaper** — Arabic PDF generation

## 👨‍💻 المطور | Developer

**أ.م. علي حسين فاضل** — استاذ مساعد
كادر وحدة تكنولوجيا المعلومات — قسم ضمان الجودة
جامعة ديالى

## 📜 الترخيص | License

© 2026 University of Diyala — All rights reserved
