# Employability Analytics Tool for Datascience
![image](https://github.com/user-attachments/assets/706aad6f-4f5b-4436-a5f6-95839ccbcf69)

## 📌 Overview

The Employability Analytics Tool is a data-driven solution designed to help mid-career professionals optimize their career decisions. By leveraging job market data, the tool provides actionable insights for career transitions, skill development, salary benchmarking, industry trends, and job security analysis.

## 🚀 Key Features

- **Skills Assessment Module:** Identifies current skills, skill gaps, and recommended courses.
- **Career Path Modeling:** Maps potential career transitions and required qualifications.
- **Salary Benchmarking:** Provides industry-specific salary comparisons and location-based adjustments.
- **Market Trend Analysis:** Analyzes industry growth rates, job postings, and demand for skills.
- **Job Security Predictor:** Evaluates company stability, industry risks, and job turnover rates.

## 📖 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Structure](#data-structure)
- [Data Sources](#data-sources)
- [Features](#features)
- [Live Dashboard](#live-dashboard)
- [Contributing](#contributing)
- [License](#license)

## 🛠 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/employability-analytics-tool.git
   cd employability-analytics-tool
   ```
2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🎯 Usage

Run the application with:

```bash
python app.py
```

## 📊 Data Structure

The tool utilizes structured data across multiple tables:

### Job Postings

| Variable         | Type         | Description                  |
| ---------------- | ------------ | ---------------------------- |
| Job Title        | String       | Title of the job role        |
| Industry         | String       | Industry sector              |
| Location         | String       | City/State of the job        |
| Salary Range Min | Float        | Minimum salary offered       |
| Salary Range Max | Float        | Maximum salary offered       |
| Required Skills  | List[String] | Skills required for the job  |
| Posted Date      | Date         | Date when the job was posted |

### Candidate Profiles

| Variable            | Type         | Description                              |
| ------------------- | ------------ | ---------------------------------------- |
| Candidate ID        | Integer      | Unique identifier for each candidate     |
| Current Skills      | List[String] | Skills the candidate currently possesses |
| Desired Skills      | List[String] | Skills the candidate wants to develop    |
| Current Job Title   | String       | Current role of the candidate            |
| Years of Experience | Integer      | Total years of work experience           |

## 📈 Data Sources

The tool aggregates data from multiple sources:

1. **Job Market Platforms:** LinkedIn, Indeed, industry job boards.
2. **Industry Reports:** World Economic Forum reports, market analysis.
3. **Professional Networks:** Career progression insights.
4. **Educational Platforms:** Skill development resources.
5. **Salary Databases:** Compensation benchmarks and trends.
6. **Uploaded Data:** The tool allows users to upload their own structured datasets, such as CSV files containing job postings, salaries, and industry-specific information.
   Data source link

## 🏆 Features

- **Interactive Career Maps:** Visual representations of potential career paths.
- **Skill Gap Analysis Charts:** Compare current vs. required skills.
- **Salary Range Visualizations:** Industry and role-specific compensation data.
- **Trend Analysis Graphs:** Market movements and projections.
- **Skills Heat Maps:** Representation of in-demand skills by industry.
- **Personalized Dashboard:** Customizable career metrics view.
- **Real-time Job Market Scanner:** Monitors relevant opportunities.

## 📊 Live Dashboard

We are creating our Dashboard in Mircosoft Power Bi tool and still its under construction stage.

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

This README provides a comprehensive guide for setting up and using the Employability Analytics Tool, making it easy for professionals to navigate their career paths effectively.

# Employability-Analytics-Tool-for-DATASCIENCE
Employability Analytics Tool for DATASCIENCE
