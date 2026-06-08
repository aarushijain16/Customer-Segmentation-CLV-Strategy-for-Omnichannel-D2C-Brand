# Customer Segmentation & CLV Strategy for Omnichannel D2C Brand
### Inspired by Nicobar - Indian Lifestyle & Design Brand
### Python · Power BI · K-Means · CLV Modelling · RFM Analysis

---

## Overview

This project builds an omnichannel customer segmentation and CLV framework 
for a premium lifestyle D2C brand - modelled on the business context of 
Nicobar, an Indian design-led omnichannel retailer.

Using publicly available retail data and synthetically generated omnichannel 
behaviour, I built a customer insight system that connects segmentation, 
lifetime value signals, loyalty risk, and product affinity - designed to 
support CRM strategy, retention planning, and merchandising decisions.

**Tools:** Python (Pandas, NumPy, Scikit-learn) · Power BI · K-Means · 
PCA · CLV Proxy Modelling · Feature Engineering

---

## Business Problem

Premium D2C brands face a specific scaling challenge: their customers are 
not homogeneous. A brand like Nicobar has brand loyalists, occasional 
premium buyers, discount-driven shoppers, and at-risk advocates - all 
with completely different retention needs.

Key questions this project addresses:

- Who are the highest-value customer segments and what drives their loyalty?
- Which customers are at churn risk despite being brand-aligned?
- How do online and in-store behaviours differ across segments?
- How can CRM strategy move beyond discounts toward relationship-driven growth?

---

## Analytical Approach

**Customer Segmentation & Personas**
- Behavioural clustering using K-Means and PCA
- Segmentation across spend, frequency, engagement, and channel mix
- Five customer personas defined:
  - Engaged Regulars
  - Transitional Shoppers
  - Premium but At-Risk
  - Occasional Premiums
  - Price-Sensitive Shoppers

**CLV & Loyalty Signal Modelling**
- CLV proxy modelling by cluster
- Loyalty and churn-risk scoring
- Engagement index based on visit frequency and interaction depth

**Channel & Experience Analysis**
- Online vs. in-store behaviour comparison
- Basket size, dwell time, and visit frequency by segment
- Cross-channel optimisation opportunities

**Product Affinity & Intent Mapping**
- Category co-purchase and affinity analysis
- Product groupings mapped to lifestyle intents 
  (e.g., Hosting, Comfort Living, Gifting)
- Insights to guide curated collections and personalisation

**Strategic Reporting**
- Power BI dashboard built for brand, CRM, and growth teams
- Strategy deck synthesising findings into actionable priorities

---

## Key Findings

**High-value, low-frequency buyers drive ~30% of revenue**
RFM and CLV modelling revealed that a small segment of high-value, 
low-frequency customers - those who buy rarely but spend significantly 
when they do - contributed approximately 30% of total revenue. These 
customers require a completely different retention approach than 
frequent buyers.

**~25% of the customer base is silently at churn risk**
A quarter of the customer base was identified as "At-Risk" - brand-aligned 
customers showing declining engagement signals. Personalised reactivation 
without discount dependency is the highest-impact intervention for this group.

**Loyalty correlates with engagement frequency, not spend**
Customers who engaged more frequently - visiting, browsing, interacting - 
showed stronger long-term retention regardless of basket size. This shifts 
the loyalty programme design from spend-based rewards toward 
community and access-driven incentives.

**Occasional Premiums have the highest untapped CLV potential**
This segment buys infrequently but at premium price points. CLV modelling 
showed they represent the largest upside if converted to higher frequency 
through experiential retention - events, exclusive previews, 
editorial storytelling.

**Product affinity clusters align with lifestyle intent, not categories**
Co-purchase analysis revealed customers shop by lifestyle moment 
(Hosting, Comfort Living, Gifting) rather than product category. 
This has direct implications for collection curation, cross-sell 
sequencing, and content strategy.

---

## Strategic Recommendations

- Build persona-led CRM journeys - different messaging, cadence, 
  and offer logic for each of the five segments
- Shift loyalty programme design from spend-based to 
  access-and-experience-based
- Prioritise Occasional Premiums for experiential retention 
  (events, previews, community)
- Use engagement signals - not just purchase history - to identify 
  brand loyalists before they churn
- Align merchandising and content with lifestyle intent clusters, 
  not product categories
- Monitor segment migration monthly via Power BI dashboard

---

## Modelled Business Impact

*All impacts are modelled estimates based on publicly available and 
synthetically generated data, scaled to reflect real-world D2C brand economics.*

| Segment Insight | Strategic Opportunity |
|---|---|
| ~30% revenue from high-value low-frequency buyers | CRM nudges + micro-collection strategy |
| ~25% at-risk but brand-aligned | Personalised reactivation without discounting |
| Engagement > spend as loyalty driver | Community-led loyalty programme redesign |
| Occasional Premiums - highest CLV upside | Experiential retention investment |

---

## Tools & Technologies

| Tool | Usage |
|---|---|
| Python (Pandas, NumPy, Scikit-learn) | Segmentation, CLV modelling, feature engineering |
| K-Means + PCA | Behavioural clustering and dimensionality reduction |
| Power BI | Executive dashboard and segment monitoring |
| Synthetic data generation | Omnichannel behaviour simulation |

---

## Dataset Note

This project uses publicly available retail datasets and synthetically 
generated omnichannel behaviour data. Insights are framed to reflect 
real-world D2C brand strategy. This is an analytical framework 
demonstration, not a real business engagement.

---

*Part of the E-Commerce & Supply Chain Analytics Portfolio*
*[View full portfolio](https://aarushijainnportfolio.netlify.app/)*
