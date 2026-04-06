# 🌟 Smart Campus Insights - AI-Powered Campus Analytics Dashboard

**Transform raw campus data into actionable insights with beautiful visualizations and ML predictions!**

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Streamlit App](https://static.streamlit.io/badges/featured.svg)](https://share.streamlit.io/)

## ✨ Features

### 📊 **Interactive Dashboard**
- **Student Filters** - Select specific students across all metrics
- **Real-time Charts** - Dynamic updates with filtered data
- **Responsive Design** - Perfect on desktop & mobile

### 📈 **Attendance Analysis**
- **Trend Lines** - Track attendance patterns over time
- **Status Breakdown** - Present vs Absent visualization
- **Date-wise Insights** - Identify peak attendance days

### 🎓 **Event Participation**
- **Popularity Ranking** - Top events by participation
- **Event Analytics** - Measure engagement across campus events
- **Bar Charts** - Clear visual representation

### 💻 **LMS Usage Metrics**
- **Session Analysis** - Average duration per student
- **Content Consumption** - Pages viewed statistics
- **Data Table** - Detailed student-wise breakdown

### 🤖 **ML-Powered Predictions**
- **Engagement Risk Model** - Decision Tree Classifier
- **Real-time Prediction** - Input form for new student data
- **Classification Report** - Model accuracy metrics
- **Risk Assessment** - At Risk vs Engaged status

## 🖼️ Screenshots / Demo

### 📱 Dashboard Overview
*(Add screenshot: Main dashboard with sidebar filters)*

### 📊 Attendance Trends
```
[Placeholder for line chart screenshot]
```

### 🎓 Event Stats
```
[Placeholder for bar chart screenshot]
```

### 🤖 ML Prediction
```
[Placeholder for prediction interface screenshot]
```

## 📋 **Dataset Overview**

| File | Description | Columns |
|------|-------------|---------|
| `attendance_logs.xlsx` | Daily attendance records | StudentID, Date, Status |
| `event_participation.xlsx` | Campus event registrations | StudentID, EventName |
| `lms_usage.xlsx` | Learning Management System logs | StudentID, SessionDuration, PagesViewed |

## 🛠️ **Tech Stack**

```python
streamlit           # Interactive web dashboard
pandas              # Data processing & Excel handling
matplotlib/seaborn  # Visualizations
scikit-learn        # ML Decision Tree Classifier
openpyxl            # Excel file reader
```

## 🚀 **Quick Start (Local)**

```bash
# 1. Clone/Download repo
git clone https://github.com/Mayurii07/Smart-Campus-Insights.git
cd Smart-Campus-Insights

# 2. Setup virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or
venv\\Scripts\\activate  # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run smart_campus_insights_app.py
```

**App opens at: `http://localhost:8501`**

## ☁️ **Deploy to Streamlit Cloud (Hosted)**

1. Fork/Use this repo on GitHub
2. Visit [share.streamlit.io](https://share.streamlit.io/)
3. Sign in with GitHub
4. **New app** → Select `Smart-Campus-Insights` repo
5. Set **Main file path**: `smart_campus_insights_app.py`
6. **Deploy!** Get instant shareable URL like `https://yourcampus.streamlit.app`

## 🔍 **App Structure**

```
smart-campus-insights-main/
├── smart_campus_insights_app.py     # Main Streamlit app
├── requirements.txt                 # Dependencies
├── attendance_logs.xlsx            # Attendance data
├── event_participation.xlsx        # Events data
├── lms_usage.xlsx                  # LMS usage data
├── README.md                       # 📄 You're reading it!
├── .gitignore
└── TODO.md                         # Progress tracker
```

## 🎯 **ML Model Details**

**Decision Tree Classifier** trained on:
- **Absence Rate** (target < 20% = Engaged)
- **Session Duration** (avg minutes)
- **Pages Viewed** (content consumption)

**Features:**
- Instant prediction interface
- Model performance metrics
- Risk classification (Engaged / At Risk)

## 🌟 **Future Enhancements**

- [ ] Add more ML models (Random Forest, XGBoost)
- [ ] Interactive student comparison charts
- [ ] Export reports (PDF/Excel)
- [ ] Real-time data integration
- [ ] Advanced filtering (date range, course-wise)
- [ ] Predictive alerts dashboard
- [ ] Multi-campus support
- [ ] Admin data upload interface

## 📚 **Perfect For**
- **University Admins** - Monitor student engagement
- **Academic Advisors** - Identify at-risk students
- **Event Coordinators** - Measure participation
- **Data Analysts** - Campus health metrics

## 🤝 **Contributing**
1. Fork the repo
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 **License**
MIT License - Free to use, modify, and deploy!

## 👩‍💻 **Author**
**Mayurii07** - Campus Data Enthusiast

---

⭐ **Star this repo if you found it useful!** 🚀

**Deploy your own copy now: [Streamlit Cloud](https://share.streamlit.io/)**
