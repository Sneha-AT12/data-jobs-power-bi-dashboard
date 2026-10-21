<h1 align="center">📊 Data Jobs Dashboard (Power BI)</h1>

<p align="center">
  <b>An interactive Power BI dashboard to explore job volume, salary, hiring trends and job details across data roles.</b><br>
  Built with drill-through, bookmarks, buttons and cross-filtering.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-Measures-4C72B0" alt="DAX">
  <img src="https://img.shields.io/badge/Drill--Through-Enabled-217346" alt="Drill-through">
  <img src="https://img.shields.io/badge/Bookmarks-Navigation-F37626" alt="Bookmarks">
</p>

<hr>

<h2>📑 Table of Contents</h2>

<ol>
  <li><a href="#overview">Overview</a><br></li>
  <li><a href="#questions">The Questions</a><br></li>
  <li><a href="#tools">Tools &amp; Features Used</a><br></li>
  <li><a href="#dashboard">The Dashboard</a><br></li>
  <li><a href="#interactivity">Interactivity: How the Visuals Work Together</a><br></li>
  <li><a href="#insights">Key Insights</a><br></li>
  <li><a href="#learned">What I Learned</a><br></li>
  <li><a href="#challenges">Challenges I Faced</a><br></li>
  <li><a href="#run">How to Use This Project</a><br></li>
  <li><a href="#acknowledgements">Acknowledgements</a><br></li>
  <li><a href="#conclusion">Conclusion</a></li>
</ol>

<hr>

<h1 id="overview">🔎 Overview</h1>

<h3>Welcome to my Data Jobs Dashboard.</h3>

<p>
This project turns about <b>479K data job postings</b> into an interactive Power BI report.
A reader can see how many jobs exist, what they pay, how hiring changed during 2024, and then <b>drill into any job title</b> for a detailed view.
Clicking one visual filters all the others, so the dashboard answers follow-up questions instantly.
</p>

<details>
  <summary><b>👉 Click to see what the dashboard includes</b></summary>
  <br>
  <ul>
    <li><b>KPI cards:</b> job count, salary star rating, median yearly salary and median hourly salary</li>
    <li><b>Line chart:</b> job postings trend in 2024 with a trendline</li>
    <li><b>Scatter plot:</b> hourly vs. yearly salary by job title</li>
    <li><b>Bar chart and table:</b> job titles compared by volume and pay, with data bars and sparklines</li>
    <li><b>Drill-through page:</b> a detailed page for one job title</li>
    <li><b>Slicers:</b> job title and posting date range</li>
  </ul>
</details>

<br>

<h1 id="questions">❓ The Questions</h1>

<h3>Below are the questions I wanted this dashboard to answer:</h3>

<ol>
  <li><b>How many data jobs are there, and what is the typical salary?</b></li>
  <br>
  <li><b>How did job postings change through 2024?</b></li>
  <br>
  <li><b>Which job titles pay the most, and how do hourly and yearly pay compare?</b></li>
  <br>
  <li><b>For one job title, what is the pay by country, which platform has the most jobs, and what are the job types?</b></li>
  <br>
  <li><b>How common are remote work, health insurance and "no degree" mentions?</b></li>
</ol>

<br>

<h1 id="tools">🛠️ Tools &amp; Features Used</h1>

<table align="center">
  <thead>
    <tr>
      <th align="left">Tool / Feature</th>
      <th align="left">Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr><td><b>📈 Power BI Desktop</b></td><td>Building the report</td></tr>
    <tr><td><b>🧮 DAX measures</b></td><td>Median yearly salary, median hourly salary, job count and percentages</td></tr>
    <tr><td><b>🔽 Slicers</b></td><td>Filtering by job title and posting date</td></tr>
    <tr><td><b>🔗 Drill-through</b></td><td>Opening a detailed page for the selected job title</td></tr>
    <tr><td><b>🔖 Bookmarks</b></td><td>Saving views and controlling navigation</td></tr>
    <tr><td><b>🔘 Buttons (including Back)</b></td><td>Moving between pages and returning to the main dashboard</td></tr>
    <tr><td><b>🎯 Cross-filtering</b></td><td>Clicking one visual updates all the others</td></tr>
    <tr><td><b>🎨 Visual formatting</b></td><td>Rounded cards, gauges, donuts, treemap and consistent colors</td></tr>
    <tr><td><b>🔀 Git &amp; GitHub</b></td><td>Version control and sharing the project</td></tr>
  </tbody>
</table>

<br>

<h1 id="dashboard">📈 The Dashboard</h1>

<h2>1️⃣ Main Dashboard: overview of all data jobs</h2>

<p>
The first page shows the big picture: how many jobs exist, what they pay, how hiring moved through 2024, and how each job title compares.
</p>

<p align="center">
  <img src="https://github.com/Sneha-AT12/data-jobs-power-bi-dashboard/blob/7252763847a1a4d887eff9a61cbd88e5e62a4a7f/1_main_dashboard.png" width="850" alt="Main Power BI dashboard showing all data jobs">
</p>
<p align="center"><i>Main page: 479K jobs, median yearly salary $113K and median hourly salary $47.62.</i></p>

<hr>

<h2>2️⃣ Drill-Through Page: one job title in detail</h2>

<p>
Right-click a job title and choose <b>Drill through</b> to open a page for that title only.
This page shows its median pay, remote work, degree and health insurance shares, pay by country, the platforms with the most jobs, and the types of jobs.
The <b>back button</b> in the top-left corner returns to the main page.
</p>

<p align="center">
  <img src="images/2_drill_through.png" width="850" alt="Drill-through page for Data Scientist">
</p>
<p align="center"><i>Drill-through page for "Data Scientist" with a posting date slicer.</i></p>

<hr>

<h2>3️⃣ Cross-Filtering: selecting a visual changes the rest</h2>

<p>
When I select <b>Data Analyst</b> and <b>Senior Data Analyst</b>, every other visual updates:
the job count, the salary cards, the trend line, the scatter plot and the table all show only those two titles.
</p>

<p align="center">
  <img src="images/3_cross_filter.png" width="850" alt="Dashboard filtered to Data Analyst and Senior Data Analyst">
</p>
<p align="center"><i>The same dashboard after selecting two job titles: 128K jobs, $93K median yearly salary and $32.50 median hourly salary.</i></p>

<br>

<h1 id="interactivity">🖱️ Interactivity: How the Visuals Work Together</h1>

<ol>
  <li><b>Slicer:</b> choose a job title from the dropdown (or "All") and the whole page updates.</li>
  <br>
  <li><b>Click to filter:</b> click a bar, a dot or a table row, and the other visuals react (cross-filtering).</li>
  <br>
  <li><b>Drill through:</b> right-click a job title to open its detail page.</li>
  <br>
  <li><b>Back button:</b> on the detail page, click the arrow to return to the main dashboard.</li>
  <br>
  <li><b>Bookmarks and buttons:</b> navigation buttons and saved views let the reader move around without using the menu.</li>
</ol>

<br>

<h1 id="insights">💡 Key Insights</h1>

<ul>
  <li>The dataset has <b>479K postings</b> with a median yearly salary of about <b>$113K</b> and a median hourly salary of about <b>$48</b>.</li>
  <li><b>Machine Learning Engineer</b> has the highest median yearly salary in the table ($155,000), followed by <b>Senior Data Engineer</b> ($146,500) and <b>Software Engineer</b> ($145,000).</li>
  <li><b>Data Analyst</b> has the lowest median ($90,000) but one of the largest numbers of postings (113K).</li>
  <li><b>Data Engineer</b> has the most postings (129K) and a high median salary ($126,268).</li>
  <li>Job postings <b>trended down through 2024</b>, from a peak of about 55K early in the year to a low of about 14K, then rose again at the end of the year.</li>
  <li>For <b>Data Scientist</b>, the median is about <b>$125K</b> per year. Only about <b>14%</b> of postings mention remote work, <b>6%</b> mention no degree, and <b>16%</b> mention health insurance.</li>
  <li>Among the four countries shown for Data Scientist, the <b>United Kingdom</b> has the highest median salary and <b>France</b> the lowest.</li>
  <li><b>LinkedIn</b> is the leading platform for these jobs, and <b>Full-time</b> is the most common job type.</li>
</ul>

<br>

<h1 id="learned">🎓 What I Learned</h1>

<ol>
  <li><b>Dashboard design:</b> a clear layout with KPI cards at the top and details below tells the story quickly.</li>
  <br>
  <li><b>DAX:</b> medians, counts and percentages need measures that respond to filters.</li>
  <br>
  <li><b>Drill-through:</b> a separate detail page keeps the main dashboard simple.</li>
  <br>
  <li><b>Bookmarks and buttons:</b> these give the report an app-like feel and easy navigation.</li>
  <br>
  <li><b>Cross-filtering:</b> choosing the right visual interactions makes the report feel connected.</li>
</ol>

<br>

<h1 id="challenges">🧗 Challenges I Faced</h1>

<ol>
  <li><b>Messy data:</b> the raw data needed cleaning before the visuals were reliable.</li>
  <br>
  <li><b>Medians in DAX:</b> medians behave differently from sums and averages, so measures needed testing.</li>
  <br>
  <li><b>Too many visuals:</b> I had to decide what belongs on the main page and what belongs on the drill-through page.</li>
  <br>
  <li><b>Consistent design:</b> aligning rounded cards, colors and fonts across pages.</li>
</ol>

<br>

<h1 id="run">▶️ How to Use This Project</h1>

<ol>
  <li>Download <code>Data_Jobs_Dashboard.pbix</code> from this repository.</li>
  <br>
  <li>Open it in <b>Power BI Desktop</b> (free to download from Microsoft).</li>
  <br>
  <li>Use the <b>Job_title</b> slicer, click visuals to cross-filter, and right-click a job title to <b>drill through</b>.</li>
  <br>
  <li>Use the <b>back button</b> to return to the main page.</li>
</ol>

<h3>📁 Project Structure</h3>

```text
📦 data-jobs-power-bi-dashboard
 ┣ 📂 images/
 ┃ ┣ 🖼️ 1_main_dashboard.png
 ┃ ┣ 🖼️ 2_drill_through.png
 ┃ ┗ 🖼️ 3_cross_filter.png
 ┣ 📈 Data_Jobs_Dashboard.pbix
 ┗ 📄 README.md
```

<br>

<h1 id="acknowledgements">🙏 Acknowledgements</h1>

<p>
The data comes from the data jobs dataset used in
<a href="https://lukebarousse.com">Luke Barousse's</a> data analytics courses.
The data model, DAX measures, dashboard design and written insights in this repository are my own work.
</p>

<br>

<h1 id="conclusion">✅ Conclusion</h1>

<p>
This dashboard shows how Power BI can turn hundreds of thousands of job postings into a clear, interactive story.
With slicers, cross-filtering, drill-through, bookmarks and buttons, a reader can move from the big picture to a single job title in a few clicks.
</p>

<hr>

<p align="center">⭐ If you found this project useful, please consider giving it a star!</p>
