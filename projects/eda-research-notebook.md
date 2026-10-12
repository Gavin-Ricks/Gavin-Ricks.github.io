# EDA Research Notebook: Online vs. Offline Learning

- **One-line summary:** A Jupyter research notebook that tests whether online or offline learning leads to different test scores, and finds the difference is statistically significant.
- **When:** July 2026
- **Where / program:**  Virtual Internship Morehouse Broadening Participation in Computing Center SBX Summer Python Program.
- **My role:** Solo
- **Tools:** Python, Jupyter Notebook, Pandas, NumPy, SciPy, Matplotlib

## The problem

Does the way students learn, online or in person, relate to how they score on tests? I wanted to use a provided dataset to find out whether the data supports a real difference or whether it could just be noise.

## What I did

1. Loaded the provided dataset and cleaned it so the analysis ran on consistent, usable records.
2. Explored the data with summary statistics and visualizations to see how scores were distributed across online and offline groups.
3. Ran several statistical tests to check for a correlation between learning format and test scores.
4. Compared the results across tests to see whether they pointed to the same conclusion.
5. Wrote up the findings in the notebook with the code, charts, and reasoning together.

## Results

- The correlation between online vs. offline learning and test scores was **statistically significant** according to the data in favor of my alternative hypothesis (Offline learning was better)
- Dataset size: 1,000 student records (from my poster)
- Key test(s) and p-value(s): t-test, t-statistic = -3.579, p = 0.00036 (from my poster)
- Average score difference between groups: [4]
- Number of visualizations: 6

## What I learned

- Statistical significance and practical importance are not the same thing, so I need to look at effect size as well as p-values.
- Running more than one type of test and checking that they agree makes a conclusion more trustworthy.
- A clear notebook that explains each step is as important as the result itself.
- [ADD: anything else you took away, like a limitation of the dataset]

## Images

- `images/Gavin_Ricks_Poster.pdf` : This is the poster

## Links

- Code: https://github.com/Gavin-Ricks/SBX-PROJECTS
- Poster or slides: in images
