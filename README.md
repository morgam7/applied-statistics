# Applied Statistics
**Author:** Marcella Morgan
**Image Credit:** Images generated with the help of ChatGPT (OpenAI).

![Cover Image](images/student_with_curve.png)

This is the repository for my project for the Applied Statistics module of the [Higher Diploma in Science in Data Analytics given by ATU Galway-Mayo](https://www.gmit.ie/higher-diploma-in-science-in-computing-in-data-analytics). My lecturer was [Ian McLoughlin](https://github.com/ianmcloughlin).

In this project, I demonstrate skills learned throughout the module, including using 

## Getting Started

To get started with this repository, you’ll need:  
1. **Python**: Install Python (I recommend using [Anaconda](https://www.anaconda.com/), which includes all the necessary tools and libraries).  
2. **A Notebook Editor**: I used Visual Studio Code, but you can also use [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/).  



## Why This Project Is Useful
This project is aimed at showcasing how to . 

It might also help future students of the Applied Statistics module understand how to approach the tasks and project.

## Libraries Used
Here are the main libraries and tools I used in the project:
- **Pandas**: For data manipulation and analysis, including reading and summarising JSON weather files.
- **Matplotlib**: For visualising the weather data, such as temperature trends.
- **NumPy**: For numerical operations used in the analysis.

A `requirements.txt` file is included in the root of the repository. It lists all the Python dependencies needed to run this project.

To install the dependencies, follow these steps:

1. Ensure you have Python and pip installed on your system.
2. Navigate to the project directory in your terminal.
3. Run the following command to install all the required packages:

```bash
pip install -r requirements.txt
```

## Problem 1 Lady Testing Tea:

This problem plays with the famous Lady Tasting Tea experiment, where instead of 8 cups (4 tea-first, 4 milk-first), we now prepare 12 cups (8 tea-first, 4 milk-first). A participant claims they can identify which pouring order was used. Using numpy, we simulate the experiment by shuffling the cups and calculating the probability of correctly identifying all cups by chance. We then compare this probability with the original 8-cup experiment and discuss whether the statistical significance threshold (p-value) might reasonably be adjusted for the larger design.


## Problem 2 Standard Deviation:

Here, we explore the difference between sample standard deviation (ddof=1) and population standard deviation (ddof=0). We generate 100,000 samples of size 10 from the standard normal distribution and compute both standard deviations for each sample. By plotting the two sets of results on the same axes, we can visually compare the distributions and see how the correction for sample size affects variability. Finally, we consider how these differences are expected to change if the sample size is increased, connecting the simulation to statistical theory.




## Problem 3:

This problem focuses on type II error rates in hypothesis testing. We vary the difference in means (d = 0 to 1.0) between two normal distributions (sample size = 100 each). For each scenario, we simulate 1,000 independent t-tests, recording the proportion of times the null hypothesis is not rejected (type II error). Plotting these error rates against the mean differences illustrates how the probability of failing to detect a real effect declines as the true difference increases. This exercise emphasizes the relationship between effect size, sample size, and statistical power.


## Problem 4:

The goal here is to compare ANOVA with multiple independent t-tests when analyzing differences across more than two groups. We generate three normal samples of size 30 each, with means 0, 0.5, and 1. After performing a one-way ANOVA, we also run three pairwise t-tests (group 1 vs 2, 1 vs 3, 2 vs 3). The results are compared, highlighting how ANOVA efficiently tests for differences across all groups simultaneously, avoiding the inflation of type I error that arises when running multiple t-tests independently.


## Getting Help
If you have questions about this repository or the project, feel free to contact me at [contactmarcellamorgan@gmail.com](mailto:contactmarcellamorgan@gmail.com). Alternatively, you can submit an issue via GitHub issues.

## Resources
I relied on Python libraries like pandas and matplotlib throughout these assignments. Additional references include:
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- I also used Chat GPT when I found myself stumped. It was useful at explaining very specific problems I was having quickly, but it also got a few things wrong! 

### General Environment Issues:


### Git and GitHub:
 

### Python and Pandas:
  



## END
