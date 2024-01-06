# Distributions Repository

This repository contains implementations and examples of various probability distributions commonly used in statistics.

## Included Distributions

### Normal Distribution
The Normal distribution, also known as the Gaussian distribution, is a continuous probability distribution that is symmetric and bell-shaped. It's characterized by its mean and standard deviation.

Use Case: **Quality Control in Manufacturing**

**Analysis**: Analyze data to find the lifespan of the bulbs follows a Normal distribution with a mean (average) of 1000 hours and a standard deviation of 50 hours.

**Quality Control**: Using this distribution, we can set quality control standards. For instance, we might decide that any bulb that lasts less than 950 hours or more than 1050 hours is considered defective.

**Decision Making**: Whenever we produce a batch of bulbs, we randomly select a few from the batch and test their lifespan. By assuming a Normal distribution and using statistical tools, we can confidently make decisions about whether the batch meets their quality standards without testing every single bulb.

**Improvement**: If we notice a shift in the distribution (perhaps bulbs consistently lasting less than 950 hours), they can investigate their manufacturing process to identify and rectify any issues causing this deviation.


### Binomial Distribution
The Binomial distribution describes the number of successes in a fixed number of independent Bernoulli trials, each with the same probability of success.

Use Case: **Quality Control in Production**

**Analysis**: Analysis of a production line shows that a specific machine produces defective items with a probability of 0.1 (10% chance of being defective).

**Quality Standards**: Using the Binomial distribution, the company sets quality standards. For example, they decide that in a batch of 20 items produced by this machine, if more than 3 items are defective, the batch will be rejected.

**Sampling and Inspection**: To check quality, the company randomly selects batches of 20 items and inspects the number of defective items. By applying the Binomial distribution and statistical tools, they can decide whether to accept or reject the batch based on the number of defects found.

**Process Improvement**: If they notice a trend where more batches exceed the limit of defective items, they investigate the machine's performance or the production process to rectify issues causing higher defect rates.

In this scenario, the Binomial distribution assists in setting quality standards, making decisions on batch acceptance, and identifying areas for process improvement in manufacturing by analyzing the probability of defective items in a batch.

### Poisson Distribution
The Poisson distribution models the number of events occurring within a fixed interval of time or space, given a known average rate of occurrence.

Use Case: **Traffic Flow Analysis**

**Analysis**: Analyze traffic flow data on a particular road junction, finding that the number of cars passing through during a 5-minute interval follows a Poisson distribution with an average rate of 10 cars per 5 minutes.

**Prediction and Planning**: Using this distribution, traffic management can predict the likelihood of heavy traffic at different times. For instance, they anticipate that during rush hour, the probability of more than 15 cars passing through the junction in 5 minutes is quite high based on the Poisson distribution parameters.

**Resource Allocation**: Based on these predictions, the local authorities can allocate resources, such as traffic police or signal adjustments, to manage congestion during peak times more efficiently.

**Response to Anomalies**: If there are consistent instances of more than 20 cars passing through the junction in 5 minutes during non-peak hours, the authorities investigate to understand the reasons behind this anomaly. It might be due to a new business opening nearby or road closures diverting traffic.

In this scenario, the Poisson distribution helps in analyzing and predicting traffic flow, allocating resources effectively, and responding to unexpected fluctuations in traffic patterns.


