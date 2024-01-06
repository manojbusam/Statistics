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

### Poisson Distribution
The Poisson distribution models the number of events occurring within a fixed interval of time or space, given a known average rate of occurrence.

## Implementation and Usage
Each distribution has its implementation within this repository, along with examples showcasing how to use these implementations in various scenarios.

### Folder Structure
- `normal_distribution/`: Contains code for the Normal distribution.
- `binomial_distribution/`: Contains code for the Binomial distribution.
- `poisson_distribution/`: Contains code for the Poisson distribution.

### Usage Examples
Within each distribution folder, you'll find code snippets demonstrating how to use the distribution functions and generate random samples from these distributions.

## How to Use
1. Clone the repository to your local machine.
2. Navigate to the desired distribution folder.
3. Follow the instructions in the README provided in each folder for specific usage guidelines and examples.

## Contribution
Contributions are welcome! If you have improvements, additional examples, or new distributions to add, feel free to fork this repository and submit a pull request.

## License
This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
