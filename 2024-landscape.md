---
site:
  hide_toc: true
  hide_footer_links: true
---

# 2024 Landscape Analysis

Python is widely adopted in data science, and its use for statistics is expanding rapidly---particularly in education and applied research.
The statistical ecosystem in Python is currently anchored by four major libraries:

- [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html), which provides a comprehensive suite of probability distributions, summary statistics, and basic statistical tests.
- [statsmodels](https://www.statsmodels.org/), which offers tools for econometrics, classical statistics, and statistical modeling---including linear and generalized linear models, time series analysis, and hypothesis testing.
- [scikit-learn](https://scikit-learn.org/), which is best known for machine learning but also supports some statistical modeling, offering a consistent API for predictive analytics and data preprocessing.
- [seaborn](https://seaborn.pydata.org/), a library built on top of matplotlib that excels at creating informative and attractive statistical graphics, making it easier to visualize distributions, relationships, and trends in data.

These core libraries are generally well-tested, reliable, and uphold high software engineering standards, making them trusted foundations for research and application.
They benefit from contributions not only from science users but also from methods and software developers.
Libraries like scikit-learn are especially valued for their clean, consistent interfaces and their integration with the broader Python data stack, which streamlines workflows and enhances usability for both new and experienced users.

While there are many smaller, specialized packages available, the ecosystem remains dominated by these large, general-purpose libraries.
This concentration of resources ensures stability and quality but can also limit the visibility and adoption of innovative or niche statistical tools.
As Python's role in statistics continues to grow, fostering a more diverse and accessible ecosystem will be key to meeting the evolving needs of educators, researchers, and practitioners.
This will also require increased statistics methods developers' participation in the core packages.

# Relationship to Other Languages

R remains the gold standard for statistics, with better branding, a more cohesive ecosystem, and more teaching resources.
R's [tidyverse](https://www.tidyverse.org/) and [RStudio](https://posit.co/products/open-source/rstudio/) provide a smoother and more cohesive user experience for statistics, and CRAN offers a vast repository of statistical packages.
The R ecosystem also benefits from substantial contributions from statistics methods developers.

:::{table} Python vs. R for Statistics
:label: table
:align: center

| Aspect              | Python (Scientific Python)                                                                                                                                   | R (CRAN, tidyverse)                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| Core Libraries      | [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html), [statsmodels](https://www.statsmodels.org/), [scikit-learn](https://scikit-learn.org/) | [base R](https://www.r-project.org/), [tidyverse](https://www.tidyverse.org/), many CRAN packages |
| User Experience     | Fragmented, less cohesive                                                                                                                                    | Cohesive, tidyverse pipelines, RStudio                                                            |
| Teaching Resources  | Improving, but less abundant                                                                                                                                 | Extensive, beginner-friendly                                                                      |
| Community           | Large, less connected in statistics                                                                                                                          | Strong, statistics-focused, welcoming                                                             |
| Package Development | High barriers, less modularity                                                                                                                               | Easy, many small packages, dev tools                                                              |
| Interoperability    | Needs improvement (data structures, APIs)                                                                                                                    | Strong within tidyverse, RStudio                                                                  |
| Branding            | Data science/machine learning focus                                                                                                                          | Statistics-focused                                                                                |

:::

**Interoperability**: While some users switch between Python and R in their workflows, true interoperability is limited.
Most projects use one language at a time, though it is common to leverage R for data manipulation and Python for modeling, or vice versa.

**Other Platforms**: Tools like GraphPad Prism remain popular among practicing scientists for basic statistical analyses, indicating that neither Python nor R fully dominates all applied domains.

# Weaknesses and Needs

Despite Python's strengths, several challenges remain.

- **Fragmentation**: The ecosystem is fragmented, with major libraries (e.g., statsmodels vs. scikit-learn) adopting incompatible APIs and workflows, leading to confusion for users and students.
- **User Experience**: There is no central landing place or unified entry point for statistics in Python, unlike R's [tidyverse](https://www.tidyverse.org/) or RStudio, making it harder for newcomers to get started.
- **Interoperability**: Data structures (such as those from [pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/)) do not always work seamlessly across libraries, requiring conversions and leading to unpredictable function outputs compared to R's tidyverse pipelines.
- **Teaching Resources**: Python lacks the abundance of user-friendly, statistics-focused tutorials and case studies found in the R community.
- **Contributor Barriers**: Contributing to core libraries can be difficult due to high standards and lack of modularity.
  Small, specialized packages exist but are less visible and less widely used than in R.
- **Statistical Methods Coverage**: Some advanced or niche statistical methods are missing or hard to find, especially compared to R's vast [CRAN](https://cran.r-project.org/) repository.
- **Community and Culture**: The Python statistics community is less cohesive and connected than R's, which benefits from a strong identity and established events.

# Conclusion

Python's statistics ecosystem is powerful but fragmented, with significant opportunities for improvement in usability, interoperability, teaching resources, and community cohesion.
While R remains the default for statistics, Python is gaining ground, especially as data science and machine learning continue to grow in influence.
Stronger integration, better documentation, and a more unified vision could help Python become a true peer to R in the statistics domain.
In particular, Python needs:

- A unified, user-friendly interface for statistics, possibly modeled after scikit-learn.
- Improved interoperability between core data structures and libraries.
- More accessible teaching resources and case studies focused on statistics.
- Lower barriers for contributors and greater visibility for specialized statistical packages.
- Stronger community identity and central organization for statistics in Python.

The Statistical Python project seeks to address these needs by fostering collaboration, sharing best practices, and building a sustainable, inclusive community.
As a domain stack within the [Scientific Python project](https://scientific-python.org/), and with support from the NSF POSE Phase I grant, we are committed to making Python a premier platform for statistical computing, education, and research.
