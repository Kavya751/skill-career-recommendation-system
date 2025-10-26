# Skill-Based Student Progress and Career Recommendation System

A mini project for tracking student certification progress, extracting skills, and recommending suitable career opportunities.

## 🎯 Project Objective

Many students complete online certification courses but struggle to:
- Track their acquired skills
- Align skills with career opportunities
- Identify skill gaps for desired jobs

This system solves these problems by:
1. Tracking student progress in certification courses
2. Extracting and categorizing learned skills
3. Matching students with suitable jobs/internships
4. Identifying skill gaps and recommending learning paths

## ✅ Current Implementation (25-30%)

### Completed Features:
- ✅ Student data collection and storage
- ✅ Job posting database with required skills
- ✅ Comprehensive skill dictionary (80+ skills)
- ✅ Skill extraction from course names
- ✅ Proficiency calculation (weighted by completion %, grade, time spent)
- ✅ Student skill profile builder
- ✅ Job matching algorithm using cosine similarity
- ✅ Skill gap analysis
- ✅ Data visualizations and reports

### Demo Statistics:
- **30 students** with 80+ course enrollments
- **20 job postings** from various companies
- **80+ technical skills** tracked across 8 categories
- **Average match accuracy:** ~65%

## 📊 Sample Outputs

1. **Student Skill Profile** - Bar chart showing proficiency in each skill
2. **Job Recommendations** - Top 5 matching jobs with match percentages
3. **Skill Gap Analysis** - Skills needed vs skills possessed
4. **Overall Statistics** - System-wide analytics

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** 
  - Pandas, NumPy (data handling)
  - Scikit-learn (TF-IDF, cosine similarity)
  - Matplotlib, Seaborn (visualizations)
- **Storage:** CSV files
- **Development:** Jupyter Notebook

## 📁 Project Structure
```
skill-career-recommendation-system/
├── data/
│   ├── student_data.csv
│   ├── jobs_data.csv
│   └── student_data_with_skills.csv
├── notebooks/
│   └── 01_data_creation.ipynb
├── outputs/
│   ├── student_profiles.csv
│   ├── recommendations.csv
│   ├── demo_summary.txt
│   └── *.png (visualizations)
└── README.md
```

## 🚀 Future Enhancements (70% remaining)

- Advanced NLP for better skill extraction
- Resume parsing capability
- Skill verification quiz system
- Interactive dashboard (Streamlit/Flask)
- Integration with learning platforms
- Real-time job scraping
- Machine learning-based recommendations

## 👥 Team

Team of 4 students - 5th Semester Mini Project

## 📝 License

Academic project for educational purposes

---

**Status:** 25-30% Complete | **Next Demo:** [Add date]
