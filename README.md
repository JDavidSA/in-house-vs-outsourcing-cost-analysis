<!-- MAIN TITLE -->
<h1 align="center">📊 In-House Operations vs. Outsourcing — Cost Analysis</h1>

<p align="center">
  An interactive <b>Power BI dashboard</b> comparing the monthly costs of <b>in-house operations</b> and <b>outsourcing</b> across operational activities.<br>
  The project highlights <b>potential cost savings</b>, supports <b>make-or-buy decisions</b>, and helps stakeholders evaluate opportunities for <b>operational efficiency</b>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Focus-Cost%20Optimization-17365D" alt="Cost optimization">
  <img src="https://img.shields.io/badge/Area-Business%20Intelligence-6355A4" alt="Business intelligence">
</p>

---

## 🧭 1. Introduction

Organizations often need to decide whether operational activities should be performed by internal teams or outsourced to specialized providers. A meaningful comparison requires visibility into **costs by activity**, **overall financial differences**, and the **trade-offs behind each option**.

This project presents an interactive **Power BI report** that compares two operating models—**in-house operations** and **outsourcing**—to reveal where the largest potential savings exist and support evidence-based operational planning.

**Business question:** *Which activities offer the greatest potential savings through outsourcing, and how significant is the overall cost difference?*

---

## 🎯 2. Project Objective

To develop an interactive cost-comparison dashboard that enables decision-makers to:

- Compare **monthly in-house and outsourcing costs** across operational activities
- Quantify **potential monthly and annual savings**
- Identify **high-impact activities** with the largest cost differences
- Explore the results using an **activity-level filter**
- Support **cost optimization and outsourcing decisions** with clear financial indicators

The report is intended as a **decision-support tool**, not as a recommendation to outsource every activity without further operational assessment.

---

## 🧪 3. What Was Done

### ✔ Comparative Cost Analysis
- Compared estimated **monthly costs** under two operating models
- Examined cost differences at both **total** and **individual activity** levels
- Summarized potential **monthly savings**, **percentage reduction**, and **annualized savings**

### ✔ Interactive Power BI Dashboard
Designed a Power BI report with four complementary components:

1. **KPI Cards — Cost and savings overview**
   - In-house operating costs, outsourcing costs, monthly savings, and estimated annual savings
2. **Clustered Horizontal Bar Chart — Monthly costs by activity**
   - Side-by-side comparisons that make differences between the two alternatives easy to identify
3. **Activity Filter — Focused exploration**
   - Allows users to review a selected activity or view the complete analysis
4. **Key Findings Panel — Decision-oriented storytelling**
   - Summarizes major savings opportunities and considerations before outsourcing

### ✔ Business Interpretation
- Identified the largest contributor to the observed cost difference
- Highlighted **scope, frequency, quality, and operational obligations** as factors to validate before a final decision

---

## 🛠️ 4. Tools & Technologies Used

- **Microsoft Power BI Desktop** — report development and interactive data visualization
- **Power BI report (.pbix)** — editable project file containing the report
- **KPI design and comparative analysis** — business performance assessment
- **Data storytelling** — communication of findings for decision-makers

> **Scope note:** The screenshot confirms the report's visual elements and displayed results. Specific data sources, Power Query transformations, and DAX measures are not documented here because the underlying `.pbix` file has not been reviewed.

---

## 📊 5. Key Results

### ✔ Overall Cost Comparison

| Indicator | Dashboard value |
|:--|--:|
| Monthly in-house operations cost | **$605.64 million** |
| Monthly outsourcing cost | **$234.99 million** |
| **Potential monthly savings** | **$370.65 million** |
| **Potential cost reduction** | **61.2%** |
| **Estimated annual savings** | **$4,447.77 million** |

*Values are transcribed from the Power BI dashboard. The screenshot shows a `$` symbol and amounts in millions, but does not specify the currency. Values are rounded as displayed; the annual estimate may therefore differ slightly from multiplying the rounded monthly savings by 12.*

### ✔ Largest Savings Opportunity: Brush Cleaning

- **In-house:** $470.03 million per month
- **Outsourcing:** $150.46 million per month
- **Potential difference:** **$319.57 million per month**
- This activity accounts for approximately **86.2% of the total monthly savings opportunity** shown in the report.

### ✔ Strategic Takeaway

The modeled outsourcing scenario shows a **61.2% lower overall monthly cost** than in-house execution. However, outsourcing decisions should also consider **service quality, provider capacity, activity scope, operating frequency, contractual terms, and execution risk**.

---

## 📊 6. Dashboard

### Power BI Dashboard Preview

<p align="center">
  <img src="assets/dashboard-preview.png" alt="In-House Operations vs. Outsourcing Power BI dashboard" width="100%">
</p>

<p align="center">
  The report combines <b>financial KPIs</b>, an <b>activity-based cost comparison</b>, and <b>decision-oriented findings</b> in one interactive Power BI view.
</p>

### Open the Interactive Power BI Report

📁 **[Download the Power BI project (.pbix)](In_House_vs_Outsourcing.pbix)**

1. Download the `.pbix` file from this repository.
2. Open the file in **Microsoft Power BI Desktop**.
3. Use **Filter by activity** to select an operational activity or view all activities.
4. Review the cost indicators, comparison chart, and key findings.

> **Important:** Add your original Power BI file to this repository using the name `In_House_vs_Outsourcing.pbix` for the link above to work. The starter package includes the README and preview image, **not** the original `.pbix`. If the report uses external data connections, reopening or refreshing it may require access to those sources.

### Repository Structure

```text
in-house-vs-outsourcing-cost-analysis/
│
├── README.md
├── In_House_vs_Outsourcing.pbix     # Add your original Power BI report
└── assets/
    └── dashboard-preview.png        # Dashboard screenshot
```

---

## 🔍 7. Insights & Conclusions

- **Outsourcing presents a substantial potential cost advantage** in the scenario represented by the dashboard.
- **Brush Cleaning is the main savings driver**, making it the most important activity to investigate in a more detailed financial and operational assessment.
- **Activity-level comparisons** help distinguish major opportunities from smaller cost differences and support more focused decision-making.
- **Annualized savings are estimates**, assuming the monthly cost difference remains broadly consistent over 12 months.
- **Financial savings alone are not sufficient** to justify outsourcing: decisions should validate service-level expectations, quality standards, contractual scope, and operational risk.

### ✔ Business Value

This Power BI project demonstrates how **business intelligence**, **cost comparison**, and **clear data visualization** can turn operational cost figures into actionable insights for **resource allocation**, **efficiency planning**, and **make-or-buy evaluations**.
