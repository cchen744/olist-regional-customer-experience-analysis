# olist-regional-customer-experience-analysis
## 1. Business Context
Olist is a large e-commerce platform operating across Brazil, connecting sellers and customers nationwide. As the platform continues to expand into new markets and scale its operations, maintaining a consistent and satisfactory customer experience becomes increasingly critical.

Customer reviews provide direct signals of user dissatisfaction and potential friction points in the order fulfillment process. However, it is currently unclear whether negative customer experiences are evenly distributed across regions or concentrated in specific areas, which may pose a risk to sustainable growth if left unaddressed.

## 2. Business Objective
The objective of this analysis is to examine whether negative customer reviews exhibit spatial concentration across regions and, if so, to identify which regions should be prioritized for further attention. In addition, the analysis aims to explore potential factors associated with this spatial pattern of dissatisfaction, in order to support more targeted follow-up investigations.

## 3. Key Business Questions
**Question 1**: Is customer dissatisfaction, as reflected by negative reviews, evenly distributed across regions, or does it exhibit spatial concentration? If spatial concentration exists, which regions show the highest levels of negative reviews?

**Question 2**: Within regions with a high concentration of negative reviews, is there evidence of an association between negative reviews and delivery performance, such as longer delivery times?

## 4. Data Scope
Data sources: Brazilian E-Commerce Public Dataset by Olist (from Kaggle)

Geographic level: [to be specified]

Time coverage: [to be specified]

## 5. Metric Definitions
**Customer Experience Metrics**

Metric 1: regional proportion of negative reviews

Metric 2: [to be specified]

**Delivery Performance Metrics**

Metric 1: average delivery time

Metric 2: [to be specified]

**Business Scale / Context Metrics**

Metric 1: Order Volume (by region)

Metric 2: Seller Count / Seller Density (by region)

## 6. Analytical Plan
**Step 0**: Establish regional baseline metrics by aggregating negative review rate, average delivery time, and seller density at the state level.

**Step 1**: Identify regions with disproportionately high levels of customer dissatisfaction based on region-level negative review metrics.

**Step 2**: Examine the relationship between delivery performance and negative reviews using correlation-based analysis, with a focus on:
          
          - Overall regional-level patterns
          
          - Subset of regions identified as high-dissatisfaction regions in Step 1
          
**Step 3**: Analyze seller–customer distance patterns to assess whether geographic separation may help explain delivery performance differences across regions.

**Step 4**: If delivery performance does not sufficiently explain the observed pattern, explore additional factors such as product category and price level to assess their association with negative reviews.

## 7. Expected Insights 

**Expected insight type 1**: Identification of regions with systematically higher proportions of negative reviews, indicating relatively lower customer satisfaction.

**Expected insight type 2**: Assessment of whether delivery performance is significantly associated with negative reviews in high-complaint regions.

**Expected insight type 3**: [to be specified]

## 8. Decision Implications
The results of this analysis are expected to support the prioritization of regions for further operational investigation, helping the company determine where attention should be focused first rather than applying uniform strategies across all markets.

## 9. Scope and Limitations
This project focuses on identifying regional patterns of customer dissatisfaction and exploring factors associated with negative reviews. It does not attempt to prescribe specific operational solutions, such as logistics optimization or delivery process redesign, as these actions require additional data and cross-functional input beyond the scope of this analysis.

## 10.Deliverables
Deliverable 1: spatial distribution of negative reviews, delivery time, order volume, and seller density.

Deliverable 2: [to be specified]

Deliverable 3: [to be specified]

## 11. Success Criteria
[to be specified]


