# 🎵 DataWave Music: Customer Engagement & Churn Analysis

A comprehensive data analysis project examining customer churn patterns and retention strategies for DataWave Music, a streaming platform serving global markets.

## 📊 Project Overview

This project analyzes customer behavior, churn patterns, and engagement metrics across DataWave Music's subscriber base to identify actionable insights for reducing churn and improving retention.

**Author:** Prajwol Khadka

---

## 🎯 Key Metrics

| Metric | Value |
|--------|-------|
| **Overall Churn Rate** | 30.0% |
| **Retention Rate** | 70.0% |
| **Average Weekly Listening** | 10.03 hours |
| **Average Satisfaction Score** | 3.18/5 |

---

## 🔍 Key Findings

### The Satisfaction Paradox

A counterintuitive discovery: satisfaction scores show a **weak positive correlation (+0.05) with churn**. This paradox can be explained by:

- **Expectation-Reality Gap**: Satisfied users have higher expectations that aren't consistently met
- **Alternative Seeking**: Happy users feel confident exploring competitors
- **Survey Response Bias**: Churning users may give positive exit surveys
- **Status Quo Bias**: Dissatisfied users stay due to high switching costs

### Correlation Analysis

| Variable | Correlation with Churn | Interpretation |
|----------|------------------------|----------------|
| Total Songs Played | +0.02 | Very weak positive |
| Satisfaction Score | +0.05 | Very weak positive |
| Monthly Fee | -0.02 | Very weak negative |
| Age | -0.01 | Very weak negative |
| Listening Hours | 0.00 | No correlation |

**Insight:** Churn depends on factors beyond simple usage metrics or demographics, such as subscription type, region, and customer service interactions.

---

## 🌍 Regional Analysis

### Market Segmentation

**Developed Markets** (US, UK)
- Churn Rate: 29.6%
- Average Fee: $7.7
- Average Hours: 10.5hrs

**Emerging Markets** (Others)
- Churn Rate: 30.3%
- Average Fee: $7.6
- Average Hours: 9.8hrs

### Regional Behavioral Patterns & Recommendations

#### 🌍 Africa
- **Focus:** Data-efficient streaming
- **Actions:** Enable offline modes, prioritize mobile optimization

#### 🌏 South Asia
- **Focus:** Community-oriented features
- **Actions:** Promote family/group plans, introduce loyalty programs, invest in local content

#### 🇪🇺 Europe
- **Focus:** Quality & personalization
- **Actions:** Maintain high personalization, ensure quality streaming, expand diverse music catalog

#### 🌎 Latin America
- **Focus:** Value & cultural relevance
- **Actions:** Offer competitive pricing, highlight local artists, add social engagement features

---

## 👥 Cross-Segment Analysis

### Age Group Churn by Subscription Type

| Age Group | Family | Free | Premium | Student |
|-----------|--------|------|---------|---------|
| 13-18 | 38% | 33% | **42%** | 29% |
| 18-24 | 37% | 25% | 29% | **41%** |
| 25-34 | 28% | 23% | 26% | 19% |
| 35-44 | 24% | 33% | 32% | 28% |
| 45-54 | 22% | 22% | 25% | 32% |
| 55-64 | **37%** | 24% | 32% | **38%** |

**Critical Pattern:** Young teens (13-18) on Premium plans and seniors (55-64) on Student/Family plans show the highest churn rates, indicating subscription-age mismatches.

---

## 📈 Temporal Analysis

### User Count and Churn Rate by Join Quarter

**Key Insights:**

1. **2023 Q4**: Inverse correlation where user count is decreasing while churn rate is rising
2. **2024 Q2**: Critical recent issue with user onboarding or early experience
3. **Declining Acquisition**: Number of new users has fallen sharply

**Positive Trend:** Newer cohorts (excluding Q2 2024) show lower churn rates, suggesting improvements in onboarding, product features, or user targeting.

**Urgent Action Required:** Immediately investigate the 2024 Q2 onboarding experience to understand the cause of high early churn for this cohort.

---

## 🧠 Cognitive Biases in User Behavior

| Bias | Impact | Users Affected | Retention Rate |
|------|--------|----------------|----------------|
| **Status Quo Bias** | Strongest | 98 users (26.8% of long-tenure) | High |
| **Social Proof** | Significant | - | - |
| **Choice Paralysis** | Significant | - | - |
| **Sunk Cost** | Moderate | 43 users | 72.1% active |
| **Anchoring** | Weakest | - | - |

**Key Insight:** Status Quo bias is the strongest cognitive influence on retention behavior.

---

## 💡 Strategic Recommendations

### 1. Resolve the Subscription Mismatch Paradox

**Problem:** Highest churn exists in specific age-subscription mismatches

**Action:**
- Immediately review and re-target 13-18 year-olds on Premium plans (42% churn)
- Address 55-64 year-olds on Student/Family plans (37-38% churn)

**Goal:** Offer age-appropriate, value-aligned plans to these high-risk groups

### 2. Localize & Optimize for Data Constraints

**Insight:** Simple usage metrics show very weak correlation with churn

**Action:**
- Implement hyper-localized product fixes based on regional patterns
- **Priority Focus on Africa:** Enable and promote offline streaming modes and mobile optimization

**Goal:** Solve data-efficiency issues in bandwidth-constrained markets

### 3. Leverage Behavioral Biases for Retention

**Insight:** Status Quo Bias is the strongest cognitive influence

**Actions:**
- Introduce high-value, longer-term annual subscription plans
- Create 'sunk cost' features (e.g., personalized archives, year-in-review features)

**Goal:** Increase perceived switching costs and capitalize on Status Quo effect

---

## 📊 Key Metrics to Track

1. **Churn Rate of 13-18 Premium Segment** - Monitor subscription-age mismatch
2. **Annual Plan Adoption Rate** - Measure Status Quo bias utilization
3. **Africa/Emerging Market Churn Rate** - Track regional optimization effectiveness

---

## 🎓 Key Takeaways

| Finding | Implication |
|---------|-------------|
| **Satisfaction ≠ Retention** | Don't rely on NPS alone |
| **Culture Matters** | Regionalize approach |
| **Bias is Opportunity** | Build positive switching costs |
| **Usage ≠ Retention** | Look beyond simple usage metrics |

---

## 🛠️ Technologies & Methods

- **Data Analysis:** Python (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn
- **Statistical Analysis:** Correlation analysis, cohort analysis, behavioral segmentation
- **Presentation:** PowerPoint with data-driven visualizations

---

---

## 🚀 Next Steps

1. **Immediate Actions:**
   - Investigate 2024 Q2 onboarding issues
   - Launch age-appropriate subscription recommendations
   - Pilot offline mode in African markets

2. **Medium-term Initiatives:**
   - Develop annual subscription plans
   - Create personalized retention features
   - Implement regional content strategies

3. **Long-term Strategy:**
   - Build predictive churn models
   - Develop behavioral segmentation framework
   - Establish continuous monitoring dashboards

---

## 📧 Contact

**Prajwol Khadka**
prazolkhadka67@gmail.com
https://www.linkedin.com/in/prajwol-khadka-12ba6b320/
For questions or collaboration opportunities, please reach out via mail or linkedin.

---

## 📄 License

This project is available for educational and portfolio purposes.
