# KPI Framework, Business Experiment Analysis \& Decision Recommendation

## Business Analytics Capstone Project

A/B Experiment Analysis | KPI Framework | Executive Decision Recommendation

## 

## 1\. Repository Information



| Item | Details |

|------|---------|

| Repository | nipunbanga\_2511197\_part2\_kpi\_experiment |

| Course | Business Analytics with Gen \& Agentic AI |

| Assignment | Part 2 – KPI Framework \& Business Experiment Analysis |

| Project Type | Business Analytics Case Study |



### 

## 2\. Table of Contents



1\. Repository Information

2\. Table of Contents

3\. Executive Summary

4\. Business Value

5\. Project Highlights

6\. Business Context

7\. Business Problem Statement

8\. Business Objectives

9\. Success Criteria

10\. Stakeholder Analysis

11\. Project Scope

12\. Out of Scope

13\. Dataset Overview

14\. Data Validation Methodology

15\. North Star Metric

16\. Guardrail Metrics

17\. KPI Tree Explanation

18\. Experiment Design

19\. Statistical Methodology

20\. Segment Analysis

21\. Business Risks

22\. Recommendation Framework

23\. Repository Structure

24\. Project Deliverables

25\. Assumptions

26\. Limitations

27\. Future Enhancements

28\. References

29\. Executive Conclusion

30\. Repository Status



## 3\. Executive Summary



This repository presents a comprehensive business analytics case study that evaluates the effectiveness of a redesigned onboarding and activation campaign for a subscription-based digital product. The analysis applies a structured experimentation framework combining KPI design, statistical hypothesis testing, guardrail evaluation, and executive decision-making.

The primary objective is to determine whether the redesigned onboarding experience should be launched to all users based on measurable business outcomes rather than intuition. The recommendation considers commercial performance, statistical significance, customer experience, and operational sustainability to support evidence-based product decisions



## 4\. Business Value



This analysis enables business leaders to make evidence-based rollout decisions by combining statistical significance, KPI performance, and customer experience metrics into a single decision framework.



## 5\. Project Highlights



This project delivers a complete business experimentation framework for evaluating a subscription-based onboarding campaign. The repository includes:



\- 📊 KPI Framework aligned with business objectives

\- ⭐ North Star Metric selection and justification

\- 🌳 Executive KPI Tree with business drivers and guardrail metrics

\- 🧪 End-to-end A/B Experiment Analysis

\- 📈 Statistical Hypothesis Testing using a Two-Proportion Z-Test

\- 🌍 Segment-Level Performance Analysis

* 🛡️ Guardrail Metric Evaluation
* 📑 Executive Recommendation supported by data


## 6\. Business Context

For subscription-based digital products, sustainable growth depends on efficiently converting new users into long-term paying customers. The onboarding experience is a critical stage in this journey because it directly influences activation, engagement, conversion, and early customer satisfaction.



To improve user activation, the company introduced a redesigned onboarding campaign and evaluated its effectiveness using a randomized A/B experiment. Rather than relying on assumptions, leadership intends to use quantitative evidence to determine whether the redesigned experience should replace the existing onboarding flow.
• Control Group – Existing onboarding

• Treatment Group – Redesigned onboarding



## 7\. Business Problem Statement

The organization must determine whether the redesigned onboarding experience delivers sufficient business value to justify a full production rollout.



The decision impacts Product Management, Marketing, Customer Success, Engineering, Finance, and Executive Leadership. Before deployment, leadership requires evidence that the redesigned experience increases paid conversion while maintaining healthy customer experience and operational performance.



The recommendation must therefore be supported by statistically significant results, positive business KPIs, stable guardrail metrics, and consistent performance across customer segments.



## 8\. Business Objectives

The analysis is designed to achieve the following objectives:



1\. Evaluate whether the redesigned onboarding experience improves Paid Conversion Rate.

2\. Measure improvements in user activation through Trial Start Rate and Onboarding Completion Rate.

3\. Assess the commercial impact using Average Revenue Per User (ARPU) and Average Revenue Per Paying User (ARPPU).

4\. Monitor customer experience using Engagement Score, Refund Rate, and Support Ticket Rate.

5\. Validate business improvements using statistical hypothesis testing.

6\. Identify high-performing customer segments for potential phased rollout.

7\. Deliver an evidence-based executive recommendation supported by measurable business outcomes.

### 

## 9\. Success Criteria 



The experiment will be considered successful if:



\- Paid Conversion Rate improves significantly.

\- Guardrail metrics remain stable.

\- Customer engagement increases.

\- Revenue quality is maintained.

\- Statistical significance is achieved.



## 10\. Stakeholder Analysis

| Stakeholder | Primary Interest |

|--------------|------------------|

| Executive Leadership | Revenue growth and strategic decisions |

| Product Team | Onboarding performance |

| Marketing | Campaign effectiveness |

| Engineering | Production rollout |

| Customer Success | Customer experience |

| Finance | Commercial performance |

| Business Analytics | Statistical validation |



## 11\. Project Scope

This project includes:

* KPI Framework
* North Star Metric
* Data Validation
* Experiment Analysis
* Statistical Testing
* Guardrail Evaluation
* Segment Analysis
* Executive Recommendation

## 

## 12\. Out of Scope

This project does not include:

\- Long-term churn prediction

\- Customer Lifetime Value modelling

\- Marketing attribution analysis

\- Pricing optimization

\- Cross-product behavioral analysis

## 

## 13\. Dataset Overview

The dataset contains anonymized user-level observations collected during a controlled A/B experiment conducted on a subscription-based digital product.



Each record represents a unique user assigned to either the Control Group or the Treatment Group. The dataset includes behavioral, operational, and financial variables required to evaluate acquisition, activation, monetization, engagement, and customer experience.



### Key Attributes

* User ID
* Experiment Group
* Region
* Device Type
* Traffic Source
* Plan Type
* Landing Page Visit
* Trial Start
* Onboarding Completion
* Paid Conversion
* Revenue
* Refund Request
* Support Ticket
* Engagement Score
* Days to Convert

## 

## 14\. Data Validation Methodology

Before analysis, the dataset is validated using the following quality checks:

1. Missing value assessment
2. Duplicate User ID detection
3. Binary value validation (0/1 fields)
4. Revenue outlier analysis using the IQR method
5. Experimental group balance
6. Segment distribution review

These checks ensure that downstream KPI calculations and statistical tests are based on reliable data.

## 

## 15\. North Star Metric

## Paid Conversion Rate

**Definition**

Paid Conversion Rate = Converted Users / Total Users



### Why it was selected

The Paid Conversion Rate is the primary indicator of successful monetization. Improvements in this metric directly contribute to recurring subscription revenue and align with the company's strategic growth objectives.



# Supporting KPIs

The following KPIs help explain changes in the North Star Metric:



| KPI | Business Purpose |

|------|------------------|

| Landing Page Visit Rate | Measures campaign reach |

| Trial Start Rate | Measures activation intent |

| Onboarding Completion Rate | Measures onboarding effectiveness |

| Average Revenue Per User (ARPU) | Measures monetization efficiency |

| Average Revenue Per Paying User (ARPPU) | Measures value of paying users |

| Engagement Score | Measures early product adoption |

| Average Days to Convert | Measures conversion efficiency |





# 16\. Guardrail Metrics

To avoid optimizing for conversion at the expense of customer experience, the following guardrail metrics are monitored:

* Refund Rate
* Support Ticket Rate
* Engagement Score
* Revenue Quality
* Segment Performance
* Average Days to Convert



A rollout recommendation will only be made if the North Star Metric improves while guardrail metrics remain within acceptable business thresholds.



# 17\. KPI Tree Explanation

The KPI Tree links the organization's strategic objective of increasing sustainable subscription revenue to measurable operational drivers.



## Business Goal

Increase sustainable subscription revenue through improved customer activation and monetization.



## North Star Metric

**Paid Conversion Rate**

### Primary KPI Drivers



| Driver | Purpose |

|--------|----------|

| Acquisition | Bring qualified users into the onboarding journey |

| Activation | Encourage users to complete onboarding and start trials |

| Monetization | Convert trial users into paying subscribers |
| Retention \& Engagement | Maintain healthy customer behavior after activation |



## Supporting Sub-Drivers

• Landing Page Visit Rate

• Trial Start Rate

• Onboarding Completion Rate

• Average Revenue Per User (ARPU)

• Average Revenue Per Paying User (ARPPU)

• Engagement Score

• Average Days to Convert



# 18\. Experiment Design

The company conducted a randomized A/B experiment.



| Group | Experience |

|-------|------------|

| Control | Existing onboarding experience |

| Treatment | Redesigned onboarding and activation experience |



# 19\. Statistical Methodology

The primary business metric (Paid Conversion Rate) is evaluated using a **Two-Proportion Z-Test** because the outcome is binary (converted vs. not converted) and the experiment compares two independent groups.



The significance level is set at **α = 0.05** with a **95% confidence level**.

A rollout recommendation should only be considered if the observed improvement is statistically significant and supported by healthy guardrail metrics.



# 20\. Segment Analysis

Performance is evaluated across multiple business dimensions:

* Region
* Device Type
* Traffic Source
* Plan Type

Segment-level analysis identifies whether the Treatment performs consistently across the customer base or whether a phased rollout should be considered.



# 21\. Business Risks

While higher conversion is desirable, business decisions should not rely solely on revenue improvement. The following risks must be evaluated before recommending a production rollout:



\- Increased customer refund requests

\- Higher support ticket volume

\- Reduced customer engagement

\- Segment-specific performance decline

\- Revenue quality deterioration

\- Statistical uncertainty due to sampling variation



Evaluating these risks ensures that short-term conversion improvements do not create long-term operational or customer experience challenges.



# 22\. Recommendation Framework

The rollout decision follows this framework:



| Outcome | Recommendation |

|----------|----------------|

| Significant improvement + healthy guardrails | Launch |

| Improvement limited to specific segments | Launch for Selected Segments |

| Mixed or inconclusive evidence | Continue Testing |

| Negative impact on KPIs or guardrails | Do Not Launch |



## 

## 23\. Repository Structure

\---



```text

part2\\\_kpi\\\_experiment/

├── data/

│   └── campaign\\\_experiment\\\_data.xlsx

├── analysis/

│   ├── experiment\\\_analysis.xlsx

│   └── hypothesis\\\_test\\\_notes.md

├── outputs/

│   ├── experiment\\\_summary.xlsx

│   ├── recommendation\\\_memo.md

│   └── kpi\\\_tree.png

├── screenshots/

│   ├── summary\\\_metrics.png

│   ├── hypothesis\\\_test\\\_output.png

│   └── kpi\\\_tree\\\_preview.png

└── README.md

```

## 

## 24\. Project Deliverables

This repository includes:



| Deliverable | Description |

|--------------|-------------|

| Experiment Analysis Workbook | Detailed KPI calculations |

| Experiment Summary Workbook | Executive dashboard |

| KPI Tree | Business KPI hierarchy |

| Recommendation Memo | Executive recommendation |

| README | Project documentation |



# 25\. Assumptions

* Users were randomly assigned to Control and Treatment groups.
* Experimental data accurately represents user behavior.
* Binary fields are correctly encoded.
* Revenue values are recorded consistently.
* Sample size is sufficient for statistical inference.



# 26\. Limitations

* Analysis is limited to the experimental period.
* Long-term retention and churn are outside the scope.
* External seasonality and marketing effects are not explicitly
evaluated.
* Results should be validated after production rollout through ongoing
KPI monitoring.



## 

## 27\. Future Enhancements

Potential follow-up analyses include:

* Multi-variant onboarding experiments
* Personalized onboarding journeys
* Region-specific optimization
* Device-specific onboarding improvements
* Pricing and subscription experiments
* Long-term retention analysis
* Customer lifetime value modelling



# 28\. References

The analysis methodology is based on established A/B testing, KPI framework, and business analytics practices. All findings are derived from the provided experiment dataset and documented calculations within this repository.



# 29\. Executive Conclusion

This project demonstrates how KPI frameworks, business experimentation, and statistical analysis can be integrated into executive decision-making. Rather than relying solely on conversion improvement, the recommendation considers commercial impact, customer experience, operational guardrails, and statistical evidence to ensure sustainable business growth.



The framework developed in this repository provides leadership with a structured, evidence-based approach for evaluating future product experiments and making informed rollout decisions.

## 

## 30\. Repository Status



| Deliverable | Status |

|-------------|--------|

| Data Validation | ✅ Completed |

| KPI Framework | ✅ Completed |

| Experiment Analysis | ✅ Completed |

| Statistical Hypothesis Testing | ✅ Completed |

| Executive Recommendation | ✅ Completed |

| Documentation | ✅ Completed |

