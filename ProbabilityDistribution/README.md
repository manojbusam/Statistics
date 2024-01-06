# Probability Distributions

This repository contains implementations and examples of various probability distributions commonly used in statistics.

## Included Distributions

### 1. Normal Distribution
The Normal distribution, also known as the Gaussian distribution, is a continuous probability distribution that is symmetric and bell-shaped. It's characterized by its mean and standard deviation.

Use Case: **Normal Distribution in eCommerce: Product Delivery Times**

**Analysis**: Analyzing historical data, the eCommerce platform observes that delivery times for a specific product category follow a Normal distribution with a mean delivery time of 3 days and a standard deviation of 0.5 days.

**Quality Control**: Using this distribution, the platform sets quality control standards. For instance, they consider any delivery taking longer than 4 days or less than 2 days as a deviation from the expected delivery time.

**Decision Making**: When monitoring new deliveries, the platform assesses whether the delivery time falls within the expected range (based on the Normal distribution parameters) to ensure customer satisfaction. This helps in deciding whether to investigate potential delays or discrepancies in delivery times.

**Improvement**: If there's a consistent shift in delivery times (e.g., more deliveries taking longer than 4 days), the platform investigates operational processes, logistics, or external factors affecting delivery to rectify and optimize the delivery system.

In this scenario, leveraging the Normal distribution aids in setting quality standards, making decisions about delivery times, and identifying areas for improvement in managing product deliveries within the eCommerce platform.

![Screenshot 2024-01-05 at 11 36 59 PM](https://github.com/manojbusam/Statistics/assets/44409170/d02ef9af-53ae-46c6-88a9-a30031e505aa)

### 2. Uniform Distribution
The Uniform distribution represents a continuous probability distribution where all outcomes within a given range are equally likely.

Use Case: **Uniform Distribution in eCommerce: Product Pricing Strategy**

**Analysis**: Analyzing pricing data for a specific product category, the eCommerce platform identifies that prices for products in this category follow a Uniform distribution between $20 and $50.

**Price Control**: Utilizing this distribution, the platform sets pricing control guidelines. For instance, they ensure that no product is priced below $20 or above $50 to maintain a balanced pricing structure within the category.

**Pricing Decisions**: When introducing new products or adjusting prices, the platform ensures that the proposed price falls within the predefined range based on the Uniform distribution parameters. This helps in maintaining competitive yet consistent pricing for the category.

**Market Strategy**: By understanding the Uniform distribution of prices, the platform might strategically promote products priced closer to the lower or upper bounds to attract different segments of customers seeking varying price ranges.

**Analysis and Optimization**: If there's a notable shift in the distribution (e.g., products consistently priced at the extremes), the platform analyzes market trends or consumer behavior to optimize the pricing strategy within the defined range.

In this scenario, leveraging the Uniform distribution aids in maintaining pricing control, making informed pricing decisions, devising market strategies, and optimizing product pricing within the eCommerce platform.

![Screenshot 2024-01-05 at 11 37 30 PM](https://github.com/manojbusam/Statistics/assets/44409170/04525069-1e8f-48a5-9039-814350b3c810)

### 3. Cauchy Distribution
The Cauchy distribution is a continuous probability distribution characterized by its symmetric bell-shaped curve with heavier tails than the Normal distribution.

### Use Case: Cauchy Distribution in eCommerce Shipping

**Analysis**: Analyzing historical shipping data, the eCommerce platform discovers that shipping times for a specific product category follow a Cauchy distribution with a median shipping time of 5 days and a scale parameter of 1 day.

**Quality Control**: Using this distribution, the platform sets quality control parameters for shipping times. They establish that any shipping duration exceeding 10 days will be flagged for investigation, acknowledging the Cauchy distribution's potential for longer outliers.

**Decision Making**: When monitoring new shipments, the platform assesses whether the shipping duration surpasses the predefined threshold (based on the Cauchy distribution parameters). This assists in making decisions about whether to investigate potential delays beyond the expected range.

**Improvement**: If there's a consistent increase in shipments exceeding the quality control threshold (e.g., more shipments taking longer than 10 days), the platform investigates operational processes, logistics, or external factors impacting shipping to rectify and optimize the delivery system.

In this scenario, utilizing the Cauchy distribution aids in quality control by setting thresholds, making decisions based on predefined parameters, and identifying areas for improvement within the eCommerce platform's shipping processes.

![Screenshot 2024-01-05 at 11 43 18 PM](https://github.com/manojbusam/Statistics/assets/44409170/aaf6416d-c96a-4bf8-b203-7202569f468e)

### 4. t Distribution
The t-distribution, also known as Student's t-distribution, is a continuous probability distribution that resembles the Normal distribution but is characterized by heavier tails, allowing for a better representation of uncertainty in small sample sizes.

### Use Case: t Distribution in Market Research Survey Analysis

**Analysis**: Analyzing survey data from a market research study, researchers find that the distribution of respondent ages follows a t-distribution with a mean age of 35 and a scale parameter that accounts for the uncertainty in the sample.

**Statistical Inference**: Utilizing the t-distribution, researchers conduct hypothesis testing to determine if the average age of respondents differs significantly from the expected value. The t-distribution accounts for the smaller sample size's increased uncertainty compared to a Normal distribution.

**Decision Making**: When evaluating the impact of age on product preferences, marketers rely on the t-distribution to calculate confidence intervals for age groups, helping make informed decisions regarding targeted marketing strategies.

**Sample Size Consideration**: Recognizing the importance of sample size, especially in small surveys, researchers use the t-distribution to determine the minimum sample size required for future studies to achieve desired confidence levels in age-related analysis.

In this scenario, the t-distribution is instrumental in statistical inference, aiding decision-making processes, and considering the uncertainties associated with smaller sample sizes in market research analysis.

![Screenshot 2024-01-05 at 11 45 59 PM](https://github.com/manojbusam/Statistics/assets/44409170/a4d327ed-f456-4ebe-a860-7f7eda9519d3)

### 5. F Distribution
The F-distribution, named after Sir Ronald Fisher, is a continuous probability distribution that arises in the analysis of variances and ratios of sample variances. It's commonly used in statistics, particularly in analysis of variance (ANOVA) and regression analysis.

### Use Case: F Distribution in ANOVA for Product Testing

**Analysis**: Performing an ANOVA test for evaluating the effectiveness of three different fertilizer brands on crop yield, researchers observe that the distribution of crop yield ratios among the fertilizer groups follows an F-distribution.

**Statistical Testing**: Using the F-distribution, researchers perform ANOVA to assess if there are significant differences in crop yield means among the fertilizer groups. The F-test determines if the variance between group means is larger than expected by chance.

**Decision Making**: Based on the ANOVA results, agricultural scientists decide whether there's sufficient evidence to conclude that at least one fertilizer brand significantly differs in crop yield compared to the others, aiding in informed decisions for agricultural practices.

**Model Comparison**: In regression analysis, the F-distribution is employed to compare nested linear models, determining if adding additional predictor variables significantly improves the model's fit.

In this scenario, the F-distribution plays a crucial role in statistical testing, aiding in decision-making processes regarding fertilizer effectiveness and model comparison in regression analysis for agricultural research.

![Screenshot 2024-01-05 at 11 47 04 PM](https://github.com/manojbusam/Statistics/assets/44409170/e0eb5159-1969-40ba-97dd-e166d6b59579)


### 6. Chi-Square Distribution
The Chi-Square distribution is a continuous probability distribution that arises in statistics and is widely used in hypothesis testing and confidence interval construction, particularly in tests of independence and goodness of fit.

### Use Case: Chi-Square Distribution in Goodness-of-Fit Test

**Analysis**: Conducting a goodness-of-fit test to assess if observed data fits an expected distribution, statisticians observe that the distribution of observed frequencies across categories follows a Chi-Square distribution.

**Hypothesis Testing**: Using the Chi-Square distribution, statisticians perform hypothesis tests to determine if there's a significant difference between the observed and expected frequencies in categorical data. This aids in understanding if the observed data fits the expected distribution or not.

**Quality Control**: In manufacturing, the Chi-Square distribution is applied to assess whether the observed frequency of defective items in different categories significantly deviates from the expected defect rate, helping in quality control processes.

**Association Testing**: In social sciences, the Chi-Square distribution is utilized to test for association or independence between categorical variables in surveys or studies.

In this scenario, the Chi-Square distribution is fundamental in hypothesis testing, quality control, and association analysis, aiding in making informed decisions based on observed categorical data in various fields such as statistics, manufacturing, and social sciences.


![Screenshot 2024-01-05 at 11 48 13 PM](https://github.com/manojbusam/Statistics/assets/44409170/169d28a6-88c8-4cf5-bbb8-ab8d09e550d8)
