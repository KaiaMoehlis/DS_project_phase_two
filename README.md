# DS_project_phase_two

## Part 1 

### Problem Motivation
Rising college tuition costs have become a major concern for students and families, influencing decisions about higher education affordability and accessibility. Public universities often charge significantly different tuition rates for in-state and out-of-state students, but the extent of these differences and the factors driving them remain important areas of study. Additionally, tuition rates may be shaped by economic factors such as a state’s cost of living, as well as institutional characteristics like acceptance rates and national rankings. By analyzing tuition data across universities, this project aims to uncover patterns and relationships that impact college affordability, providing insights that can inform students, policymakers, and educators in making data-driven decisions about higher education costs.

### Key Research Questions
1. How much more do top universities charge for out-of-state students compared to in-state students?
2. Is there a relationship between a state's cost of living and the tuition rates of its universities?
3. Do universities with lower acceptance rates or higher rankings tend to have higher tuition costs?

### Motivating Sources
- [The Student's Guide to In-State vs. Out-of-State Tuition (BestColleges)](https://www.bestcolleges.com/resources/in-state-vs-out-of-state-tuition/?)
- [Trends in College Pricing (College Board)](https://research.collegeboard.org/trends/college-pricing)
- [National Center for Education Statistics(NCES)](https://nces.ed.gov/)

### Summary of the Data Processing Pipeline
1. Web scrape to get the raw data
2. Clean the data to prepare the data frame for visualization and analysis
3. Visualize using plotting libraries, such as Seaborn, Plotly, and Matplotlib

Web scraping will be used to collect datasets on average college costs by state ([source](https://educationdata.org/average-cost-of-college-by-state/)), state cost of living ([source](https://www.niche.com/colleges/search/best-colleges/)), and college acceptance rates (source). Once gathered, the raw data will be processed and cleaned to ensure consistency and accuracy before being saved as .csv files for further analysis in Jupyter notebook. The datasets will then be merged using common identifiers, such as state names and university names, to establish connections between tuition costs and influencing factors. To identify trends, we will generate visualizations using Seaborn, Plotly, and Matplotlib. A scatter plot will illustrate the relationship between tuition rates and cost of living, while a heatmap will highlight how tuition varies based on university rankings and acceptance rates.

