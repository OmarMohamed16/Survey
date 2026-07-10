Survey on Preferred Tracks of Study and Career Paths Among Computer Science University Students

## 📋 Project Overview

This project presents a comprehensive survey analysis conducted among Computer Science university students to understand their preferences, motivations, and career aspirations regarding academic tracks and career paths. The survey collected **250 responses** from CS students across different academic levels, providing valuable insights into the evolving landscape of CS education and career planning.

### 🎯 Project Objectives

The survey aimed to answer five key research questions:

1. **Track Preferences**: What are the most popular tracks of study among CS students, and how do these preferences vary by academic level?

2. **Influencing Factors**: What factors influence students' choices of specialization (personal interest, job market demand, salary prospects, etc.)?

3. **Career Aspirations**: What are the career goals of CS students, and how do they align with their chosen tracks?

4. **Curriculum Alignment**: Are there gaps between the university's curriculum and the skills required for students' desired career paths?

5. **Emerging Trends**: Are students interested in emerging fields like Quantum Computing, Blockchain, or Ethical AI, and how prepared do they feel?

---

## 📊 Key Findings

### Demographics
- **Gender Distribution**: 52% Female, 48% Male (130 females, 120 males)
- **Academic Levels**: 
  - Third-year: 95 students
  - Fourth-year: 83 students
  - Second-year: 42 students
  - First-year: 30 students

### Track Preferences
- **Most Popular Track**: Data Science (42%)
- **Second Most Popular**: Web Development (26%)
- **Other Tracks**: AI (14%), Cybersecurity (9%), Mobile Development (9%)

### Factors Influencing Track Choice
- **Personal Interest**: 58% (primary factor)
- **Market Demand**: 21%
- **Salary Prospects**: 12%
- **Flexibility**: 8%

### Student Uncertainty
- **Track Choice Hesitancy**: 
  - 46% "Hesitant"
  - 28% "Very Hesitant"
  - Only 17% "Slightly Hesitant"

### Work Preferences
- **Remote Work**: 59% prefer fully remote positions
- **Hybrid**: 21%
- **On-site**: 13%
- **Freelance**: 7%
- **LinkedIn** dominates job searches (75%)

### Career Priorities
- **Industry Demand**: 70% rate as "High" importance
- **Salary**: 60% rate as "High" importance

### Academic Resources
- **Insufficient Resources**: 83% of students feel inadequately resourced
- **Adequate Resources**: Only 17%

### Student Self-Assessment (Average Ratings)
- **Self-Learning Capabilities**: 4.15/5
- **Goal Confidence**: 3.61/5
- **Interview Preparedness**: 3.56/5
- **Certification Importance**: 3.98/5

### Internship Experience
- **Completed Internships**: 145 students (58%)
- **No Internship Experience**: 105 students (42%)
- First-year access: Only 14.8%
- Fourth-year access: 72.3%

### Curriculum Satisfaction
- **Satisfied + Very Satisfied**: 129 (52%)
- **Dissatisfied + Very Dissatisfied**: 76 (30%)
- **Neutral**: 45 (18%)

---

## 📈 Statistical Analysis

### Chi-Square Test: Gender vs Track Choice
- **Chi2 Statistic**: 2.95
- **P-Value**: 0.566 (> 0.05)
- **Conclusion**: No significant association between gender and preferred track

### Chi-Square Test: College Satisfaction vs Skill Gaps
- **Chi2 Statistic**: 80.40
- **P-Value**: < 0.001
- **Conclusion**: Strong significant association (reject null hypothesis)

### ANOVA: Goal Confidence by Academic Level
- **F-statistic**: 1.04
- **P-Value**: 0.376
- **Conclusion**: No significant difference in goal confidence across academic levels

### Correlations
- **Goal Confidence ↔ Interview Prep**: r = 0.753 (strong correlation)
- **Self-Learning ↔ Certification Value**: r = 0.653 (strong correlation)

---

## 🔍 Clustering Analysis

Three distinct student clusters identified using K-means:

1. **Cluster 0: "High Achievers"** 
   - Highest goal confidence, interview preparedness, and self-learning
   - Highly value certifications (4.70/5)

2. **Cluster 1: "Uncertain Learners"**
   - Lowest in all metrics
   - Least interested in certifications
   - Potential risk group for disengagement

3. **Cluster 2: "Certification-Focused but Less Confident"**
   - High certification importance but lower interview preparedness
   - Need practical skill development

---

## 📱 Project Files

### Data Files
- **`Final_Survey_Data.csv`**: Raw survey data (250 responses)
  - 16 columns covering demographics, preferences, and self-assessments
  - Columns: gender, academic_level, interest_in_academic_path, preferred_track, track_choice_hesitancy, track_choice_factor, has_sufficient_resources, has_practical_internship, college_satisfaction, college_to_skill_gap, self_learning_scale, interest_in_emerging_fields, industry_demand_importance, salary_importance, goal_confidence, interview_preparedness, certification_importance, preferred_work_type, preferred_platform

### Documentation
- **`Final_Survey_Report.docx`**: Comprehensive project report
  - Introduction, objectives, methodology
  - Data cleaning and analysis process
  - Visualizations and statistical tests
  - Recommendations and conclusions

- **`SURVEY_PRESENTATION.pptx`**: Project presentation
  - Key findings summary
  - Visual charts and graphs
  - Statistical analysis results
  - Recommendations

### Dashboard
- **Power BI Dashboard**: Interactive visualization dashboard
  - Key metrics at a glance
  - Comparative analysis tools
  - Trend identification
  - Interactive exploration capabilities

---

## 🛠️ Technologies Used

- **Data Collection**: Google Forms
- **Data Analysis**: Python (Pandas, NumPy, Scikit-learn, SciPy)
- **Visualization**: Matplotlib, Seaborn, Power BI
- **Statistical Analysis**: Chi-square tests, ANOVA, PCA, K-means clustering, Linear Regression
- **Documentation**: Microsoft Word, PowerPoint

---

## 🚀 Key Recommendations

### For Universities:
1. **Address Resource Deficiencies**: 83% of students report insufficient academic resources
2. **Provide Track Exploration Opportunities**: Reduce decision paralysis through workshops
3. **Enhance Practical Skill Development**: Bridge the theory-to-practice gap
4. **Target Second-Year Support**: Address the satisfaction slump observed in second year
5. **Strengthen Internship Programs**: Especially for first-year students

### For Students:
1. **Seek Early Internship Opportunities**: Gain professional experience early
2. **Develop Self-Learning Skills**: Average rating of 4.15/5 shows readiness
3. **Consider Both Passion and Market Factors**: Balance intrinsic and practical factors
4. **Leverage LinkedIn**: 75% of peers use it for job searches
5. **Pursue Certifications**: High importance rating (3.98/5) indicates value

---

## 📄 Dashboard Features

The Power BI dashboard includes:

- **Quick Insights**: Snapshot of learning behaviors, career preferences, and satisfaction
- **Comparative Analysis**: Compare metrics (e.g., self-learning vs. interview preparedness)
- **Trend Identification**: Patterns across student segments
- **Interactive Exploration**: Filter by gender, track, academic level, etc.

