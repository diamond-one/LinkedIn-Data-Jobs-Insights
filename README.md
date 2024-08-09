# LinkedIn Data Jobs Insights

## Project Overview

In the fast-paced world of data, knowing where the opportunities lie is crucial. This project digs into LinkedIn job postings across Europe, focusing on data roles like Data Analysts, Data Engineers, and Machine Learning Engineers. The goal? To uncover trends in the job market—what skills are in demand, which titles are hot, and where these jobs are concentrated.

## Why It Matters

If you're looking to stay ahead in your career, make informed hiring decisions, or understand the landscape, this analysis is for you:
- **Key Skills:** What must you know to stay competitive?
- **Industry Trends:** Which sectors are leading the charge in hiring data professionals?
- **Geographic Focus:** Where should you be looking for your next opportunity?

This isn't just about crunching numbers—it's about providing you with actionable insights that can improve your career or business strategy.

## Installation

To get this project up and running locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights.git
    ```
2. Navigate to the project directory:
    ```sh
    cd LinkedIn-Data-Jobs-Insights
    ```
3. Set up a virtual environment:
    ```sh
    python -m venv env
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        .\env\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source env/bin/activate
        ```
5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To explore the analysis, just start up the Jupyter Notebook:

1. Launch Jupyter:
    ```sh
    jupyter notebook
    ```
2. Open `LinkedIn_Data_Jobs_Insights.ipynb` and run through the cells to dive into the insights.

## What You'll Find

### 📊 Industry Breakdown for Data Roles

Data jobs aren't limited to tech companies. I've analyzed how roles like Data Analyst and Machine Learning Engineer are distributed across industries like finance, healthcare, and beyond. You'll see which sectors are investing heavily in data talent and which are catching up.

[Read more about industry trends in the full analysis report.](https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights/blob/main/Analysis%20Report.md#trends-in-data-related-job-openings-across-industries)

### 🔍 Competition at Different Career Levels

Whether you're just starting out or have years of experience, knowing where the competition is fiercest can help you strategize your next move. I've looked at how job applications vary by seniority level and what that means for your job search.

[Read more about seniority level competition in the full analysis report.](https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights/blob/main/Analysis%20Report.md#seniority-levels-and-applicant-competition-in-data-jobs)

### 🌍 Hotspots for Data Jobs

Want to know where the action is? We've mapped out the top cities and countries for data roles. Plus, we’ve explored the growing remote work trend and how it's changing the landscape.

[Read more about geographic hotspots in the full analysis report.](https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights/blob/main/Analysis%20Report.md#geographic-distribution-of-data-jobs)

### ⏳ Job Longevity

Some roles fill fast, while others sit open for weeks. We’ve analyzed job postings to understand why certain positions are harder to fill and what might signal about the market.

[Read more about time-to-fill analysis in the full report.](https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights/blob/main/Analysis%20Report.md#time-to-fill-analysis-for-data-jobs)

### 🏢 Company Size and Hiring Trends

Does it matter if you're applying to a startup versus a big corporation? We’ve looked into how company size influences the number and type of data roles available.

[Read more about company size and job openings in the full analysis report.](https://github.com/diamond-one/LinkedIn-Data-Jobs-Insights/blob/main/Analysis%20Report.md#company-size-and-job-openings-in-data)

## Methodology

1. **Data Collection:** Data was scraped from LinkedIn using Selenium to capture real-time job postings; 4800 job postings were gathered for analysis. 
2. **Data Cleaning:** We used pandas to clean and preprocess the data, ensuring it was ready for analysis.
3. **Analysis:** The data was analyzed using statistical techniques to uncover key trends.
4. **Visualization:** To make the insights easy to understand, Visuals were created with Matplotlib and Seaborn.

## Skills Demonstrated

- **Web Scraping:** Efficiently gathered data from LinkedIn using Selenium. The scraper is available [here](https://github.com/diamond-one/Linkedin_Scraper) 
- **Data Wrangling:** Cleaned and prepared large datasets with pandas.
- **Statistical Analysis:** Applied statistical techniques to derive actionable insights.
- **Data Visualization:** Produced clear, insightful visuals with Matplotlib and Seaborn.
- **Python Programming:** Structured, documented Python code that’s easy to follow.

## Contributing

If you want to contribute, here's how you can get involved:

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

Big thanks to the creators and maintainers of:
- [Selenium](https://www.selenium.dev/)
- [pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

---

Whether you're navigating your next career move or trying to get a handle on where the data job market is headed, this project offers a deep dive into the trends shaping the industry. Check out the analysis and see where you can make an impact.
