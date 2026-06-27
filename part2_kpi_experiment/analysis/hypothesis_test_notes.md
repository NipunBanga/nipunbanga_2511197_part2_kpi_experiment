# Hypothesis Test Notes

## Business Objective

Evaluate whether the redesigned onboarding experience improves the Paid
Conversion Rate without negatively affecting customer experience.

## Business Question

Should the Treatment onboarding experience be rolled out to all users?

## North Star Metric

**Paid Conversion Rate**

## Hypotheses

### Null Hypothesis (H0)

The Treatment onboarding experience does not improve the Paid Conversion
Rate compared with the Control experience.

### Alternative Hypothesis (H1)

The Treatment onboarding experience improves the Paid Conversion Rate
compared with the Control experience.

## Test Selection

**Two-Proportion Z-Test**

### Why this test?

-   Binary outcome (Paid / Not Paid)
-   Two independent groups
-   Randomized A/B experiment

## Significance Level

-   α = 0.05
-   Confidence Level = 95%

## Decision Rule

-   Reject H0 if p-value \< 0.05.
-   Otherwise, fail to reject H0.

## Assumptions

-   Random assignment
-   Independent observations
-   Adequate sample size
-   Valid binary values

## Guardrail Metrics

-   Refund Rate
-   Support Ticket Rate
-   Engagement Score
-   Days to Convert
-   Revenue Quality

## Business Interpretation

A statistically significant increase in Paid Conversion Rate is not
sufficient on its own. The final recommendation must also consider
guardrail metrics and segment-level performance before a full rollout
decision is made.
