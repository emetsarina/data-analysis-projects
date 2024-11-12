# Decision-Making Based on Business Metrics

## Description of the project  
We will conduct an analysis of a large online store. Together with the marketing department, was prepared a list of hypotheses to increase revenue.  

## Research Objectives  
- Prioritize hypotheses  
- Perform and analyze A/B test results  

## Tasks Required for Analyzing A/B Test Results:  
- Plot cumulative revenue by groups.  
- Plot cumulative average order value by groups.  
- Plot the relative difference in cumulative average order value between Group B and Group A.  
- Plot cumulative conversion rate by groups.  
- Plot the relative difference in cumulative conversion rate between Group B and Group A.  
- Create a scatter plot of the number of orders per user.  
- Calculate the 95th and 99th percentiles of orders per user to determine thresholds for identifying outlier users.  
- Create a scatter plot of order values.  
- Calculate the 95th and 99th percentiles of order values to set thresholds for identifying outlier orders.  
- Calculate the statistical significance of conversion differences between the groups based on "raw" data.  
- Calculate the statistical significance of differences in average order value between the groups based on "raw" data.  
- Calculate the statistical significance of conversion differences between the groups based on "cleaned" data.  
- Calculate the statistical significance of differences in average order value between the groups based on "cleaned" data.  
- Draw conclusions and make assumptions.

## Description of the data
**Data for Part One**  

**File /datasets/hypothesis.csv**  
- `Hypothesis` — brief description of the hypothesis;  
- `Reach` — user reach on a scale of 1 to 10;  
- `Impact` — impact on users on a scale of 1 to 10;  
- `Confidence` — confidence in the hypothesis on a scale of 1 to 10;  
- `Efforts` — resources required to test the hypothesis on a scale of 1 to 10. The higher the Efforts value, the more expensive the hypothesis testing.  

**Data for Part Two**  

**File /datasets/orders.csv**  
- `transactionId` — order ID;  
- `visitorId` — ID of the user who placed the order;  
- `date` — date the order was placed;  
- `revenue` — order revenue;  
- `group` — A/B test group to which the order belongs.  

**File /datasets/visitors.csv**  
- `date` — date;  
- `group` — A/B test group;  
- `visitors` — number of users on the specified date in the specified A/B test group.

## Tools
`Python`, `Pandas`, `SciPy`, `Matplotlib`, `A/B test` 


