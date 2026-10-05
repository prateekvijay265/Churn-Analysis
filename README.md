<div align="center">

<!-- Animated Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=250&section=header&text=ChurnIQ%20Analytics&fontSize=70&fontAlignY=35&animation=twinkling&fontColor=ffffff" width="100%" alt="ChurnIQ Banner" />

<!-- Animated Typing Text -->
<a href="https://churn-analysis-six.vercel.app/">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=600&size=22&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=800&lines=Advanced+Customer+Churn+Analysis;Predict.+Prevent.+Retain.;Actionable+Insights+for+SaaS+Businesses;ML-Driven+Forecasts+%26+Behavioral+Trends" alt="Typing SVG" />
</a>

**A breathtaking, fully interactive dashboard to identify subscription cancellation patterns, evaluate user engagement, and determine key factors that lead to churn.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Site-34d399?style=for-the-badge&logo=vercel&logoColor=white)](https://churn-analysis-six.vercel.app/)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-111624?style=for-the-badge&logo=github&logoColor=white)](https://github.com/prateekvijay265/Churn-Analysis)

</div>

---

## 🌟 Overview

**ChurnIQ** transforms raw customer data into a visual narrative. By mapping out engagement decay, analyzing cancellation reasons, and predicting future churn probability, this dashboard provides product and success teams with the exact metrics they need to deploy targeted retention strategies.

### 📸 Dashboard Sneak Peek

<div align="center">
  <img src="assets/overview.png" alt="Overview Dashboard" width="800" style="border-radius: 12px; box-shadow: 0 4px 24px rgba(0,0,0,0.4); margin-bottom: 20px;"/>
  <br/>
  <img src="assets/behavior.png" alt="Behavior Trends" width="800" style="border-radius: 12px; box-shadow: 0 4px 24px rgba(0,0,0,0.4); margin-bottom: 20px;"/>
  <br/>
  <img src="assets/segments.png" alt="Customer Segments" width="800" style="border-radius: 12px; box-shadow: 0 4px 24px rgba(0,0,0,0.4); margin-bottom: 20px;"/>
  <br/>
  <img src="assets/predictions.png" alt="Predictive Insights" width="800" style="border-radius: 12px; box-shadow: 0 4px 24px rgba(0,0,0,0.4);"/>
</div>

---

## ⚙️ How It Works & Data Flow

ChurnIQ simulates a data pipeline that ingests, scores, and visualizes customer risk. Here is how the conceptual architecture flows from raw data to actionable business intelligence:

```mermaid
graph TD
    subgraph Data Sources
        A[User Analytics] -->|Login & Feature Usage| D(Data Processing Engine)
        B[CRM & Billing] -->|Subscription Tier & MRR| D
        C[Support Desk] -->|Ticket Volume & NPS| D
    end
    
    subgraph ML & Analytics Core
        D --> E{Risk Scoring Model}
        D --> F[Behavioral Pattern Analysis]
        E --> G[High-Risk Segments]
        F --> H[Engagement Decay Metrics]
    end
    
    subgraph ChurnIQ UI Presentation
        G --> I[Segment Risk Table]
        H --> J[Behavior Trends Charts]
        E --> K[90-Day ML Forecast]
        I & J & K --> L((Actionable Retention Strategies))
    end

    style D fill:#6366f1,stroke:#ffffff,stroke-width:2px,color:#fff
    style E fill:#8b5cf6,stroke:#ffffff,stroke-width:2px,color:#fff
    style L fill:#34d399,stroke:#ffffff,stroke-width:2px,color:#fff
```

---

## 🚀 Key Features

### 1️⃣ Executive Overview
*   **Real-time KPIs**: Overall churn rate, monthly cancellations, at-risk users, and recovery rates displayed with micro-sparklines.
*   **Temporal Tracking**: 12-month churn vs. retention timeline comparison.

### 2️⃣ Behavioral Trends
*   **Engagement Funnels**: Days-to-churn decay timelines post-last-activity.
*   **Feature Heatmaps**: Radar-style distribution of feature usage separating retained users from churned users.
*   **Support Correlation**: Mapping support ticket volume against churn likelihood.

### 3️⃣ High-Risk Customer Segments
*   **Granular Filters**: Interactive risk table breaking down cohorts by primary driver (e.g., Budget Sensitivity, Feature Parity Gap).
*   **Action Recommendations**: Automated strategy suggestions per risk segment.

### 4️⃣ ML Predictive Forecasts
*   **90-Day Projections**: Forward-looking churn line with upper/lower confidence bounds.
*   **Feature Importance Ranking**: See exactly *what* factors (e.g., Days since last login, NPS score) are weighting the ML risk model.

---

## 🛠️ Technology Stack

Built with a lightning-fast, zero-build-step frontend stack for absolute maximum performance and portability:

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</div>

---

## 💻 Local Setup & Development

Want to run it locally? It takes less than 5 seconds.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prateekvijay265/Churn-Analysis.git
   ```
2. **Navigate to the directory:**
   ```bash
   cd Churn-Analysis
   ```
3. **Run it:**
   Simply double click the `index.html` file to open it in your browser, or use a live server extension in VSCode for hot-reloading.

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=111624&height=100&section=footer&text=Designed%20to%20predict,%20built%20to%20retain.&fontSize=20&fontColor=6366f1" width="100%" />
</div>
