#  Udacity_Gaussian

## Overview
This project, a part of the Introduction to Object-Oriented Programming course at Udacity, focuses on analyzing Gaussian and Binomial distributions. Originally part of the AWS Machine Learning Foundations Course, it offers a practical approach to understanding these statistical concepts through programming.

Key Features:
- Reading datasets
- Calculating mean and standard deviation
- Plotting histograms and probability density functions
- Adding Gaussian and Binomial distributions

The project structure includes a base class `Distribution` and two derived classes `Gaussian` and `Binomial`.

## Class Diagram
![class_diagram_2.png](images/class_diagram_2.png)

## Installation
To install this package, run the following command:

pip install distributions-EH


## Usage

To use this package, first import the required classes:
```python
from distributions import Gaussian, Binomial
```

For Gaussian distributions, you can create an instance and use various methods:

```
# Create Gaussian instance
gaussian_one = Gaussian(25, 2)

# Calculate mean and standard deviation
mean = gaussian_one.mean
standard_deviation = gaussian_one.stdev

# Plot histogram
gaussian_one.plot_histogram()

# Add another Gaussian distribution
gaussian_two = Gaussian(30, 3)
gaussian_sum = gaussian_one + gaussian_two
```

Similarly, for Binomial distributions:

```
# Create Binomial instance
binomial_one = Binomial(.4, 20)

# Calculate mean and standard deviation
mean = binomial_one.mean
standard_deviation = binomial_one.stdev

# Plot histogram
binomial_one.plot_histogram()

# Add another Binomial distribution
binomial_two = Binomial(.5, 30)
binomial_sum = binomial_one + binomial_two
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

Special thanks to Udacity and the AWS Machine Learning Foundations Course for the initial inspiration and guidance in creating this project.

---

This README is a work in progress and will be updated with more details and usage instructions. Thank you for your interest in Udacity_Gaussian!


