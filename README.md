<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<div align="center">
  <a href="https://medium.com/@yassinezamit26">
    <img src="https://img.shields.io/badge/Medium-Read%20Articles-brightgreen" alt="Medium" />
  </a>
  <a href="https://www.youtube.com/c/@automationworld8336">
    <img src="https://img.shields.io/badge/YouTube-Subscribe%20Now-red" alt="YouTube" />
  </a>
    <a href="https://www.linkedin.com/in/yassine-zamit/">
    <img src="https://img.shields.io/badge/LinkedIn-Follow%20Me-blue" alt="LinkedIn" />
  </a>

</div>




<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="Pizza%20Sales%20Images/pizza-slice.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Carbon FootPrint Analysis </h3>

  <p align="center">
    Comprehensive analysis of pizza sales data, driven by interactive visualizations and insights
    <br />
    <a href="https://github.com/yassineeea/Pizza-Sales-Analysis/blob/main/KPIreport.docx"><strong>Explore the docx »</strong></a>
    <br />
    <br />
    
    
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#Problem Statement">Problem Statement</a>
      <ul>
        <li><a href="#KPI requirements">KPI requirements</a></li>
        <li><a href="#CHARTS REQUIREMENT">CHARTS REQUIREMENT</a></li>
      </ul>
    </li>
    <li><a href="#Project Workflow">Project Workflow</a>
      <ul>
        <li><a href="#Data Collection and Preparation">Data Collection and Preparation</a></li>
              <ul>
                 <li><a href="#Data Source">Data Source</a></li>
                 <li><a href="#Data Cleaning">Data Cleaning</a></li>
              </ul>
      </ul>
      <ul>
        <li><a href="#Data Analysis with SQL">Data Analysis with SQL</a></li>
              <ul>
                 <li><a href="#Exploratory Data Analysis (EDA)">Exploratory Data Analysis (EDA)</a></li>
                 <li><a href="#KPI Calculation">KPI Calculation</a></li>
                 <li><a href="#Trend Analysis">Trend Analysis</a></li>
              </ul>
      </ul>   
      <ul>
        <li><a href="#Data Visualization with Power BI">Data Visualization with Power BI</a></li>
              <ul>
                 <li><a href="#Dashboard Creation">Dashboard Creation</a></li>
              </ul>
      </ul> 
      <ul>
        <li><a href="#Business Insights and Reporting">Business Insights and Reporting</a></li>
      </ul>         
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project 📚


[![Pizza Sales Analysis Screenshot](https://github.com/yassineeea/Carbon-FootPrint/blob/main/CarbonDashboard/Dash1.png)](https://example.com)


The Pizza Sales Analysis project aimed to explore and understand sales trends, customer preferences, and performance across different pizza categories and sizes. By analyzing a comprehensive dataset of pizza sales, the project sought to uncover insights that could help optimize inventory management, improve marketing strategies, and enhance overall sales performance.

#### Goals 🎯
* Identify Top Performers🥇: Determine which pizza categories and sizes contribute most to total revenue and orders.
* Analyze Sales Trends📈: Understand the daily, weekly, and monthly trends in pizza orders to optimize supply chain and marketing efforts.
* Customer Insights🕒: Identify peak order times and high-demand periods to align business strategies accordingly.



### Built With ⛏️🧑🏽‍💻
To navigate the data analyst job market, I enlisted a powerful toolkit:

- **[![SQL][SQL-badge]][SQL-url]** served as the foundation, enabling me to explore and clean database to extract valuable insights.
- **[![Microsoft SQL Server Management Studio][SSMS-badge]][SSMS-url]** Provided a familiar environment for database interaction and executing SQL queries.
- **[![Power BI][PowerBI-badge]][PowerBI-url]** Utilized for creating interactive dashboards.
- **[![Git][Git-badge]][Git-url] [![GitHub][GitHub-badge]][GitHub-url]** ensured seamless version control and collaboration by allowing me to track changes and share my SQL scripts and analysis.





<!-- Badges and URLs -->
[SQL-badge]: https://img.shields.io/badge/SQL-MySQL-orange
[SQL-url]: https://www.mysql.com/

[Jupyter-badge]: https://img.shields.io/badge/Jupyter%20Notebook-F37626.svg?logo=jupyter&logoColor=white
[Jupyter-url]: https://jupyter.org/

[SSMS-badge]: https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white
[SSMS-url]: https://docs.microsoft.com/en-us/sql/ssms/sql-server-management-studio-ssms

[Git-badge]: https://img.shields.io/badge/Git-F05032.svg?logo=git&logoColor=white
[Git-url]: https://git-scm.com/

[GitHub-badge]: https://img.shields.io/badge/GitHub-181717.svg?logo=github&logoColor=white
[GitHub-url]: https://github.com/

[PowerBI-badge]: https://img.shields.io/badge/Power%20BI-F2C811.svg?logo=power-bi&logoColor=black
[PowerBI-url]: https://powerbi.microsoft.com/

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Problem Statement -->
## Problem Statement 📝
### 1. KPI requirements 📌
We need to analyze key indicators for our pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:
- **Total Revenue:** The sum of the total price of all pizza orders.
- **Average Order Value:** The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
- **Total Pizzas Sold:** The sum of the quantities of all pizzas sold.
- **Total Orders:** The total number of orders placed.
- **Average Pizzas Per Order:** The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders

### 2. CHARTS REQUIREMENT 📊

We would like to visualize various aspects of our pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts:

- **Daily Trend for Total Orders:** Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctuations in order volumes on a daily basis.

- **Monthly Trend for Total Orders:** Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high order activity.

- **Percentage of Sales by Pizza Category:** Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall sales.


<!-- USAGE EXAMPLES -->
## Project Workflow 🚀


### 1. Data Collection and Preparation 🗂️

#### Data Source🌐: 

#### Data Cleaning🧹:

### 2. Data Analysis with SQL 🔍
#### * Exploratory Data Analysis (EDA)🔎:
I Performed initial data exploration using SQL queries to understand the distribution of data and identify any anomalies.
#### * KPI Calculation📊:
I Wrote SQL queries to calculate the required KPIs such as Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders, and Average Pizzas Per Order.
- **1. Total Revenue:** This query calculates the sum of the total price of all pizza orders.:
```sql
SELECT SUM(total_price)
AS TotalPrice from pizza_sales;
```
- **2. Average Order Value:** This query calculates the average amount spent per order, calculated by dividing the total revenue by the total number of orders.
```sql
select SUM(total_price)/count(DISTINCT(order_id)) as AverageOrderValue 
from pizza_sales;
```
- **3. Total Pizza Sold:** This query calculates the sum of the quantities of all pizzas sold.
```sql
SELECT SUM(quantity) as TotalPizzaSold 
FROM pizza_sales;
```
- **4. Total Orders:** This query calculates the total number of orders placed.
```sql
SELECT count(distinct(order_id)) as TotalOrders 
FROM pizza_sales;
```
- **5. Average Pizza Per Order :** This query calculates
```sql
select CAST(SUM(quantity) as decimal(10,2)) / CAST(count(distinct order_id) as decimal(10,2)) 
as AveragePizzaPerOrder  
from pizza_sales;
```

#### * Trend Analysis📈:
I Used SQL to extract data for daily and monthly trends, enabling the creation of the necessary charts in Power BI.
- **1. Daily Trend of orders :** This query calculates the total number of distinct orders for each day of the week. .
```sql
SELECT DATENAME(DW, order_date)  as order_date , count(distinct order_id) as totalorders     
FROM pizza_sales 
GROUP BY DATENAME(DW, order_date);
```
- **2. Monthly Trend of orders  :** This query calculates the total number of distinct orders for each month.
```sql
SELECT DATENAME(Month, order_date)  as order_date , count(distinct order_id) as totalorders     
FROM pizza_sales 
GROUP BY  DATENAME(Month, order_date);
```
- **3. Percentages of sales per category  :** This query calculatesThis query calculates the percentage of total sales for each pizza category.
```sql
SELECT pizza_category, SUM(total_price)*100 / (select SUM(total_price)
FROM pizza_sales)  as TotalPrice 

FROM pizza_sales
GROUP BY pizza_category;
```
- **4. Top 5 pizzas by revenue   :** This query calculates the total revenue for the top 5 pizza names, ordered by revenue in descending order.
```sql
SELECT TOP 5 pizza_name, Sum(total_price) as TotalRevenue 
FROM pizza_sales 
GROUP BY pizza_name
ORDER BY TotalRevenue DESC;
```
### 3. Data Visualization with Power BI 📊
- **Dashboard Creation:** Leveraging Power BI, I transformed the processed data into interactive, insightful dashboards that provide a comprehensive view of pizza sales performance over time.  
[![Pizza Sales Analysis Screenshot](https://github.com/yassineeea/Pizza-Sales-Analysis/blob/main/Pizza%20Sales%20Images/PizzaDash.png)](https://example.com)

 
[![Pizza Sales Analysis Screenshot](https://github.com/yassineeea/Pizza-Sales-Analysis/blob/main/Pizza%20Sales%20Images/pizzadash2.png)](https://example.com)


### 4. Business Insights and Reporting 🧠

- **Actionable Insights:** The visualized data provides actionable insights that can drive strategic decisions, such as optimizing inventory for the best-selling pizzas, revising marketing strategies for underperforming products, and adjusting pricing models based on customer demand patterns.

- **Performance Monitoring:** These dashboards enable continuous performance monitoring, allowing stakeholders to track progress against sales targets, identify potential issues early on, and respond swiftly to changes in market conditions.



<!-- CONTACT -->
## Contact

Yassine Zamit - [linkedin-url]: https://linkedin.com/in/yassine-zamit/ - yassinezamit26@gmail.com

Project Link: [https://github.com/yassineeea/Pizza-Sales-Analysis](https://github.com/yassineeea/Pizza-Sales-Analysis)




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/yassine-zamit/
[medium-shield]: https://img.shields.io/badge/Medium-Read%20Articles-brightgreen
[medium-url]: https://medium.com/@yassinezamit26
[youtube-shield]: https://img.shields.io/badge/YouTube-Subscribe%20Now-red
[youtube-url]: https://www.youtube.com/c/@automationworld8336
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 

