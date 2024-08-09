# LinkedIn Data Jobs Insights

## Project Description

This project analyzes LinkedIn job postings related to data positions. By scraping and processing job data, we gain insights into the current job market, including the most sought-after skills, common job titles, and geographic distribution of these roles.

## Table of Contents

- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Methodology](#methodology)
- [Skills Demonstrated](#skills-demonstrated)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights.git
    ```
2. Navigate to the project directory:
    ```sh
    cd LinkedIn-Data-Jobs-Insights
    ```
3. Create a virtual environment:
    ```sh
    python -m venv env
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source env/bin/activate
        ```
5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To run the Jupyter Notebook and see the analysis:

1. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```
2. Open the `LinkedIn_Data_Jobs_Insights.ipynb` notebook and run the cells to see the data analysis and visualizations.

## Results

### Trends in Data-Related Job Openings Across Industries

**Narrative Focus**: Explore how demand for data roles like Data Analysts, Data Engineers, and Machine Learning Engineers is distributed across different industries.

**Key Points**:
- Compare the prevalence of data-related job titles in different sectors (e.g., finance, healthcare, technology).
- Highlight industries with emerging demand for data roles.
- Discuss the implications for professionals looking to enter or transition within these fields.

### Seniority Levels and Applicant Competition in Data Jobs

**Narrative Focus**: Investigate the relationship between job seniority levels and the number of applicants for data-related positions.

**Key Points**:
- Analyze which seniority levels (Entry-level, Mid-level, Senior) have the highest number of applicants, indicating competition.
- Discuss the implications for job seekers at different stages of their careers.
- Provide recommendations for candidates on how to stand out in highly competitive seniority levels.

### Geographic Distribution of Data Jobs

**Narrative Focus**: Map out where the jobs in data are located geographically.

**Key Points**:
- Identify major hubs for these job categories in terms of cities and countries.
- Discuss factors that may contribute to these locations being popular for such roles (e.g., local industry presence, tech hubs).
- Explore trends in international opportunities, particularly in the context of remote work.

### Time-to-Fill Analysis for Data Jobs

**Narrative Focus**: Examine how long it takes for jobs in these fields to be filled, using the 'Posted' and 'Collected Date' information.

**Key Points**:
- Identify jobs that have been open for an extended period and hypothesize why (e.g., niche skills required, high seniority level).
- Discuss what this means for job seekers and employers, such as potential skill shortages or the need for more competitive offerings.

### Company Size and Job Openings in Data

**Narrative Focus**: Analyze how the size of the company (number of employees) correlates with job openings in data roles.

**Key Points**:
- Investigate whether larger companies are offering more positions or if smaller companies are also significant players in these job markets.
- Explore how company size influences the types of roles offered (e.g., more specialized roles in larger companies).
- Provide insights into job stability, growth opportunities, and work culture in small vs. large companies.

## Methodology

1. **Data Collection**: Explain how you scraped the data from LinkedIn, including any tools or libraries used (e.g., Selenium).
2. **Data Cleaning**: Describe the steps you took to clean and preprocess the data.
3. **Analysis**: Outline the analytical methods you used to derive insights, such as statistical analysis, clustering, etc.
4. **Visualization**: Mention the visualization tools and techniques used to present the data (e.g., Matplotlib, Seaborn).

## Skills Demonstrated

- **Data Scraping**: Demonstrated ability to scrape data from web sources using tools like Selenium.
- **Data Cleaning and Preprocessing**: Proficiency in using pandas for data manipulation and cleaning.
- **Statistical Analysis**: Applied statistical methods to extract meaningful insights from data.
- **Data Visualization**: Created clear and informative visualizations using Matplotlib and Seaborn.
- **Python Programming**: Showcased expertise in Python through well-structured and documented code.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
5. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Selenium](https://www.selenium.dev/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
