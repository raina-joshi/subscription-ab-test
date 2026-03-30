# subscription-ab-test
A/B test simulation analyzing pricing impact on conversion and retention using Python

## Objective
Evaluate whether a pricing change improves conversion without negatively impacting retention.

## Approach
- Simulated A/B test (control vs treatment)
- Measured conversion and retention
- Applied statistical testing (z-test for proportions)
- Defined conversion as the primary metric and retention as a guardrail metric

## Results
- Conversion: 11.9% → 13.9% (+2.1pp, significant)
- Retention: decreased by ~2pp, but the difference was not statistically significant (p > 0.05)
- Overall retained users increased
- Cohort analysis showed consistent retention patterns across signup periods

## Conclusion
The treatment increased conversion from 11.9% to 13.9% (+2.1pp), and this uplift was statistically significant (p < 0.05).
Retention decreased slightly by ~2pp, but the result was not statistically significant (p > 0.05), indicating no strong evidence of negative impact.
Overall, the treatment resulted in a higher number of retained users, suggesting a net positive effect.

## Recommendation
Roll out the pricing change while continuing to monitor retention over time to ensure no long-term negative impact.
