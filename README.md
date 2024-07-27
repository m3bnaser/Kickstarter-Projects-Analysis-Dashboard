### Kickstarter Projects Analysis Dashboard 🎨📊

This Power BI dashboard provides a comprehensive analysis of Kickstarter projects based on a dataset sourced from [Kaggle](https://www.kaggle.com/datasets/kemical/kickstarter-projects). The visualizations offer insights into various aspects of Kickstarter campaigns, including funding, project categories, success rates, and geographic distribution.

#### Data Preparation 🛠️

The dataset consists of two tables:
- **2016 Kickstarter Projects:** Approximately **324K projects**
- **2018 Kickstarter Projects:** Approximately **378K projects**

These tables were merged using Power Query, where data transformation included removing unused columns and handling merge errors by removing and addressing them.

#### Dashboard Overview 🗂️
![Screenshot 2024-07-27 131247](https://github.com/user-attachments/assets/84503c52-feee-4278-bd13-5c69e4d1c6cf)

1. **Total Metrics**
   - **Total Pledged:** **6.48 billion** 💸
   - **Total Goal:** **34 billion** 🎯
   - **Number of Backers:** **3981** 👥
   - **Number of Projects:** **701.78K** 📈

2. **Filters**
   - **Deadline Year:** Allows filtering projects by their deadline year 📅.
   - **Launched Year:** Allows filtering projects by their launch year 🚀.

3. **Visualizations**

   - **Number of Projects by Project Hierarchy:**
     - This bar chart displays the distribution of projects across various categories. The categories with the highest number of projects are:
       - **Film & Video:** **121K** 🎬
       - **Music:** **99K** 🎵
       - **Publishing:** **74K** 📚
       - **Games:** **63K** 🎮
       - **Technology:** **59K** 💻

   - **Total Pledged by Currency:**
     - A donut chart shows the distribution of the total pledged amount by currency. The majority of pledges are in **USD (86.63%)**, followed by **GBP (4.76%)**, **EUR (3.38%)**, **CAD**, and **AUD**.

   - **Total Pledged by Country:**
     - This map visualizes the total pledged amount by country, providing a geographical distribution of Kickstarter funding. The size of the bubbles indicates the magnitude of pledges from each country 🌍. The highest pledges come from the **US, totaling 5.2 billion**.

   - **Number of Projects by State:**
     - A bar chart that categorizes projects based on their state:
       - **Failed:** **365.94K** ❌
       - **Successful:** **247.04K** ✅
       - **Canceled:** **71.13K** 🚫
       - **Live:** **7.23K** 🔴
       - **Undefined:** **7.12K** ❓
       - **Suspended:** **3.33K** ⏸️

   - **Number of Projects by Launched Date:**
     - A line chart shows the monthly trend of launched projects. The peak months for project launches are **July (68K)** and **October (62K)**.

#### Insights 💡

1. **Project Distribution:**
   - The majority of Kickstarter projects fall under the categories of **Film & Video, Music, and Publishing**, indicating a strong preference for creative and artistic ventures on the platform 🎨.

2. **Funding by Currency:**
   - A significant portion of pledges is in **USD**, highlighting the dominance of the **US market** in crowdfunding 💵. This can be important for understanding market focus and currency risks.

3. **Geographical Trends:**
   - The map visualization can help identify key markets for Kickstarter campaigns, allowing project creators to tailor their campaigns based on regional preferences and funding potentials 🌐. The highest amount of pledges comes from the **US, totaling 5.2 billion**.

4. **Project Success Rates:**
   - The high number of **failed projects (365.94K)** compared to **successful ones (247.04K)** indicates that a considerable number of campaigns do not reach their funding goals 📉. This could be useful for analyzing factors that contribute to successful campaigns.

5. **Monthly Launch Trends:**
   - There are noticeable peaks in project launches in **July and October** 📅. Understanding these trends can help in strategic planning for new project launches, aiming to avoid overly competitive periods or to leverage high-traffic times.

#### Usage 🛠️

This dashboard is designed for stakeholders interested in analyzing Kickstarter data, including project creators, backers, and market analysts. By interacting with the filters, users can drill down into specific years and gain detailed insights into the Kickstarter ecosystem.

#### Data Source 📊

The data used in this dashboard is sourced from [Kaggle's Kickstarter Projects dataset](https://www.kaggle.com/datasets/kemical/kickstarter-projects). The dataset includes various attributes related to Kickstarter campaigns, such as project titles, categories, goals, pledged amounts, backer counts, and more.

#### How to Use

1. **Filtering Data:**
   - Use the Deadline Year and Launched Year filters to narrow down the analysis to specific time periods 📆.
   
2. **Interpreting Visuals:**
   - Hover over the charts and maps to see detailed tooltips with additional information ℹ️.
   - Use the insights derived from each visualization to inform decision-making and strategic planning 💼.

3. **Updating Data:**
   - To update the data, replace the dataset in Power BI with the latest version from Kaggle, ensuring that the data schema remains consistent 🔄.

- Mohamed Abdelnaser
- [Linkedin](https://www.linkedin.com/in/3bnaser01/)
