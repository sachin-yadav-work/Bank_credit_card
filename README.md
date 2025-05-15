
# 📊 Voltrix Bank Credit Card Launch – Market Analysis & A/B Testing

### Customer Segmentation & A/B Testing of Voltrix Bank's New Credit Card Launch in India

---

## 📌 Project Overview

Voltrix Bank is planning to launch a new credit card in the Indian market. As the lead Data Scientist, the objective was to identify the most promising target segment for this launch using data-driven customer segmentation, followed by the design and analysis of an A/B test to measure the effectiveness of the launch campaign.

---

## 🚀 Project Phases

### ✅ Phase 1: Market Segmentation

- **Goal**: Identify the best customer segment for the credit card launch.
- **Process**:
  - Analyzed transaction behavior, credit scores, product preferences, and demographics.
  - Segmented customers based on factors such as age, income, gender, location, credit score, and purchase behavior.
  - Final target segment: **Age Group 18–25 years**.

#### 🎯 Target Segment Rationale:
- Lower credit card penetration – untapped potential.
- Average transaction sizes comparable to other groups.
- Higher adoption potential due to fewer existing credit card affiliations.

---

### ✅ Phase 2: A/B Testing for Launch Effectiveness

- **Objective**: Measure if the new credit card leads to higher average transaction amounts than the existing card.
- **Pre-Campaign Setup**:
  - Power analysis conducted.
  - Due to budget constraints, a test size of 100 customers was agreed upon.
  - Selected 100 customers aged 18–25 from a pool of 246.

- **A/B Testing Methodology**:
  - Randomly split the group into:
    - **Control Group**: Existing credit card users.
    - **Test Group**: New credit card users.
  - Measured **average amount spent** post-campaign for both groups.

- **Statistical Testing**:
  - Conducted hypothesis testing (t-test).
  - Verified assumptions including normality and variance.
  - Interpreted p-values and effect sizes.

---

## 📊 Key Insights

- Customers aged 18–25:
  - Represent ~25% of the user base.
  - Have lower credit histories and income.
  - Spend mainly on Electronics, Fashion & Apparel, and Personal Care.
- Significant behavioral differences found between test and control groups after campaign.
- A/B test results support the effectiveness of targeting this segment with the new product.

---

## 🛠 Tools & Technologies

- **Language**: Python
- **Data Manipulation**: pandas, numpy
- **Visualization**: seaborn, matplotlib
- **Statistical Analysis**: scipy.stats, statsmodels
- **Notebook**: Jupyter

---

## 📁 Repository Structure

```
├── Bank_credit_card_launch_SachinYadav.ipynb  # Main notebook with EDA, segmentation, and A/B testing
├── data/                                      # (If applicable) Directory for datasets
├── images/                                    # (If applicable) Visualizations and plots
└── README.md                                  # Project documentation
```

---

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/voltrix-creditcard-launch.git
   cd voltrix-creditcard-launch
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Bank_credit_card_launch_SachinYadav.ipynb
   ```
3. Run all cells to reproduce the analysis.

---

## 👨‍💼 Author

**Sachin Yadav**  
*Data Scientist | Credit & Risk Analytics | Customer Segmentation | A/B Testing*

---

## 📝 License

This project is licensed under the MIT License.
