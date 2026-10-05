<div align="center">

  <h1>🌍 Global Sales Operations Analytics Dashboard</h1>
  <p><b>An End-to-End Enterprise Power BI Dashboard analyzing sales operations, hourly demand trends, product categories, and multi-regional market performance.</b></p>

  <!-- Clean Tech Stack Badge Bar -->
  <p align="center">
    <code>🟡 Power BI</code> &nbsp;|&nbsp; 
    <code>🔵 Power Query & ETL</code> &nbsp;|&nbsp; 
    <code>🟢 Advanced DAX</code> &nbsp;|&nbsp; 
    <code>🟣 Time-Intelligence & Hourly Analytics</code> &nbsp;|&nbsp; 
    <code>🚗 Regional Operations</code>
  </p>

</div>

<hr />
<br />

<h2>📌 Project Overview</h2>
<p>
  This project delivers an interactive <b>Global Sales Operations Dashboard</b> designed to optimize sales strategies, analyze regional performance across major markets (e.g., USA, Australia), and evaluate time-based transactional patterns down to specific product categories like Classic Cars.
</p>
<p>
  <b>Business Objective:</b> Empower sales operations managers and regional directors to identify high-converting product segments, streamline peak-hour inventory, and execute precision regional targeting.
</p>

<br />

<h2>📊 Executive Operations Dashboard</h2>
<p>The primary interactive interface featuring core operational metrics, global territory performance, and category distributions:</p>

<div align="center">
  <img src="https://i.postimg.cc/GtKfYBT6/dashbwrd.png" alt="Global Sales Operations Dashboard" width="100%" />
</div>

<br />
<hr />
<br />

<h2>🔑 Operational Key Performance Indicators (KPIs)</h2>
<ul>
  <li><b>Total Revenue / Sales:</b> Overall financial revenue across global operational territories.</li>
  <li><b>Order Volume & Quantities:</b> Total sales orders fulfilled and units delivered.</li>
  <li><b>Average Order Value (AOV):</b> Mean sales generated per single transaction ticket.</li>
  <li><b>Time & Hourly Patterns:</b> Peak transactional volume analysis across different time windows.</li>
</ul>

<br />
<hr />
<br />

<h2>🛠️ Analytics Architecture & Pipeline Stages</h2>

<h3>Stage 1: ETL & Data Transformation (Power Query)</h3>
<p>
  Raw operational records were transformed using <b>Power Query</b> to cleanse missing entries, adjust field data types, extract custom time/date dimension attributes, and structure transaction logs for analytical efficiency.
</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Power Query ETL Engine</h4>
        <img src="https://i.postimg.cc/nr2W7s9S/data-bawr-kwyry.png" width="95%" alt="Power Query Transformation" />
      </td>
      <td width="50%" align="center" valign="top">
        <h4>Cleaned Data View & Attributes</h4>
        <img src="https://i.postimg.cc/brg5bGS5/data.png" width="95%" alt="Transformed Data View" />
      </td>
    </tr>
  </table>
</div>

<br />

<h3>Stage 2: DAX Calculations & Time Analytics</h3>
<p>Engineered core measure tables and time intelligence calculations:</p>
<ul>
  <li><code>Total Revenue</code> = <code>SUM(Sales[LineTotal])</code></li>
  <li><code>Average Order Value</code> = <code>DIVIDE([Total Revenue], [Total Orders], 0)</code></li>
  <li><code>Hourly Peak Analysis</code> = Dynamic measures mapping transactions across daily operational hours.</li>
</ul>

<br />
<hr />
<br />

<h2>🎯 Deep Slicing & Operational Scenarios</h2>

<h3>1. Time-Based & Hourly Demand Analytics</h3>
<p>Evaluating purchasing behavior across specific operating hours and daily time slots:</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Global Time Distribution View</h4>
        <img src="https://i.postimg.cc/brg5bGSW/dashbwrd-balwqt.png" width="95%" alt="Global Time Analytics" />
        <p align="left"><small>Monitors order volumes across daily operating hours globally.</small></p>
      </td>
      <td width="50%" align="center" valign="top">
        <h4>Regional Time Trends (Australia)</h4>
        <img src="https://i.postimg.cc/2yrJVdyM/balwqt-w-astralya.png" width="95%" alt="Australia Time Distribution" />
        <p align="left"><small>Isolates time-of-day purchase trends specifically for the Australian market.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />

<h3>2. Category & Territory Cross-Filtering</h3>
<p>Granular cross-filtering isolating specific product lines and geographic markets:</p>

<div align="center">
  <table border="0" width="100%">
    <tr>
      <td width="50%" align="center" valign="top">
        <h4>Classic Cars Category in USA</h4>
        <img src="https://i.postimg.cc/qqwFntC4/fltr-klasyk-kar-w-amryka.png" width="95%" alt="Classic Cars USA Slicer" />
        <p align="left"><small>Filters performance for Classic Cars within the United States market.</small></p>
      </td>
      <td width="50%" align="center" valign="top">
        <h4>Vehicles Category in Australia (2005)</h4>
        <img src="https://i.postimg.cc/kGsH8Vt7/fltr-alʿrbyat-wastralya-w-2005.png" width="95%" alt="Australia Vehicles 2005 Slicer" />
        <p align="left"><small>Multi-tiered slicing combining product line, region, and fiscal year 2005.</small></p>
      </td>
    </tr>
  </table>
</div>

<br />
<hr />
<br />

<h2>💡 Strategic Recommendations & Insights</h2>
<ol>
  <li><b>Product Line Focus:</b> Classic Cars represent a major revenue anchor; marketing spend in the USA should prioritize this high-converting category.</li>
  <li><b>Regional Operations Optimization:</b> Align Australian fulfillment shifts with peak purchasing hours to minimize dispatch lead times.</li>
  <li><b>Inventory Allocation:</b> Maintain optimized safety stock levels for top vehicle lines during high-volume seasonal spikes identified in historical analysis.</li>
</ol>

<br />
<hr />
<br />

<h2>📂 Repository Architecture</h2>
<pre>
├── Data/                        # Raw operational & sales datasets
├── Reports/                     # Global_Sales_Operations_Analytics.pbix
├── Screenshots/                 # Operational dashboard walkthroughs
└── README.md                    # Project documentation
</pre>
